--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-25 05:08:28.49538889 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 43.76 | 12.52 | 0.63 |
| 4 | 227 | 858 | 48.11 | 13.97 | 0.68 |
| 5 | 282 | 969 | 56.01 | 16.25 | 0.76 |
| 6 | 339 | 1081 | 65.53 | 18.88 | 0.86 |
| 7 | 394 | 1192 | 78.57 | 22.44 | 1.00 |
| 8 | 449 | 1303 | 96.39 | 27.25 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 23.92 | 7.60 | 0.48 |
| 2| 1929 | 25.55 | 8.71 | 0.50 |
| 3| 2013 | 25.91 | 9.48 | 0.52 |
| 5| 2280 | 28.93 | 11.66 | 0.57 |
| 10| 3212 | 42.05 | 18.65 | 0.77 |
| 40| 7725 | 98.29 | 54.31 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 22.77 | 7.36 | 0.42 |
| 2| 804 | 25.40 | 8.77 | 0.45 |
| 3| 884 | 25.09 | 9.33 | 0.46 |
| 5| 1224 | 29.16 | 11.79 | 0.52 |
| 10| 1975 | 39.89 | 18.13 | 0.69 |
| 40| 6570 | 99.94 | 54.80 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 815 | 29.19 | 9.60 | 0.49 |
| 3| 939 | 32.76 | 11.24 | 0.54 |
| 5| 1172 | 36.35 | 13.57 | 0.59 |
| 10| 2069 | 45.05 | 19.40 | 0.75 |
| 36| 6026 | 97.31 | 51.43 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.79 | 10.15 | 0.53 |
| 2| 826 | 35.85 | 11.38 | 0.56 |
| 3| 891 | 37.24 | 12.41 | 0.58 |
| 5| 1282 | 42.65 | 15.28 | 0.66 |
| 10| 1996 | 53.95 | 21.78 | 0.83 |
| 29| 4689 | 96.05 | 46.11 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.05 | 9.07 | 0.69 |
| 2| 5948 | 37.05 | 12.48 | 0.80 |
| 3| 6042 | 43.76 | 14.65 | 0.88 |
| 4| 6237 | 54.82 | 18.49 | 1.00 |
| 5| 6522 | 66.17 | 22.36 | 1.13 |
| 6| 6794 | 75.71 | 25.60 | 1.25 |
| 7| 6648 | 80.97 | 27.19 | 1.29 |
| 8| 6638 | 84.05 | 28.19 | 1.32 |
| 9| 6891 | 92.70 | 31.20 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 56 | 5867 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 30 | 1708 | 6854 | 78.71 | 30.00 | 1.30 |
| 10 | 40 | 2279 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

