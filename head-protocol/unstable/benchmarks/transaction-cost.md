--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-07 04:37:33.289795865 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6041 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10096 | 98.61 | 68.52 | 1.89 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 640 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 40.35 | 11.74 | 0.59 |
| 4 | 226 | 858 | 52.92 | 15.19 | 0.73 |
| 5 | 284 | 969 | 56.32 | 16.36 | 0.77 |
| 6 | 338 | 1081 | 67.79 | 19.43 | 0.89 |
| 7 | 395 | 1196 | 73.88 | 21.31 | 0.95 |
| 8 | 450 | 1303 | 92.07 | 26.12 | 1.14 |
| 9 | 505 | 1414 | 94.15 | 27.07 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.00 | 7.62 | 0.48 |
| 2| 1927 | 25.85 | 8.78 | 0.51 |
| 3| 2055 | 27.31 | 9.86 | 0.53 |
| 5| 2466 | 32.45 | 12.63 | 0.61 |
| 10| 3309 | 42.81 | 18.87 | 0.78 |
| 39| 7635 | 99.29 | 53.89 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 824 | 25.56 | 8.81 | 0.46 |
| 3| 980 | 28.08 | 10.16 | 0.49 |
| 5| 1164 | 27.97 | 11.46 | 0.51 |
| 10| 1836 | 36.36 | 17.15 | 0.65 |
| 42| 6697 | 98.29 | 55.71 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.13 | 8.90 | 0.48 |
| 2| 845 | 29.22 | 9.61 | 0.49 |
| 3| 1003 | 31.53 | 10.94 | 0.53 |
| 5| 1359 | 38.32 | 14.18 | 0.62 |
| 10| 2079 | 48.14 | 20.26 | 0.78 |
| 35| 5795 | 95.62 | 50.26 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.87 | 10.16 | 0.53 |
| 2| 873 | 36.60 | 11.61 | 0.57 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1284 | 43.31 | 15.48 | 0.67 |
| 10| 2070 | 55.00 | 22.08 | 0.84 |
| 28| 4888 | 97.46 | 45.95 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5786 | 27.04 | 9.09 | 0.69 |
| 2| 5885 | 32.68 | 10.93 | 0.75 |
| 3| 6065 | 43.78 | 14.69 | 0.88 |
| 4| 6294 | 55.31 | 18.69 | 1.01 |
| 5| 6125 | 51.55 | 17.13 | 0.96 |
| 6| 6409 | 65.53 | 21.94 | 1.12 |
| 7| 6723 | 81.04 | 27.27 | 1.30 |
| 8| 6978 | 91.06 | 30.71 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2223 | 7163 | 98.05 | 37.58 | 1.53 |

