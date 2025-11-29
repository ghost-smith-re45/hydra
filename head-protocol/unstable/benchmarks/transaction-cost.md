--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-29 04:39:14.548550521 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7644 | 29.00 | 9.14 | 0.79 |
| 43| 14285 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 751 | 41.22 | 11.94 | 0.60 |
| 4 | 225 | 858 | 53.90 | 15.35 | 0.73 |
| 5 | 282 | 969 | 59.41 | 17.10 | 0.80 |
| 6 | 340 | 1081 | 68.10 | 19.54 | 0.89 |
| 7 | 394 | 1192 | 78.71 | 22.48 | 1.00 |
| 8 | 449 | 1303 | 90.24 | 25.78 | 1.12 |
| 9 | 505 | 1414 | 92.95 | 26.67 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.37 | 7.71 | 0.48 |
| 2| 1998 | 25.93 | 8.83 | 0.51 |
| 3| 2060 | 27.31 | 9.86 | 0.53 |
| 5| 2395 | 31.49 | 12.36 | 0.60 |
| 10| 3169 | 40.66 | 18.27 | 0.75 |
| 40| 7585 | 97.85 | 54.18 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.81 | 7.37 | 0.42 |
| 2| 766 | 24.25 | 8.44 | 0.44 |
| 3| 874 | 25.13 | 9.32 | 0.46 |
| 5| 1224 | 29.50 | 11.91 | 0.53 |
| 10| 2098 | 40.62 | 18.33 | 0.70 |
| 41| 6475 | 94.74 | 54.04 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 27.54 | 8.47 | 0.46 |
| 2| 869 | 29.90 | 9.82 | 0.50 |
| 3| 1039 | 32.29 | 11.17 | 0.54 |
| 5| 1266 | 34.85 | 13.20 | 0.58 |
| 10| 2165 | 46.63 | 19.89 | 0.77 |
| 36| 6025 | 99.13 | 51.95 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.87 | 10.16 | 0.53 |
| 2| 872 | 36.56 | 11.60 | 0.57 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1220 | 41.93 | 15.06 | 0.65 |
| 10| 2115 | 55.37 | 22.21 | 0.85 |
| 29| 4914 | 98.81 | 46.95 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.13 | 9.09 | 0.69 |
| 2| 5957 | 35.83 | 12.03 | 0.79 |
| 3| 6041 | 43.90 | 14.72 | 0.88 |
| 4| 6306 | 55.91 | 18.87 | 1.02 |
| 5| 6356 | 63.28 | 21.28 | 1.09 |
| 6| 6468 | 69.42 | 23.35 | 1.16 |
| 7| 6706 | 81.61 | 27.50 | 1.30 |
| 8| 6705 | 85.14 | 28.59 | 1.34 |
| 9| 6880 | 99.67 | 33.42 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6854 | 79.97 | 30.44 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

