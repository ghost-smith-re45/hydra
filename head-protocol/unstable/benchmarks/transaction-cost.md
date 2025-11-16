--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-16 04:41:50.556227659 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.76 | 4.67 | 0.58 |
| 5| 6646 | 18.41 | 5.80 | 0.63 |
| 10| 7651 | 28.71 | 9.03 | 0.78 |
| 43| 14286 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10079 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 171 | 747 | 43.56 | 12.48 | 0.63 |
| 4 | 228 | 858 | 51.29 | 14.75 | 0.71 |
| 5 | 283 | 969 | 64.61 | 18.37 | 0.85 |
| 6 | 337 | 1081 | 73.35 | 20.76 | 0.94 |
| 7 | 395 | 1196 | 81.00 | 23.11 | 1.02 |
| 8 | 450 | 1303 | 94.26 | 26.64 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1829 | 24.00 | 7.62 | 0.48 |
| 2| 1977 | 26.58 | 9.01 | 0.52 |
| 3| 2062 | 27.27 | 9.85 | 0.53 |
| 5| 2385 | 31.12 | 12.27 | 0.60 |
| 10| 3220 | 41.86 | 18.60 | 0.76 |
| 42| 7853 | 99.42 | 55.94 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 22.54 | 7.31 | 0.41 |
| 2| 796 | 23.59 | 8.23 | 0.44 |
| 3| 914 | 27.07 | 9.88 | 0.48 |
| 5| 1148 | 28.87 | 11.73 | 0.52 |
| 10| 1974 | 38.80 | 17.83 | 0.68 |
| 46| 6959 | 99.95 | 58.85 | 1.69 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.13 | 8.90 | 0.48 |
| 2| 777 | 30.94 | 10.07 | 0.51 |
| 3| 941 | 30.87 | 10.74 | 0.52 |
| 5| 1238 | 34.30 | 13.02 | 0.58 |
| 10| 1981 | 43.96 | 19.09 | 0.73 |
| 33| 5776 | 94.20 | 48.59 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 820 | 35.85 | 11.38 | 0.56 |
| 3| 1006 | 38.66 | 12.84 | 0.60 |
| 5| 1366 | 43.58 | 15.57 | 0.67 |
| 10| 1967 | 53.79 | 21.72 | 0.83 |
| 28| 4804 | 97.10 | 45.82 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.00 | 9.07 | 0.69 |
| 2| 5894 | 34.95 | 11.69 | 0.78 |
| 3| 6182 | 45.80 | 15.45 | 0.90 |
| 4| 6277 | 55.08 | 18.57 | 1.01 |
| 5| 6486 | 62.27 | 21.09 | 1.09 |
| 6| 6394 | 64.68 | 21.63 | 1.11 |
| 7| 6732 | 81.14 | 27.36 | 1.30 |
| 8| 7046 | 94.50 | 31.93 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.08 | 6.83 | 0.62 |
| 10 | 5 | 283 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 38 | 2163 | 7126 | 96.00 | 36.77 | 1.50 |

