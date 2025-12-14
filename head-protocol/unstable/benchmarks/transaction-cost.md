--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-14 04:52:40.822628145 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7651 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 39.89 | 11.59 | 0.59 |
| 4 | 227 | 858 | 47.88 | 13.89 | 0.67 |
| 5 | 284 | 969 | 60.70 | 17.37 | 0.81 |
| 6 | 338 | 1081 | 73.63 | 20.90 | 0.94 |
| 7 | 394 | 1192 | 76.23 | 21.92 | 0.98 |
| 8 | 451 | 1307 | 95.53 | 26.84 | 1.17 |
| 9 | 505 | 1414 | 90.39 | 26.00 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.00 | 7.62 | 0.48 |
| 2| 1994 | 26.92 | 9.09 | 0.52 |
| 3| 2173 | 29.10 | 10.38 | 0.56 |
| 5| 2396 | 31.44 | 12.35 | 0.60 |
| 10| 3118 | 40.74 | 18.29 | 0.75 |
| 38| 7492 | 97.15 | 52.65 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.54 | 7.30 | 0.41 |
| 2| 785 | 25.31 | 8.74 | 0.45 |
| 3| 962 | 27.06 | 9.89 | 0.48 |
| 5| 1319 | 31.94 | 12.58 | 0.56 |
| 10| 2066 | 41.94 | 18.70 | 0.71 |
| 39| 6374 | 95.00 | 52.79 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.17 | 8.91 | 0.48 |
| 2| 808 | 30.91 | 10.06 | 0.51 |
| 3| 997 | 33.47 | 11.46 | 0.55 |
| 5| 1293 | 35.01 | 13.24 | 0.59 |
| 10| 2094 | 47.81 | 20.17 | 0.77 |
| 36| 6002 | 97.00 | 51.32 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 880 | 36.56 | 11.60 | 0.57 |
| 3| 940 | 37.87 | 12.61 | 0.59 |
| 5| 1300 | 43.13 | 15.44 | 0.67 |
| 10| 2101 | 55.89 | 22.36 | 0.86 |
| 29| 4838 | 97.73 | 46.58 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.93 | 7.56 | 0.64 |
| 2| 5998 | 37.13 | 12.51 | 0.80 |
| 3| 6221 | 46.99 | 15.86 | 0.92 |
| 4| 6281 | 52.23 | 17.58 | 0.98 |
| 5| 6428 | 61.73 | 20.76 | 1.08 |
| 6| 6618 | 75.56 | 25.47 | 1.24 |
| 7| 6575 | 75.72 | 25.37 | 1.23 |
| 8| 6791 | 88.90 | 29.84 | 1.38 |
| 9| 6987 | 98.45 | 33.15 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2280 | 7197 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2220 | 7159 | 99.82 | 38.19 | 1.55 |

