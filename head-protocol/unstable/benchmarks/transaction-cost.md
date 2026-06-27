--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-27 08:07:59.678671716 UTC |
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
| 1| 5841 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 15.07 | 4.78 | 0.58 |
| 5| 6638 | 18.60 | 5.87 | 0.63 |
| 10| 7651 | 29.47 | 9.30 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.16 | 11.66 | 0.59 |
| 4 | 227 | 858 | 50.83 | 14.62 | 0.70 |
| 5 | 283 | 969 | 62.57 | 17.88 | 0.83 |
| 6 | 339 | 1081 | 67.73 | 19.48 | 0.89 |
| 7 | 395 | 1192 | 72.57 | 21.05 | 0.94 |
| 8 | 449 | 1303 | 80.42 | 23.28 | 1.03 |
| 10 | 560 | 1525 | 99.23 | 28.57 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.37 | 7.71 | 0.48 |
| 2| 1925 | 25.51 | 8.70 | 0.50 |
| 3| 2115 | 28.09 | 10.09 | 0.54 |
| 5| 2333 | 29.92 | 11.94 | 0.58 |
| 10| 3141 | 40.60 | 18.25 | 0.75 |
| 40| 7557 | 96.46 | 53.77 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.81 | 7.37 | 0.42 |
| 2| 764 | 23.56 | 8.22 | 0.43 |
| 3| 976 | 27.34 | 9.97 | 0.49 |
| 5| 1200 | 29.11 | 11.78 | 0.52 |
| 10| 1968 | 38.54 | 17.75 | 0.68 |
| 42| 6773 | 99.86 | 56.12 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.17 | 8.91 | 0.48 |
| 2| 770 | 30.94 | 10.07 | 0.51 |
| 3| 941 | 30.86 | 10.73 | 0.52 |
| 5| 1226 | 34.18 | 13.00 | 0.57 |
| 10| 2187 | 47.04 | 20.02 | 0.77 |
| 35| 5889 | 94.59 | 50.02 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 710 | 33.87 | 10.16 | 0.53 |
| 2| 863 | 36.48 | 11.58 | 0.57 |
| 3| 896 | 37.16 | 12.39 | 0.58 |
| 5| 1281 | 42.53 | 15.25 | 0.66 |
| 10| 2097 | 54.62 | 21.99 | 0.84 |
| 28| 4645 | 95.52 | 45.33 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 27.08 | 9.09 | 0.69 |
| 2| 5937 | 35.83 | 12.04 | 0.79 |
| 3| 6089 | 45.78 | 15.42 | 0.90 |
| 4| 6343 | 56.63 | 19.18 | 1.03 |
| 5| 6320 | 60.92 | 20.49 | 1.07 |
| 6| 6476 | 69.89 | 23.47 | 1.17 |
| 7| 6753 | 85.07 | 28.70 | 1.34 |
| 8| 6911 | 89.60 | 30.19 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.71 | 7.04 | 0.63 |
| 10 | 5 | 283 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 37 | 2104 | 7090 | 95.72 | 36.57 | 1.50 |

