--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-13 04:42:24.531893373 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 43.44 | 12.44 | 0.62 |
| 4 | 228 | 858 | 49.21 | 14.23 | 0.69 |
| 5 | 282 | 969 | 62.84 | 17.89 | 0.83 |
| 6 | 338 | 1081 | 64.42 | 18.66 | 0.85 |
| 7 | 392 | 1196 | 80.16 | 22.82 | 1.01 |
| 8 | 449 | 1303 | 94.04 | 26.64 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2068 | 27.02 | 9.79 | 0.53 |
| 5| 2419 | 32.19 | 12.57 | 0.61 |
| 10| 3121 | 41.16 | 18.39 | 0.75 |
| 42| 7894 | 99.58 | 56.01 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 22.57 | 7.31 | 0.41 |
| 2| 694 | 22.55 | 7.93 | 0.42 |
| 3| 929 | 26.09 | 9.61 | 0.47 |
| 5| 1228 | 29.86 | 12.01 | 0.53 |
| 10| 1984 | 39.59 | 18.06 | 0.69 |
| 40| 6517 | 96.78 | 53.96 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.98 | 10.08 | 0.51 |
| 3| 1007 | 31.57 | 10.95 | 0.53 |
| 5| 1339 | 35.53 | 13.41 | 0.59 |
| 10| 2161 | 49.64 | 20.72 | 0.80 |
| 37| 6040 | 98.17 | 52.29 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.83 | 10.15 | 0.53 |
| 2| 885 | 36.64 | 11.62 | 0.57 |
| 3| 938 | 37.84 | 12.60 | 0.59 |
| 5| 1260 | 42.53 | 15.25 | 0.66 |
| 10| 2153 | 55.47 | 22.24 | 0.85 |
| 29| 4635 | 94.50 | 45.64 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 26.96 | 9.06 | 0.69 |
| 2| 5845 | 31.52 | 10.48 | 0.74 |
| 3| 6190 | 47.07 | 15.90 | 0.92 |
| 4| 6231 | 51.48 | 17.28 | 0.96 |
| 5| 6450 | 61.35 | 20.65 | 1.08 |
| 6| 6567 | 71.14 | 23.89 | 1.19 |
| 7| 6822 | 81.24 | 27.44 | 1.30 |
| 8| 6853 | 91.96 | 30.96 | 1.42 |
| 9| 6844 | 91.45 | 30.68 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 39 | 2220 | 7160 | 99.12 | 37.95 | 1.54 |

