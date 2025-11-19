--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-19 04:40:54.251911362 UTC |
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
| 1| 5837 | 10.95 | 3.49 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6645 | 18.58 | 5.86 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 41.73 | 12.09 | 0.61 |
| 4 | 224 | 858 | 52.25 | 14.98 | 0.72 |
| 5 | 283 | 974 | 59.59 | 17.14 | 0.80 |
| 6 | 342 | 1081 | 71.93 | 20.49 | 0.93 |
| 7 | 395 | 1192 | 80.89 | 23.04 | 1.02 |
| 8 | 454 | 1303 | 99.12 | 27.90 | 1.21 |
| 9 | 504 | 1414 | 92.14 | 26.65 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.29 | 7.69 | 0.48 |
| 2| 1916 | 25.39 | 8.67 | 0.50 |
| 3| 2081 | 26.94 | 9.77 | 0.53 |
| 5| 2412 | 32.19 | 12.57 | 0.61 |
| 10| 3131 | 40.57 | 18.23 | 0.75 |
| 40| 7685 | 99.13 | 54.52 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 599 | 22.57 | 7.30 | 0.41 |
| 2| 811 | 25.47 | 8.77 | 0.45 |
| 3| 896 | 25.74 | 9.54 | 0.47 |
| 5| 1347 | 32.37 | 12.69 | 0.56 |
| 10| 1951 | 38.64 | 17.81 | 0.68 |
| 41| 6609 | 97.91 | 54.97 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 29.13 | 8.90 | 0.48 |
| 2| 733 | 30.27 | 9.86 | 0.50 |
| 3| 946 | 30.98 | 10.76 | 0.52 |
| 5| 1288 | 37.78 | 14.00 | 0.61 |
| 10| 2121 | 46.99 | 20.00 | 0.77 |
| 35| 5794 | 96.07 | 50.39 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.87 | 10.16 | 0.53 |
| 2| 818 | 36.18 | 11.48 | 0.56 |
| 3| 896 | 37.13 | 12.38 | 0.58 |
| 5| 1395 | 44.15 | 15.73 | 0.68 |
| 10| 1951 | 53.08 | 21.50 | 0.82 |
| 30| 4925 | 99.13 | 47.63 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.12 | 9.10 | 0.69 |
| 2| 6032 | 36.96 | 12.47 | 0.80 |
| 3| 6035 | 45.31 | 15.22 | 0.89 |
| 4| 6323 | 56.23 | 18.99 | 1.02 |
| 5| 6308 | 59.60 | 19.97 | 1.05 |
| 6| 6547 | 74.51 | 25.12 | 1.22 |
| 7| 6680 | 80.12 | 26.95 | 1.29 |
| 8| 6987 | 95.82 | 32.39 | 1.47 |
| 9| 6931 | 98.97 | 33.29 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 567 | 6172 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 38 | 2162 | 7124 | 96.00 | 36.77 | 1.50 |

