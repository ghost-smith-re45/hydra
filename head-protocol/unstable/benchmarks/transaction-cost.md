--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-22 07:48:42.560838258 UTC |
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
| 1| 5838 | 10.95 | 3.49 | 0.52 |
| 2| 6037 | 12.82 | 4.07 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.88 | 5.97 | 0.64 |
| 10| 7646 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 751 | 41.20 | 11.90 | 0.60 |
| 4 | 226 | 862 | 49.42 | 14.30 | 0.69 |
| 5 | 284 | 969 | 59.15 | 16.97 | 0.79 |
| 6 | 339 | 1081 | 74.78 | 21.10 | 0.95 |
| 7 | 395 | 1196 | 86.50 | 24.34 | 1.08 |
| 8 | 452 | 1307 | 96.09 | 27.08 | 1.18 |
| 9 | 506 | 1414 | 89.41 | 25.94 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1826 | 24.00 | 7.62 | 0.48 |
| 2| 1969 | 26.55 | 9.00 | 0.52 |
| 3| 2055 | 27.32 | 9.86 | 0.53 |
| 5| 2365 | 31.37 | 12.33 | 0.60 |
| 10| 3149 | 41.23 | 18.41 | 0.75 |
| 40| 7651 | 99.61 | 54.64 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 22.81 | 7.37 | 0.42 |
| 2| 837 | 25.17 | 8.71 | 0.45 |
| 3| 828 | 24.02 | 9.01 | 0.45 |
| 5| 1165 | 28.12 | 11.50 | 0.51 |
| 10| 2005 | 41.07 | 18.46 | 0.70 |
| 39| 6465 | 99.05 | 53.91 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.17 | 8.91 | 0.48 |
| 2| 780 | 30.91 | 10.06 | 0.51 |
| 3| 1012 | 31.69 | 10.98 | 0.53 |
| 5| 1173 | 36.31 | 13.56 | 0.59 |
| 10| 2107 | 46.18 | 19.76 | 0.76 |
| 37| 6146 | 99.77 | 52.74 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.83 | 10.15 | 0.53 |
| 2| 821 | 35.92 | 11.40 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1196 | 41.93 | 15.06 | 0.65 |
| 10| 2094 | 55.10 | 22.12 | 0.85 |
| 28| 4717 | 95.59 | 45.35 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.58 | 0.64 |
| 2| 5935 | 36.04 | 12.09 | 0.79 |
| 3| 5994 | 41.41 | 13.85 | 0.85 |
| 4| 6270 | 55.09 | 18.59 | 1.01 |
| 5| 6490 | 65.94 | 22.28 | 1.13 |
| 6| 6476 | 69.70 | 23.35 | 1.17 |
| 7| 6790 | 82.32 | 27.75 | 1.31 |
| 8| 6888 | 93.83 | 31.61 | 1.44 |
| 9| 7019 | 99.73 | 33.60 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2166 | 7128 | 97.77 | 37.38 | 1.52 |

