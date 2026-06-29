--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-29 10:17:10.28135999 UTC |
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
| 1| 5840 | 10.93 | 3.49 | 0.52 |
| 2| 6038 | 12.82 | 4.07 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 29.57 | 9.34 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 40.27 | 11.70 | 0.59 |
| 4 | 226 | 858 | 52.64 | 15.08 | 0.72 |
| 5 | 283 | 969 | 64.64 | 18.32 | 0.85 |
| 6 | 339 | 1081 | 64.73 | 18.77 | 0.86 |
| 7 | 392 | 1192 | 71.97 | 20.81 | 0.93 |
| 8 | 449 | 1303 | 91.93 | 26.13 | 1.14 |
| 9 | 506 | 1414 | 89.86 | 26.10 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 1930 | 25.80 | 8.77 | 0.51 |
| 3| 2013 | 25.91 | 9.48 | 0.52 |
| 5| 2495 | 33.26 | 12.87 | 0.62 |
| 10| 3251 | 42.51 | 18.80 | 0.77 |
| 39| 7521 | 98.49 | 53.68 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 607 | 22.53 | 7.29 | 0.41 |
| 2| 814 | 25.52 | 8.78 | 0.46 |
| 3| 896 | 25.10 | 9.32 | 0.46 |
| 5| 1220 | 29.08 | 11.77 | 0.52 |
| 10| 2081 | 42.01 | 18.72 | 0.72 |
| 40| 6424 | 96.61 | 53.90 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.09 | 8.89 | 0.48 |
| 2| 778 | 30.87 | 10.05 | 0.51 |
| 3| 1010 | 31.62 | 10.96 | 0.53 |
| 5| 1352 | 38.45 | 14.21 | 0.62 |
| 10| 2163 | 46.01 | 19.72 | 0.76 |
| 36| 6030 | 97.62 | 51.55 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.79 | 10.15 | 0.53 |
| 2| 888 | 36.52 | 11.59 | 0.57 |
| 3| 1001 | 38.59 | 12.82 | 0.60 |
| 5| 1267 | 42.57 | 15.26 | 0.66 |
| 10| 1965 | 53.50 | 21.63 | 0.82 |
| 28| 4786 | 96.49 | 45.63 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.92 | 9.04 | 0.69 |
| 2| 5938 | 35.93 | 12.07 | 0.79 |
| 3| 6015 | 41.33 | 13.84 | 0.85 |
| 4| 6292 | 55.07 | 18.59 | 1.01 |
| 5| 6553 | 64.76 | 21.87 | 1.12 |
| 6| 6492 | 72.17 | 24.27 | 1.19 |
| 7| 6734 | 83.11 | 27.96 | 1.32 |
| 8| 6957 | 91.18 | 30.80 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 37 | 2108 | 7093 | 93.51 | 35.81 | 1.48 |

