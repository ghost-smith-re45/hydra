--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-13 04:55:38.180483481 UTC |
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
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.79 | 5.94 | 0.64 |
| 10| 7644 | 29.30 | 9.24 | 0.79 |
| 43| 14283 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 41.22 | 11.94 | 0.60 |
| 4 | 225 | 858 | 49.54 | 14.28 | 0.69 |
| 5 | 283 | 969 | 64.35 | 18.31 | 0.84 |
| 6 | 341 | 1081 | 74.79 | 21.14 | 0.95 |
| 7 | 394 | 1192 | 80.36 | 22.87 | 1.02 |
| 8 | 451 | 1303 | 91.71 | 25.98 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.29 | 7.69 | 0.48 |
| 2| 1999 | 26.42 | 8.96 | 0.52 |
| 3| 2073 | 27.47 | 9.90 | 0.53 |
| 5| 2459 | 33.51 | 12.93 | 0.62 |
| 10| 3239 | 43.19 | 18.96 | 0.78 |
| 40| 7608 | 99.36 | 54.57 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.39 | 0.42 |
| 2| 739 | 23.65 | 8.24 | 0.43 |
| 3| 925 | 25.14 | 9.33 | 0.46 |
| 5| 1115 | 27.12 | 11.22 | 0.50 |
| 10| 1983 | 38.43 | 17.72 | 0.68 |
| 41| 6579 | 99.22 | 55.30 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 29.13 | 8.90 | 0.48 |
| 2| 812 | 29.26 | 9.62 | 0.49 |
| 3| 898 | 30.19 | 10.53 | 0.51 |
| 5| 1130 | 35.60 | 13.34 | 0.58 |
| 10| 1913 | 46.54 | 19.78 | 0.75 |
| 36| 5931 | 97.59 | 51.52 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 878 | 36.56 | 11.60 | 0.57 |
| 3| 959 | 37.88 | 12.61 | 0.59 |
| 5| 1158 | 41.15 | 14.83 | 0.64 |
| 10| 2010 | 53.91 | 21.77 | 0.83 |
| 30| 4908 | 99.20 | 47.69 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5959 | 36.04 | 12.11 | 0.79 |
| 3| 6087 | 42.72 | 14.36 | 0.87 |
| 4| 6189 | 52.38 | 17.57 | 0.97 |
| 5| 6336 | 63.20 | 21.28 | 1.09 |
| 6| 6594 | 74.09 | 24.97 | 1.22 |
| 7| 6731 | 84.49 | 28.52 | 1.33 |
| 8| 6888 | 94.01 | 31.77 | 1.44 |
| 9| 7060 | 99.88 | 33.77 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 283 | 6002 | 29.79 | 10.58 | 0.73 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2219 | 7159 | 98.93 | 37.88 | 1.54 |

