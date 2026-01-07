--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-07 04:56:48.822285533 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7648 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 43.53 | 12.46 | 0.62 |
| 4 | 226 | 858 | 47.71 | 13.87 | 0.67 |
| 5 | 284 | 969 | 64.10 | 18.19 | 0.84 |
| 6 | 337 | 1081 | 65.95 | 18.99 | 0.87 |
| 7 | 393 | 1192 | 71.71 | 20.75 | 0.93 |
| 8 | 449 | 1303 | 92.00 | 26.10 | 1.14 |
| 9 | 504 | 1414 | 88.44 | 25.59 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.29 | 7.69 | 0.48 |
| 2| 1955 | 25.84 | 8.78 | 0.51 |
| 3| 2054 | 26.94 | 9.77 | 0.53 |
| 5| 2317 | 30.16 | 12.00 | 0.58 |
| 10| 3081 | 39.55 | 17.96 | 0.73 |
| 40| 7688 | 99.00 | 54.46 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.81 | 7.37 | 0.42 |
| 2| 793 | 24.05 | 8.40 | 0.44 |
| 3| 853 | 24.03 | 9.02 | 0.45 |
| 5| 1259 | 31.14 | 12.36 | 0.55 |
| 10| 2035 | 39.06 | 17.92 | 0.68 |
| 40| 6420 | 94.64 | 53.36 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 932 | 32.72 | 11.23 | 0.54 |
| 5| 1290 | 37.81 | 14.01 | 0.61 |
| 10| 1966 | 47.48 | 20.05 | 0.76 |
| 37| 5983 | 97.92 | 52.21 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 885 | 36.64 | 11.62 | 0.57 |
| 3| 896 | 37.16 | 12.39 | 0.58 |
| 5| 1158 | 41.29 | 14.86 | 0.64 |
| 10| 2026 | 54.10 | 21.82 | 0.83 |
| 29| 4801 | 97.39 | 46.52 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 27.09 | 9.09 | 0.69 |
| 2| 5913 | 36.07 | 12.11 | 0.79 |
| 3| 6063 | 42.54 | 14.25 | 0.86 |
| 4| 6257 | 54.65 | 18.42 | 1.00 |
| 5| 6488 | 65.79 | 22.24 | 1.13 |
| 6| 6562 | 70.26 | 23.62 | 1.18 |
| 7| 6696 | 83.35 | 28.04 | 1.32 |
| 8| 6901 | 91.06 | 30.74 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1706 | 6853 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.93 | 37.88 | 1.54 |

