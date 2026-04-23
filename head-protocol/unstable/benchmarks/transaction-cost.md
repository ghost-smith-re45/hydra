--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-23 07:18:56.89296177 UTC |
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
| 1| 5837 | 10.74 | 3.42 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.10 | 6.05 | 0.64 |
| 10| 7651 | 29.55 | 9.33 | 0.79 |
| 43| 14279 | 99.33 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 635 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 42.33 | 12.19 | 0.61 |
| 4 | 227 | 858 | 53.93 | 15.36 | 0.73 |
| 5 | 283 | 969 | 57.83 | 16.72 | 0.78 |
| 6 | 337 | 1085 | 67.93 | 19.54 | 0.89 |
| 7 | 393 | 1192 | 82.41 | 23.32 | 1.04 |
| 8 | 450 | 1303 | 80.89 | 23.44 | 1.03 |
| 9 | 506 | 1414 | 94.59 | 27.13 | 1.17 |
| 10 | 560 | 1525 | 97.81 | 28.48 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1880 | 24.43 | 8.40 | 0.49 |
| 3| 2077 | 27.43 | 9.89 | 0.53 |
| 5| 2464 | 31.91 | 12.50 | 0.61 |
| 10| 3110 | 40.57 | 18.25 | 0.75 |
| 42| 7833 | 98.68 | 55.75 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.38 | 0.41 |
| 2| 813 | 25.16 | 8.72 | 0.45 |
| 3| 946 | 26.08 | 9.60 | 0.47 |
| 5| 1228 | 29.00 | 11.75 | 0.52 |
| 10| 1885 | 36.59 | 17.20 | 0.65 |
| 40| 6516 | 96.28 | 53.81 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.54 | 8.47 | 0.46 |
| 2| 805 | 30.94 | 10.07 | 0.51 |
| 3| 948 | 30.94 | 10.75 | 0.52 |
| 5| 1206 | 34.22 | 13.01 | 0.57 |
| 10| 2046 | 45.61 | 19.58 | 0.75 |
| 36| 6019 | 98.36 | 51.75 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.83 | 10.15 | 0.53 |
| 2| 859 | 36.22 | 11.49 | 0.56 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1366 | 44.11 | 15.72 | 0.68 |
| 10| 1943 | 53.24 | 21.56 | 0.82 |
| 30| 5019 | 99.22 | 47.69 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.09 | 9.10 | 0.69 |
| 2| 6042 | 36.81 | 12.42 | 0.80 |
| 3| 6119 | 42.44 | 14.26 | 0.87 |
| 4| 6278 | 52.30 | 17.63 | 0.98 |
| 5| 6223 | 56.23 | 18.80 | 1.01 |
| 6| 6760 | 75.14 | 25.41 | 1.24 |
| 7| 6818 | 84.16 | 28.39 | 1.33 |
| 8| 6785 | 89.10 | 29.97 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 284 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1703 | 6849 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2215 | 7155 | 98.68 | 37.80 | 1.53 |

