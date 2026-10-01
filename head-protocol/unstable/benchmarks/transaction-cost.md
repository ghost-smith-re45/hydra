--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-01 12:00:11.29405108 UTC |
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
| 2| 6037 | 12.75 | 4.04 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7651 | 29.21 | 9.21 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 227 | 862 | 50.72 | 14.57 | 0.70 |
| 5 | 282 | 969 | 60.90 | 17.42 | 0.81 |
| 6 | 338 | 1081 | 75.26 | 21.22 | 0.96 |
| 7 | 394 | 1192 | 83.28 | 23.66 | 1.05 |
| 8 | 450 | 1303 | 80.67 | 23.39 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.29 | 7.69 | 0.48 |
| 2| 1971 | 26.79 | 9.05 | 0.52 |
| 3| 2128 | 28.39 | 10.16 | 0.55 |
| 5| 2501 | 33.32 | 12.88 | 0.62 |
| 10| 3113 | 41.26 | 18.42 | 0.75 |
| 40| 7697 | 99.08 | 54.51 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.54 | 7.31 | 0.41 |
| 2| 739 | 23.65 | 8.24 | 0.43 |
| 3| 933 | 26.59 | 9.76 | 0.48 |
| 5| 1384 | 32.43 | 12.72 | 0.56 |
| 10| 1984 | 39.57 | 18.04 | 0.69 |
| 39| 6325 | 94.96 | 52.78 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 827 | 29.22 | 9.61 | 0.49 |
| 3| 973 | 30.94 | 10.75 | 0.52 |
| 5| 1248 | 35.05 | 13.25 | 0.58 |
| 10| 2022 | 44.90 | 19.37 | 0.74 |
| 36| 5921 | 96.30 | 51.11 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 798 | 35.92 | 11.40 | 0.56 |
| 3| 1009 | 38.63 | 12.83 | 0.60 |
| 5| 1376 | 44.20 | 15.76 | 0.68 |
| 10| 1982 | 53.46 | 21.62 | 0.83 |
| 29| 4969 | 99.90 | 47.26 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.09 | 9.10 | 0.69 |
| 2| 5966 | 36.03 | 12.11 | 0.79 |
| 3| 6140 | 46.08 | 15.53 | 0.90 |
| 4| 6328 | 55.09 | 18.67 | 1.01 |
| 5| 6316 | 57.95 | 19.45 | 1.04 |
| 6| 6678 | 74.55 | 25.21 | 1.23 |
| 7| 6735 | 79.16 | 26.66 | 1.28 |
| 8| 6626 | 83.27 | 27.91 | 1.32 |
| 9| 6961 | 98.97 | 33.35 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1138 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1707 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.24 | 37.65 | 1.53 |

