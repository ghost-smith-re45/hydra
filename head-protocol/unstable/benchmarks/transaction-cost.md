--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-25 06:59:12.229107913 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 169 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 226 | 858 | 50.83 | 14.64 | 0.70 |
| 5 | 283 | 974 | 56.61 | 16.40 | 0.77 |
| 6 | 338 | 1081 | 66.48 | 19.19 | 0.87 |
| 7 | 393 | 1192 | 74.24 | 21.40 | 0.96 |
| 8 | 451 | 1303 | 91.31 | 25.83 | 1.13 |
| 9 | 506 | 1414 | 93.38 | 26.77 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1753 | 23.30 | 7.41 | 0.47 |
| 2| 1974 | 26.62 | 9.02 | 0.52 |
| 3| 2122 | 28.85 | 10.29 | 0.55 |
| 5| 2317 | 30.38 | 12.05 | 0.58 |
| 10| 3240 | 42.77 | 18.86 | 0.77 |
| 39| 7595 | 98.47 | 53.69 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.54 | 7.31 | 0.41 |
| 2| 764 | 23.56 | 8.22 | 0.43 |
| 3| 897 | 25.03 | 9.30 | 0.46 |
| 5| 1207 | 29.14 | 11.80 | 0.52 |
| 10| 2044 | 41.11 | 18.48 | 0.71 |
| 41| 6614 | 98.66 | 55.13 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.54 | 8.47 | 0.46 |
| 2| 836 | 31.58 | 10.26 | 0.52 |
| 3| 944 | 30.94 | 10.75 | 0.52 |
| 5| 1380 | 36.51 | 13.69 | 0.60 |
| 10| 1973 | 47.03 | 19.92 | 0.76 |
| 35| 5659 | 94.08 | 49.78 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.87 | 10.16 | 0.53 |
| 2| 832 | 35.89 | 11.39 | 0.56 |
| 3| 986 | 38.55 | 12.81 | 0.60 |
| 5| 1240 | 42.64 | 15.28 | 0.66 |
| 10| 1897 | 52.67 | 21.38 | 0.81 |
| 28| 4929 | 98.92 | 46.37 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 27.08 | 9.09 | 0.69 |
| 2| 5967 | 35.80 | 12.05 | 0.79 |
| 3| 6105 | 42.41 | 14.24 | 0.86 |
| 4| 6170 | 50.34 | 16.89 | 0.95 |
| 5| 6461 | 65.00 | 21.93 | 1.12 |
| 6| 6523 | 70.84 | 23.86 | 1.18 |
| 7| 6726 | 82.64 | 27.88 | 1.31 |
| 8| 6858 | 92.39 | 31.04 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 16.98 | 5.65 | 0.58 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 58.84 | 22.14 | 1.07 |
| 10 | 30 | 1705 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 99.12 | 37.95 | 1.54 |

