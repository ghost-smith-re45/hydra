--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-23 04:49:35.863415143 UTC |
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
| 1| 5834 | 10.35 | 3.28 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.69 | 4.65 | 0.58 |
| 5| 6645 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 29.21 | 9.21 | 0.79 |
| 43| 14281 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 169 | 747 | 41.22 | 11.92 | 0.60 |
| 4 | 227 | 858 | 49.94 | 14.48 | 0.70 |
| 5 | 281 | 969 | 61.09 | 17.50 | 0.81 |
| 6 | 341 | 1085 | 73.25 | 20.81 | 0.94 |
| 7 | 397 | 1196 | 76.60 | 22.01 | 0.98 |
| 8 | 449 | 1303 | 96.64 | 27.26 | 1.18 |
| 9 | 504 | 1414 | 98.49 | 28.00 | 1.21 |
| 10 | 560 | 1525 | 97.07 | 28.17 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 24.00 | 7.62 | 0.48 |
| 2| 1880 | 24.40 | 8.39 | 0.49 |
| 3| 2171 | 29.26 | 10.41 | 0.56 |
| 5| 2326 | 30.38 | 12.05 | 0.58 |
| 10| 3265 | 42.89 | 18.89 | 0.78 |
| 39| 7209 | 91.48 | 51.69 | 1.58 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 617 | 22.84 | 7.37 | 0.42 |
| 2| 723 | 22.60 | 7.95 | 0.42 |
| 3| 904 | 25.85 | 9.56 | 0.47 |
| 5| 1293 | 31.02 | 12.33 | 0.55 |
| 10| 1917 | 37.55 | 17.47 | 0.66 |
| 41| 6573 | 98.76 | 55.20 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.54 | 8.47 | 0.46 |
| 2| 805 | 31.65 | 10.28 | 0.52 |
| 3| 960 | 33.43 | 11.44 | 0.55 |
| 5| 1388 | 38.33 | 14.18 | 0.62 |
| 10| 1946 | 43.36 | 18.91 | 0.72 |
| 38| 6016 | 98.71 | 53.06 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 853 | 36.52 | 11.59 | 0.57 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1376 | 43.87 | 15.66 | 0.68 |
| 10| 2061 | 54.80 | 22.03 | 0.84 |
| 29| 4945 | 99.98 | 47.32 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5831 | 26.96 | 9.06 | 0.69 |
| 2| 6021 | 37.08 | 12.49 | 0.80 |
| 3| 6068 | 45.05 | 15.12 | 0.89 |
| 4| 6215 | 50.42 | 16.96 | 0.95 |
| 5| 6456 | 66.25 | 22.39 | 1.13 |
| 6| 6414 | 67.70 | 22.65 | 1.14 |
| 7| 6943 | 85.81 | 28.98 | 1.36 |
| 8| 6663 | 87.41 | 29.36 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1704 | 6850 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2221 | 7160 | 97.61 | 37.43 | 1.52 |

