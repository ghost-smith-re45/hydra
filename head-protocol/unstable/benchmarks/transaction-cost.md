--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-08 06:11:58.416373861 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.79 | 4.69 | 0.58 |
| 5| 6640 | 18.93 | 5.98 | 0.64 |
| 10| 7647 | 28.90 | 9.10 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 43.63 | 12.50 | 0.63 |
| 4 | 226 | 858 | 53.33 | 15.21 | 0.73 |
| 5 | 283 | 969 | 56.36 | 16.37 | 0.77 |
| 6 | 336 | 1081 | 67.71 | 19.44 | 0.89 |
| 7 | 394 | 1192 | 72.35 | 20.99 | 0.94 |
| 8 | 451 | 1303 | 89.09 | 25.35 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2173 | 29.42 | 10.45 | 0.56 |
| 5| 2319 | 30.12 | 11.99 | 0.58 |
| 10| 3089 | 39.79 | 18.02 | 0.74 |
| 39| 7594 | 98.04 | 53.55 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.54 | 7.30 | 0.41 |
| 2| 693 | 22.55 | 7.93 | 0.42 |
| 3| 904 | 25.45 | 9.45 | 0.46 |
| 5| 1283 | 30.13 | 12.06 | 0.54 |
| 10| 2104 | 40.47 | 18.29 | 0.70 |
| 43| 6700 | 97.29 | 56.10 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.17 | 8.91 | 0.48 |
| 2| 840 | 31.62 | 10.27 | 0.52 |
| 3| 869 | 31.97 | 11.01 | 0.53 |
| 5| 1202 | 36.38 | 13.58 | 0.59 |
| 10| 1952 | 44.26 | 19.17 | 0.73 |
| 35| 5732 | 99.60 | 51.31 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.83 | 10.15 | 0.53 |
| 2| 806 | 35.92 | 11.40 | 0.56 |
| 3| 986 | 38.58 | 12.82 | 0.60 |
| 5| 1251 | 42.61 | 15.27 | 0.66 |
| 10| 2045 | 54.13 | 21.83 | 0.83 |
| 29| 4966 | 99.11 | 47.06 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5796 | 27.09 | 9.10 | 0.69 |
| 2| 5894 | 34.95 | 11.69 | 0.78 |
| 3| 6016 | 43.94 | 14.71 | 0.88 |
| 4| 6096 | 49.12 | 16.46 | 0.93 |
| 5| 6446 | 65.35 | 22.05 | 1.12 |
| 6| 6576 | 70.16 | 23.64 | 1.18 |
| 7| 6810 | 83.97 | 28.38 | 1.33 |
| 8| 6821 | 88.20 | 29.69 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2160 | 7122 | 95.56 | 36.62 | 1.50 |

