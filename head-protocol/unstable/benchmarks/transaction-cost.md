--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-07 05:21:55.993818939 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.40 | 9.68 | 0.52 |
| 3 | 171 | 747 | 41.59 | 12.03 | 0.61 |
| 4 | 226 | 862 | 50.95 | 14.67 | 0.71 |
| 5 | 282 | 969 | 64.09 | 18.15 | 0.84 |
| 6 | 339 | 1081 | 75.42 | 21.33 | 0.96 |
| 7 | 394 | 1192 | 86.06 | 24.23 | 1.07 |
| 8 | 450 | 1303 | 88.17 | 25.33 | 1.10 |
| 9 | 506 | 1414 | 94.29 | 27.00 | 1.17 |
| 10 | 560 | 1525 | 97.63 | 28.25 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2155 | 28.13 | 10.10 | 0.55 |
| 5| 2327 | 30.29 | 12.03 | 0.58 |
| 10| 3176 | 41.52 | 18.52 | 0.76 |
| 40| 7503 | 95.81 | 53.57 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 22.80 | 7.36 | 0.42 |
| 2| 777 | 25.55 | 8.81 | 0.45 |
| 3| 954 | 26.91 | 9.86 | 0.48 |
| 5| 1165 | 27.97 | 11.46 | 0.51 |
| 10| 1976 | 38.70 | 17.79 | 0.68 |
| 44| 6751 | 95.80 | 56.33 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.09 | 8.89 | 0.48 |
| 2| 855 | 29.93 | 9.83 | 0.50 |
| 3| 911 | 32.76 | 11.24 | 0.54 |
| 5| 1173 | 36.28 | 13.55 | 0.59 |
| 10| 1898 | 45.98 | 19.60 | 0.75 |
| 34| 5719 | 94.06 | 49.18 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.16 | 0.53 |
| 2| 862 | 36.48 | 11.58 | 0.57 |
| 3| 938 | 37.87 | 12.61 | 0.59 |
| 5| 1194 | 42.01 | 15.08 | 0.65 |
| 10| 1944 | 53.41 | 21.61 | 0.82 |
| 28| 4878 | 97.41 | 45.92 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 26.97 | 9.07 | 0.69 |
| 2| 5845 | 31.59 | 10.51 | 0.74 |
| 3| 6118 | 45.07 | 15.15 | 0.89 |
| 4| 6242 | 53.80 | 18.12 | 0.99 |
| 5| 6456 | 64.60 | 21.78 | 1.11 |
| 6| 6528 | 73.75 | 24.78 | 1.21 |
| 7| 6682 | 82.12 | 27.62 | 1.31 |
| 8| 6750 | 93.61 | 31.58 | 1.43 |
| 9| 6773 | 90.69 | 30.36 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 570 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2217 | 7156 | 98.68 | 37.80 | 1.53 |

