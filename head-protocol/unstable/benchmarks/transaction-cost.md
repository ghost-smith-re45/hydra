--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-06 09:41:35.519071307 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.69 | 4.65 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.88 | 9.10 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10083 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 40.25 | 11.69 | 0.59 |
| 4 | 227 | 858 | 52.47 | 15.01 | 0.72 |
| 5 | 282 | 969 | 59.67 | 17.13 | 0.80 |
| 6 | 338 | 1081 | 66.57 | 19.22 | 0.87 |
| 7 | 396 | 1192 | 81.33 | 23.24 | 1.03 |
| 8 | 451 | 1303 | 86.81 | 24.76 | 1.09 |
| 9 | 504 | 1414 | 98.19 | 27.98 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2013 | 25.94 | 9.49 | 0.52 |
| 5| 2360 | 30.96 | 12.23 | 0.59 |
| 10| 3156 | 41.46 | 18.48 | 0.76 |
| 41| 7803 | 98.38 | 55.01 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.80 | 7.38 | 0.42 |
| 2| 808 | 25.41 | 8.76 | 0.45 |
| 3| 935 | 26.87 | 9.85 | 0.48 |
| 5| 1215 | 29.03 | 11.75 | 0.52 |
| 10| 1988 | 39.68 | 18.06 | 0.69 |
| 41| 6524 | 95.54 | 54.32 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.13 | 8.90 | 0.48 |
| 2| 877 | 29.90 | 9.82 | 0.50 |
| 3| 910 | 32.75 | 11.24 | 0.54 |
| 5| 1285 | 34.94 | 13.22 | 0.58 |
| 10| 2162 | 46.69 | 19.91 | 0.77 |
| 36| 5809 | 94.77 | 50.68 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.79 | 10.15 | 0.53 |
| 2| 823 | 35.88 | 11.39 | 0.56 |
| 3| 1019 | 38.55 | 12.81 | 0.60 |
| 5| 1391 | 44.07 | 15.71 | 0.68 |
| 10| 2008 | 54.29 | 21.86 | 0.83 |
| 30| 4864 | 99.70 | 47.80 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.96 | 9.05 | 0.69 |
| 2| 5845 | 31.48 | 10.47 | 0.74 |
| 3| 6229 | 46.77 | 15.82 | 0.92 |
| 4| 6368 | 56.74 | 19.23 | 1.03 |
| 5| 6544 | 67.32 | 22.76 | 1.15 |
| 6| 6604 | 74.58 | 25.14 | 1.22 |
| 7| 6610 | 76.90 | 25.86 | 1.25 |
| 8| 6834 | 88.16 | 29.65 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2164 | 7127 | 96.00 | 36.77 | 1.50 |

