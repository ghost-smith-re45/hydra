--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-15 07:25:07.632525653 UTC |
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
| 1| 5836 | 10.78 | 3.43 | 0.52 |
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6242 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 169 | 747 | 43.84 | 12.56 | 0.63 |
| 4 | 225 | 858 | 49.85 | 14.41 | 0.69 |
| 5 | 281 | 974 | 59.07 | 16.98 | 0.79 |
| 6 | 338 | 1081 | 75.76 | 21.45 | 0.96 |
| 7 | 399 | 1192 | 86.67 | 24.42 | 1.08 |
| 8 | 448 | 1307 | 86.54 | 24.73 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 23.92 | 7.60 | 0.48 |
| 2| 1924 | 25.88 | 8.79 | 0.51 |
| 3| 2059 | 27.35 | 9.87 | 0.53 |
| 5| 2422 | 32.07 | 12.54 | 0.61 |
| 10| 3188 | 42.52 | 18.78 | 0.77 |
| 41| 7560 | 94.97 | 54.00 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.84 | 7.37 | 0.41 |
| 2| 723 | 22.60 | 7.95 | 0.42 |
| 3| 857 | 24.11 | 9.04 | 0.45 |
| 5| 1287 | 31.44 | 12.45 | 0.55 |
| 10| 1874 | 36.55 | 17.19 | 0.65 |
| 43| 6827 | 98.78 | 56.53 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.17 | 8.91 | 0.48 |
| 2| 781 | 30.98 | 10.08 | 0.51 |
| 3| 1026 | 31.57 | 10.95 | 0.53 |
| 5| 1172 | 36.31 | 13.56 | 0.59 |
| 10| 1962 | 44.04 | 19.11 | 0.73 |
| 35| 5727 | 98.86 | 51.10 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 878 | 36.64 | 11.62 | 0.57 |
| 3| 941 | 37.91 | 12.62 | 0.59 |
| 5| 1317 | 43.21 | 15.46 | 0.67 |
| 10| 2031 | 54.06 | 21.81 | 0.83 |
| 30| 4784 | 98.69 | 47.49 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 26.97 | 9.07 | 0.69 |
| 2| 5981 | 36.93 | 12.47 | 0.80 |
| 3| 6085 | 44.83 | 15.07 | 0.89 |
| 4| 6234 | 53.92 | 18.14 | 0.99 |
| 5| 6367 | 60.30 | 20.27 | 1.06 |
| 6| 6410 | 69.32 | 23.22 | 1.16 |
| 7| 6698 | 83.35 | 28.11 | 1.32 |
| 8| 6971 | 94.87 | 31.99 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 567 | 6172 | 38.37 | 14.06 | 0.83 |
| 10 | 20 | 1136 | 6510 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2223 | 7162 | 98.68 | 37.80 | 1.54 |

