--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-24 04:51:42.264987103 UTC |
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
| 1| 5837 | 10.86 | 3.46 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10043 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 42.50 | 12.23 | 0.61 |
| 4 | 226 | 862 | 53.84 | 15.36 | 0.73 |
| 5 | 283 | 969 | 56.07 | 16.26 | 0.76 |
| 6 | 338 | 1081 | 68.30 | 19.63 | 0.89 |
| 7 | 394 | 1192 | 76.40 | 21.92 | 0.98 |
| 8 | 449 | 1303 | 96.71 | 27.28 | 1.19 |
| 9 | 506 | 1414 | 98.85 | 28.14 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.00 | 7.62 | 0.48 |
| 2| 1981 | 26.55 | 9.00 | 0.52 |
| 3| 2014 | 26.31 | 9.58 | 0.52 |
| 5| 2381 | 30.99 | 12.24 | 0.59 |
| 10| 3315 | 44.18 | 19.26 | 0.79 |
| 41| 7778 | 99.19 | 55.24 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.57 | 7.32 | 0.41 |
| 2| 699 | 22.62 | 7.96 | 0.42 |
| 3| 995 | 26.06 | 9.59 | 0.47 |
| 5| 1212 | 29.94 | 12.04 | 0.53 |
| 10| 1892 | 37.47 | 17.44 | 0.66 |
| 41| 6723 | 97.64 | 54.86 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 27.54 | 8.47 | 0.46 |
| 2| 778 | 30.94 | 10.07 | 0.51 |
| 3| 977 | 33.43 | 11.45 | 0.55 |
| 5| 1186 | 36.39 | 13.58 | 0.59 |
| 10| 2092 | 45.42 | 19.54 | 0.75 |
| 36| 6115 | 98.43 | 51.79 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.83 | 10.15 | 0.53 |
| 2| 878 | 36.64 | 11.62 | 0.57 |
| 3| 951 | 37.84 | 12.60 | 0.59 |
| 5| 1256 | 42.53 | 15.25 | 0.66 |
| 10| 2095 | 55.02 | 22.10 | 0.85 |
| 29| 4810 | 96.69 | 46.32 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.12 | 9.10 | 0.69 |
| 2| 5911 | 35.88 | 12.03 | 0.79 |
| 3| 6014 | 41.39 | 13.86 | 0.85 |
| 4| 6331 | 56.03 | 18.96 | 1.02 |
| 5| 6303 | 59.64 | 19.98 | 1.05 |
| 6| 6628 | 75.80 | 25.61 | 1.24 |
| 7| 6867 | 86.60 | 29.26 | 1.36 |
| 8| 6837 | 90.46 | 30.50 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

