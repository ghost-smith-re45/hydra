--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-14 04:39:05.635941581 UTC |
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
| 1| 5837 | 10.72 | 3.41 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6243 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7651 | 29.31 | 9.25 | 0.79 |
| 43| 14279 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10035 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 42.66 | 12.27 | 0.62 |
| 4 | 225 | 858 | 48.46 | 14.08 | 0.68 |
| 5 | 283 | 969 | 64.20 | 18.21 | 0.84 |
| 6 | 337 | 1081 | 64.67 | 18.76 | 0.86 |
| 7 | 395 | 1192 | 74.91 | 21.65 | 0.96 |
| 8 | 452 | 1303 | 86.43 | 24.66 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2064 | 27.32 | 9.86 | 0.53 |
| 5| 2423 | 32.03 | 12.53 | 0.61 |
| 10| 3152 | 41.04 | 18.36 | 0.75 |
| 40| 7566 | 98.84 | 54.41 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.54 | 7.30 | 0.41 |
| 2| 764 | 23.56 | 8.22 | 0.43 |
| 3| 915 | 25.14 | 9.33 | 0.46 |
| 5| 1178 | 29.94 | 12.02 | 0.53 |
| 10| 2023 | 40.79 | 18.38 | 0.70 |
| 40| 6397 | 95.20 | 53.53 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 27.50 | 8.46 | 0.46 |
| 2| 804 | 29.15 | 9.59 | 0.49 |
| 3| 1043 | 31.91 | 11.05 | 0.53 |
| 5| 1206 | 34.33 | 13.03 | 0.57 |
| 10| 1932 | 46.17 | 19.67 | 0.75 |
| 37| 6134 | 98.89 | 52.54 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.92 | 11.40 | 0.56 |
| 3| 1011 | 38.59 | 12.82 | 0.60 |
| 5| 1268 | 42.45 | 15.23 | 0.66 |
| 10| 2185 | 56.27 | 22.48 | 0.86 |
| 28| 4756 | 96.08 | 45.49 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.05 | 9.08 | 0.69 |
| 2| 5927 | 36.07 | 12.12 | 0.79 |
| 3| 6191 | 47.06 | 15.90 | 0.92 |
| 4| 6225 | 52.49 | 17.70 | 0.98 |
| 5| 6242 | 55.87 | 18.66 | 1.01 |
| 6| 6656 | 74.53 | 25.13 | 1.23 |
| 7| 6712 | 83.61 | 28.20 | 1.32 |
| 8| 6887 | 91.99 | 30.93 | 1.42 |
| 9| 6865 | 95.94 | 32.30 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 40.13 | 14.67 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2217 | 7157 | 98.93 | 37.88 | 1.54 |

