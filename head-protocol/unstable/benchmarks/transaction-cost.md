--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-09 12:24:13.949947879 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6042 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.90 | 4.72 | 0.58 |
| 5| 6640 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14286 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 747 | 41.01 | 11.85 | 0.60 |
| 4 | 227 | 858 | 52.55 | 15.06 | 0.72 |
| 5 | 283 | 974 | 57.96 | 16.78 | 0.78 |
| 6 | 338 | 1085 | 75.74 | 21.44 | 0.96 |
| 7 | 396 | 1192 | 79.38 | 22.77 | 1.01 |
| 8 | 448 | 1303 | 93.97 | 26.52 | 1.16 |
| 9 | 505 | 1418 | 88.64 | 25.75 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1939 | 25.51 | 8.70 | 0.50 |
| 3| 2104 | 28.10 | 10.09 | 0.54 |
| 5| 2418 | 32.23 | 12.58 | 0.61 |
| 10| 3028 | 38.75 | 17.73 | 0.72 |
| 43| 7869 | 99.81 | 56.70 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.57 | 7.32 | 0.41 |
| 2| 746 | 23.62 | 8.25 | 0.43 |
| 3| 880 | 25.12 | 9.32 | 0.46 |
| 5| 1271 | 31.14 | 12.36 | 0.55 |
| 10| 2097 | 41.35 | 18.54 | 0.71 |
| 44| 6765 | 97.41 | 56.77 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 29.13 | 8.90 | 0.48 |
| 2| 783 | 30.98 | 10.08 | 0.51 |
| 3| 987 | 31.69 | 10.98 | 0.53 |
| 5| 1269 | 34.85 | 13.20 | 0.58 |
| 10| 2088 | 44.97 | 19.39 | 0.75 |
| 36| 6050 | 98.13 | 51.68 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 887 | 36.56 | 11.60 | 0.57 |
| 3| 939 | 37.87 | 12.61 | 0.59 |
| 5| 1376 | 44.00 | 15.69 | 0.68 |
| 10| 1896 | 52.49 | 21.34 | 0.81 |
| 29| 4912 | 99.25 | 47.06 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 27.04 | 9.07 | 0.69 |
| 2| 6006 | 36.89 | 12.43 | 0.80 |
| 3| 6067 | 44.57 | 14.98 | 0.89 |
| 4| 6280 | 56.22 | 19.00 | 1.02 |
| 5| 6432 | 61.84 | 20.84 | 1.08 |
| 6| 6365 | 65.51 | 21.93 | 1.12 |
| 7| 6450 | 72.41 | 24.30 | 1.19 |
| 8| 6819 | 88.64 | 29.82 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2222 | 7161 | 98.68 | 37.80 | 1.54 |

