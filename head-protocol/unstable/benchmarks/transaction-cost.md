--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-06 11:45:11.755116643 UTC |
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
| 1| 5840 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.73 | 4.04 | 0.55 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.18 | 9.20 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 751 | 41.35 | 11.96 | 0.60 |
| 4 | 226 | 858 | 52.61 | 15.07 | 0.72 |
| 5 | 282 | 969 | 56.41 | 16.32 | 0.77 |
| 6 | 336 | 1081 | 63.83 | 18.51 | 0.85 |
| 7 | 393 | 1192 | 77.20 | 22.21 | 0.99 |
| 8 | 451 | 1303 | 83.71 | 24.22 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.37 | 7.71 | 0.48 |
| 2| 1949 | 25.92 | 8.80 | 0.51 |
| 3| 2166 | 29.54 | 10.48 | 0.56 |
| 5| 2366 | 31.37 | 12.33 | 0.60 |
| 10| 3251 | 42.60 | 18.84 | 0.77 |
| 40| 7516 | 96.67 | 53.84 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.84 | 7.38 | 0.42 |
| 2| 862 | 25.49 | 8.79 | 0.46 |
| 3| 995 | 28.33 | 10.23 | 0.50 |
| 5| 1316 | 32.33 | 12.68 | 0.56 |
| 10| 2013 | 40.64 | 18.36 | 0.70 |
| 40| 6498 | 98.33 | 54.35 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.17 | 8.91 | 0.48 |
| 2| 737 | 30.19 | 9.84 | 0.50 |
| 3| 1021 | 31.53 | 10.94 | 0.53 |
| 5| 1396 | 36.51 | 13.69 | 0.61 |
| 10| 2131 | 46.54 | 19.87 | 0.76 |
| 36| 5883 | 94.97 | 50.73 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 33.15 | 9.95 | 0.52 |
| 2| 818 | 35.85 | 11.38 | 0.56 |
| 3| 954 | 37.91 | 12.62 | 0.59 |
| 5| 1364 | 44.03 | 15.70 | 0.68 |
| 10| 2014 | 53.98 | 21.79 | 0.83 |
| 29| 4883 | 98.94 | 46.96 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.13 | 9.10 | 0.69 |
| 2| 5968 | 35.92 | 12.06 | 0.79 |
| 3| 5968 | 40.36 | 13.46 | 0.84 |
| 4| 6163 | 50.44 | 16.94 | 0.95 |
| 5| 6290 | 61.66 | 20.67 | 1.07 |
| 6| 6447 | 65.91 | 22.10 | 1.13 |
| 7| 6722 | 83.19 | 28.11 | 1.32 |
| 8| 6633 | 81.34 | 27.26 | 1.30 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 5 | 283 | 6002 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1138 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2216 | 7155 | 98.24 | 37.65 | 1.53 |

