--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-01 04:36:36.30483222 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.16 | 11.66 | 0.59 |
| 4 | 226 | 858 | 52.27 | 14.96 | 0.72 |
| 5 | 282 | 969 | 57.73 | 16.66 | 0.78 |
| 6 | 338 | 1081 | 73.03 | 20.75 | 0.94 |
| 7 | 396 | 1192 | 74.48 | 21.50 | 0.96 |
| 8 | 449 | 1303 | 81.44 | 23.67 | 1.04 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.37 | 7.71 | 0.48 |
| 2| 1921 | 25.92 | 8.80 | 0.51 |
| 3| 2134 | 28.40 | 10.19 | 0.55 |
| 5| 2407 | 32.45 | 12.63 | 0.61 |
| 10| 3160 | 41.20 | 18.42 | 0.76 |
| 39| 7300 | 92.81 | 52.08 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.57 | 7.32 | 0.41 |
| 2| 787 | 25.55 | 8.81 | 0.45 |
| 3| 996 | 28.05 | 10.16 | 0.49 |
| 5| 1281 | 30.08 | 12.05 | 0.54 |
| 10| 2155 | 43.95 | 19.25 | 0.74 |
| 40| 6544 | 96.76 | 53.97 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 27.50 | 8.46 | 0.46 |
| 2| 873 | 29.86 | 9.81 | 0.50 |
| 3| 1046 | 32.36 | 11.19 | 0.54 |
| 5| 1292 | 34.93 | 13.22 | 0.58 |
| 10| 1917 | 46.12 | 19.63 | 0.75 |
| 36| 6038 | 98.95 | 51.90 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 996 | 38.66 | 12.84 | 0.60 |
| 5| 1301 | 43.40 | 15.50 | 0.67 |
| 10| 1982 | 53.31 | 21.58 | 0.82 |
| 29| 5023 | 99.77 | 47.23 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 5930 | 35.96 | 12.06 | 0.79 |
| 3| 6185 | 46.00 | 15.49 | 0.91 |
| 4| 6229 | 51.53 | 17.29 | 0.97 |
| 5| 6425 | 61.42 | 20.68 | 1.08 |
| 6| 6510 | 69.29 | 23.33 | 1.16 |
| 7| 6635 | 77.41 | 26.06 | 1.26 |
| 8| 6916 | 93.20 | 31.46 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 572 | 6177 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1707 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

