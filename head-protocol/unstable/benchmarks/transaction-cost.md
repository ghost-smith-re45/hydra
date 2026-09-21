--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-21 10:54:43.847045721 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6035 | 12.42 | 3.93 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.39 | 9.43 | 0.51 |
| 3 | 170 | 747 | 41.39 | 11.97 | 0.60 |
| 4 | 227 | 858 | 51.27 | 14.75 | 0.71 |
| 5 | 283 | 969 | 64.40 | 18.29 | 0.85 |
| 6 | 339 | 1081 | 71.30 | 20.30 | 0.92 |
| 7 | 395 | 1192 | 74.74 | 21.61 | 0.96 |
| 8 | 448 | 1303 | 80.55 | 23.36 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1886 | 24.80 | 8.49 | 0.49 |
| 3| 2066 | 27.32 | 9.86 | 0.53 |
| 5| 2327 | 30.30 | 12.03 | 0.58 |
| 10| 3188 | 41.57 | 18.53 | 0.76 |
| 42| 7799 | 98.67 | 55.74 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.57 | 7.32 | 0.41 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 948 | 26.71 | 9.79 | 0.48 |
| 5| 1116 | 26.98 | 11.18 | 0.50 |
| 10| 1863 | 36.52 | 17.18 | 0.65 |
| 40| 6632 | 98.44 | 54.44 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 900 | 29.90 | 9.82 | 0.50 |
| 3| 903 | 30.23 | 10.54 | 0.51 |
| 5| 1302 | 37.81 | 14.01 | 0.61 |
| 10| 1992 | 44.90 | 19.37 | 0.74 |
| 37| 6042 | 99.83 | 52.78 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 952 | 37.91 | 12.62 | 0.59 |
| 5| 1199 | 41.97 | 15.07 | 0.65 |
| 10| 1980 | 53.35 | 21.59 | 0.82 |
| 29| 4884 | 98.42 | 46.83 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.09 | 9.10 | 0.69 |
| 2| 5929 | 35.91 | 12.08 | 0.79 |
| 3| 6081 | 42.24 | 14.20 | 0.86 |
| 4| 6358 | 56.23 | 18.98 | 1.02 |
| 5| 6387 | 63.28 | 21.40 | 1.10 |
| 6| 6510 | 71.87 | 24.15 | 1.19 |
| 7| 6590 | 79.07 | 26.57 | 1.27 |
| 8| 6851 | 88.91 | 29.92 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 40.13 | 14.67 | 0.85 |
| 10 | 20 | 1136 | 6510 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

