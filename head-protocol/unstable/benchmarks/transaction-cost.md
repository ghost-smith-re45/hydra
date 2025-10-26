--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-26 04:39:45.2275643 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.59 | 4.61 | 0.58 |
| 5| 6645 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 43.88 | 12.56 | 0.63 |
| 4 | 227 | 858 | 51.05 | 14.67 | 0.71 |
| 5 | 284 | 969 | 56.55 | 16.39 | 0.77 |
| 6 | 339 | 1085 | 69.70 | 19.92 | 0.90 |
| 7 | 393 | 1192 | 84.66 | 23.94 | 1.06 |
| 8 | 449 | 1303 | 91.44 | 25.96 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1985 | 26.58 | 9.01 | 0.52 |
| 3| 2055 | 27.35 | 9.87 | 0.53 |
| 5| 2467 | 32.04 | 12.53 | 0.61 |
| 10| 3163 | 40.93 | 18.34 | 0.75 |
| 40| 7488 | 96.37 | 53.73 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 743 | 24.31 | 8.46 | 0.44 |
| 3| 959 | 26.17 | 9.62 | 0.47 |
| 5| 1322 | 31.19 | 12.37 | 0.55 |
| 10| 1932 | 38.31 | 17.71 | 0.67 |
| 42| 6756 | 98.87 | 55.85 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 813 | 29.26 | 9.62 | 0.49 |
| 3| 931 | 32.76 | 11.24 | 0.54 |
| 5| 1295 | 37.78 | 14.00 | 0.61 |
| 10| 2068 | 48.12 | 20.25 | 0.78 |
| 36| 6063 | 99.35 | 52.02 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 817 | 35.88 | 11.39 | 0.56 |
| 3| 1022 | 39.26 | 13.03 | 0.61 |
| 5| 1314 | 43.39 | 15.50 | 0.67 |
| 10| 2123 | 55.26 | 22.18 | 0.85 |
| 29| 4629 | 95.58 | 45.95 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.08 | 9.09 | 0.69 |
| 2| 5985 | 37.00 | 12.47 | 0.80 |
| 3| 6115 | 44.64 | 15.04 | 0.89 |
| 4| 6287 | 55.08 | 18.53 | 1.01 |
| 5| 6435 | 63.43 | 21.41 | 1.10 |
| 6| 6579 | 74.09 | 24.98 | 1.22 |
| 7| 6623 | 80.50 | 27.07 | 1.29 |
| 8| 6996 | 96.01 | 32.42 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2223 | 7162 | 99.38 | 38.04 | 1.54 |

