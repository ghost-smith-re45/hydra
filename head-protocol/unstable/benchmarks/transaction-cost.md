--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-22 06:36:02.900258074 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6042 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 15.14 | 4.81 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10079 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 42.22 | 12.14 | 0.61 |
| 4 | 226 | 858 | 53.58 | 15.25 | 0.73 |
| 5 | 281 | 974 | 56.30 | 16.35 | 0.77 |
| 6 | 339 | 1085 | 75.41 | 21.29 | 0.96 |
| 7 | 396 | 1192 | 74.99 | 21.67 | 0.96 |
| 8 | 450 | 1303 | 91.28 | 25.87 | 1.13 |
| 9 | 504 | 1414 | 91.80 | 26.56 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1924 | 25.47 | 8.70 | 0.50 |
| 3| 2097 | 28.02 | 10.07 | 0.54 |
| 5| 2471 | 32.56 | 12.66 | 0.61 |
| 10| 3336 | 44.79 | 19.42 | 0.80 |
| 39| 7257 | 93.59 | 52.28 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.80 | 7.38 | 0.42 |
| 2| 701 | 22.62 | 7.95 | 0.42 |
| 3| 976 | 26.61 | 9.78 | 0.48 |
| 5| 1263 | 30.62 | 12.23 | 0.54 |
| 10| 1748 | 34.36 | 16.58 | 0.62 |
| 42| 6586 | 98.96 | 55.88 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.09 | 8.89 | 0.48 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 967 | 30.86 | 10.73 | 0.52 |
| 5| 1425 | 36.51 | 13.69 | 0.61 |
| 10| 2134 | 45.38 | 19.53 | 0.75 |
| 35| 5878 | 95.66 | 50.33 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.79 | 10.15 | 0.53 |
| 2| 853 | 36.48 | 11.58 | 0.57 |
| 3| 954 | 37.91 | 12.62 | 0.59 |
| 5| 1271 | 42.68 | 15.29 | 0.66 |
| 10| 2124 | 55.21 | 22.15 | 0.85 |
| 29| 4874 | 97.15 | 46.46 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.09 | 9.10 | 0.69 |
| 2| 5955 | 36.04 | 12.11 | 0.79 |
| 3| 6082 | 44.89 | 15.07 | 0.89 |
| 4| 6296 | 54.66 | 18.42 | 1.00 |
| 5| 6421 | 64.61 | 21.72 | 1.11 |
| 6| 6664 | 75.28 | 25.43 | 1.24 |
| 7| 6760 | 80.24 | 27.03 | 1.29 |
| 8| 7005 | 94.09 | 31.67 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2216 | 7155 | 98.93 | 37.88 | 1.54 |

