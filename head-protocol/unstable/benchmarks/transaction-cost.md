--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-16 07:36:47.774507708 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 43.57 | 12.47 | 0.63 |
| 4 | 227 | 858 | 52.36 | 14.96 | 0.72 |
| 5 | 281 | 969 | 64.38 | 18.26 | 0.84 |
| 6 | 339 | 1081 | 69.56 | 19.92 | 0.90 |
| 7 | 394 | 1192 | 81.29 | 23.22 | 1.03 |
| 8 | 449 | 1303 | 83.17 | 23.99 | 1.05 |
| 9 | 505 | 1414 | 89.21 | 25.94 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2056 | 27.40 | 9.88 | 0.53 |
| 5| 2455 | 33.37 | 12.89 | 0.62 |
| 10| 3288 | 43.34 | 19.00 | 0.78 |
| 40| 7609 | 98.86 | 54.47 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.80 | 7.36 | 0.41 |
| 2| 767 | 23.56 | 8.22 | 0.43 |
| 3| 943 | 26.63 | 9.79 | 0.48 |
| 5| 1215 | 29.88 | 12.02 | 0.53 |
| 10| 1943 | 37.74 | 17.52 | 0.67 |
| 39| 6334 | 93.74 | 52.44 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.51 | 8.47 | 0.46 |
| 2| 809 | 29.22 | 9.61 | 0.49 |
| 3| 969 | 33.44 | 11.45 | 0.55 |
| 5| 1279 | 37.65 | 13.97 | 0.61 |
| 10| 1851 | 45.12 | 19.35 | 0.74 |
| 35| 5729 | 98.96 | 51.09 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.16 | 0.53 |
| 2| 845 | 36.56 | 11.60 | 0.57 |
| 3| 1012 | 38.66 | 12.84 | 0.60 |
| 5| 1263 | 42.82 | 15.34 | 0.66 |
| 10| 2179 | 55.29 | 22.19 | 0.85 |
| 28| 4641 | 95.44 | 45.29 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 27.00 | 9.06 | 0.69 |
| 2| 5990 | 35.72 | 12.01 | 0.79 |
| 3| 6130 | 44.69 | 15.02 | 0.89 |
| 4| 6275 | 54.32 | 18.31 | 1.00 |
| 5| 6370 | 62.68 | 21.08 | 1.09 |
| 6| 6517 | 73.64 | 24.75 | 1.21 |
| 7| 6734 | 84.45 | 28.47 | 1.33 |
| 8| 6853 | 92.86 | 31.30 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1136 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2220 | 7160 | 99.82 | 38.19 | 1.55 |

