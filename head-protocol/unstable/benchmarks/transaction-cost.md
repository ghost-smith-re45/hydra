--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-08 05:40:17.680372946 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7644 | 29.00 | 9.14 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 170 | 747 | 42.62 | 12.26 | 0.62 |
| 4 | 226 | 858 | 47.83 | 13.90 | 0.67 |
| 5 | 282 | 969 | 63.29 | 17.96 | 0.83 |
| 6 | 337 | 1081 | 71.03 | 20.24 | 0.92 |
| 7 | 395 | 1192 | 87.01 | 24.55 | 1.08 |
| 8 | 451 | 1303 | 92.14 | 26.18 | 1.14 |
| 9 | 505 | 1414 | 98.90 | 28.15 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 1974 | 27.00 | 9.10 | 0.52 |
| 3| 2148 | 29.50 | 10.47 | 0.56 |
| 5| 2332 | 29.96 | 11.95 | 0.58 |
| 10| 3173 | 40.58 | 18.25 | 0.75 |
| 39| 7449 | 96.16 | 53.01 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.84 | 7.37 | 0.41 |
| 2| 739 | 24.31 | 8.47 | 0.44 |
| 3| 853 | 23.99 | 9.01 | 0.45 |
| 5| 1189 | 29.93 | 12.02 | 0.53 |
| 10| 2044 | 42.42 | 18.85 | 0.72 |
| 40| 6552 | 96.15 | 53.80 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 711 | 27.54 | 8.47 | 0.47 |
| 2| 770 | 28.47 | 9.38 | 0.48 |
| 3| 986 | 31.65 | 10.97 | 0.53 |
| 5| 1342 | 36.31 | 13.64 | 0.60 |
| 10| 1987 | 47.21 | 19.99 | 0.76 |
| 37| 6010 | 97.46 | 52.09 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 803 | 35.85 | 11.38 | 0.56 |
| 3| 891 | 37.24 | 12.41 | 0.58 |
| 5| 1285 | 43.27 | 15.47 | 0.67 |
| 10| 2050 | 54.85 | 22.04 | 0.84 |
| 30| 4768 | 97.31 | 47.12 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 27.12 | 9.10 | 0.69 |
| 2| 5896 | 32.68 | 10.92 | 0.75 |
| 3| 6140 | 45.88 | 15.46 | 0.90 |
| 4| 6118 | 49.36 | 16.50 | 0.94 |
| 5| 6454 | 64.69 | 21.80 | 1.11 |
| 6| 6660 | 75.26 | 25.40 | 1.23 |
| 7| 6876 | 86.08 | 29.11 | 1.36 |
| 8| 6902 | 92.02 | 30.96 | 1.42 |
| 9| 7001 | 96.71 | 32.58 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2223 | 7163 | 98.49 | 37.73 | 1.53 |

