--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-10 04:49:27.916454344 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νInitial | c8a101a5c8ac4816b0dceb59ce31fc2258e387de828f02961d2f2045 | 2652 | 
| νCommit | 61458bc2f297fff3cc5df6ac7ab57cefd87763b0b7bd722146a1035c | 685 | 
| νHead | a1442faf26d4ec409e2f62a685c1d4893f8d6bcbaf7bcb59d6fa1340 | 14599 | 
| μHead | fd173b993e12103cd734ca6710d364e17120a5eb37a224c64ab2b188* | 5284 | 
| νDeposit | ae01dade3a9c346d5c93ae3ce339412b90a0b8f83f94ec6baa24e30c | 1102 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.42 | 3.93 | 0.54 |
| 3| 6236 | 14.60 | 4.62 | 0.58 |
| 5| 6640 | 19.00 | 6.01 | 0.64 |
| 10| 7650 | 28.90 | 9.10 | 0.79 |
| 43| 14282 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 41.24 | 11.93 | 0.60 |
| 4 | 226 | 858 | 53.64 | 15.29 | 0.73 |
| 5 | 284 | 969 | 62.82 | 17.94 | 0.83 |
| 6 | 339 | 1081 | 73.31 | 20.79 | 0.94 |
| 7 | 393 | 1192 | 76.61 | 22.01 | 0.98 |
| 8 | 451 | 1303 | 95.78 | 27.05 | 1.18 |
| 9 | 506 | 1414 | 90.12 | 26.04 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.29 | 7.69 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2121 | 27.97 | 10.06 | 0.54 |
| 5| 2475 | 33.00 | 12.80 | 0.62 |
| 10| 3214 | 41.85 | 18.60 | 0.76 |
| 39| 7599 | 97.47 | 53.43 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 599 | 22.80 | 7.36 | 0.41 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 874 | 25.05 | 9.32 | 0.46 |
| 5| 1204 | 29.46 | 11.90 | 0.53 |
| 10| 1957 | 38.54 | 17.75 | 0.68 |
| 42| 6650 | 95.75 | 55.04 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 879 | 29.82 | 9.80 | 0.50 |
| 3| 907 | 32.80 | 11.25 | 0.54 |
| 5| 1304 | 37.62 | 13.96 | 0.61 |
| 10| 2161 | 46.77 | 19.95 | 0.77 |
| 36| 5947 | 95.97 | 51.01 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.83 | 10.16 | 0.53 |
| 2| 848 | 36.64 | 11.62 | 0.57 |
| 3| 1004 | 38.62 | 12.83 | 0.60 |
| 5| 1307 | 42.90 | 15.36 | 0.67 |
| 10| 2142 | 55.53 | 22.25 | 0.85 |
| 29| 4812 | 96.59 | 46.30 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.96 | 9.06 | 0.69 |
| 2| 5822 | 31.52 | 10.49 | 0.74 |
| 3| 6066 | 42.57 | 14.29 | 0.86 |
| 4| 6234 | 53.97 | 18.12 | 0.99 |
| 5| 6371 | 63.67 | 21.53 | 1.10 |
| 6| 6362 | 64.91 | 21.69 | 1.11 |
| 7| 6657 | 79.80 | 26.80 | 1.28 |
| 8| 6939 | 94.28 | 31.91 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2276 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2159 | 7121 | 96.88 | 37.08 | 1.51 |

