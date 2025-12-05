--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-05 04:45:28.571563782 UTC |
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
| 1| 5840 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.73 | 4.04 | 0.55 |
| 3| 6240 | 14.48 | 4.58 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 43.79 | 12.52 | 0.63 |
| 4 | 227 | 858 | 52.57 | 15.08 | 0.72 |
| 5 | 283 | 969 | 65.09 | 18.52 | 0.85 |
| 6 | 340 | 1081 | 73.29 | 20.82 | 0.94 |
| 7 | 395 | 1192 | 78.65 | 22.50 | 1.00 |
| 8 | 449 | 1303 | 88.05 | 25.21 | 1.10 |
| 9 | 505 | 1414 | 98.82 | 28.19 | 1.21 |
| 10 | 560 | 1525 | 96.94 | 28.14 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1999 | 26.50 | 8.99 | 0.52 |
| 3| 2073 | 26.99 | 9.78 | 0.53 |
| 5| 2407 | 31.53 | 12.39 | 0.60 |
| 10| 3320 | 44.17 | 19.24 | 0.79 |
| 40| 7702 | 98.67 | 54.42 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.54 | 7.30 | 0.41 |
| 2| 766 | 24.32 | 8.46 | 0.44 |
| 3| 904 | 25.06 | 9.31 | 0.46 |
| 5| 1244 | 30.10 | 12.07 | 0.54 |
| 10| 1992 | 39.45 | 18.02 | 0.69 |
| 41| 6541 | 96.81 | 54.64 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 27.54 | 8.47 | 0.46 |
| 2| 833 | 31.65 | 10.28 | 0.52 |
| 3| 953 | 30.98 | 10.76 | 0.52 |
| 5| 1327 | 35.56 | 13.42 | 0.59 |
| 10| 2019 | 44.49 | 19.24 | 0.74 |
| 36| 5984 | 98.03 | 51.61 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 33.15 | 9.95 | 0.52 |
| 2| 860 | 36.64 | 11.62 | 0.57 |
| 3| 1082 | 39.30 | 13.04 | 0.61 |
| 5| 1214 | 41.82 | 15.03 | 0.65 |
| 10| 2099 | 54.85 | 22.04 | 0.84 |
| 28| 4899 | 98.45 | 46.23 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5968 | 35.84 | 12.05 | 0.79 |
| 3| 6059 | 41.33 | 13.82 | 0.85 |
| 4| 6269 | 54.15 | 18.22 | 0.99 |
| 5| 6289 | 62.48 | 21.00 | 1.08 |
| 6| 6493 | 70.50 | 23.79 | 1.18 |
| 7| 6768 | 80.89 | 27.25 | 1.30 |
| 8| 6965 | 92.65 | 31.33 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6511 | 59.73 | 22.44 | 1.08 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

