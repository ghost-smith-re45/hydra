--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-30 11:35:38.920500582 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.99 | 4.13 | 0.55 |
| 3| 6239 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 41.08 | 11.87 | 0.60 |
| 4 | 227 | 858 | 52.51 | 15.02 | 0.72 |
| 5 | 281 | 969 | 62.28 | 17.72 | 0.82 |
| 6 | 338 | 1081 | 74.72 | 21.08 | 0.95 |
| 7 | 395 | 1192 | 72.44 | 21.01 | 0.94 |
| 8 | 450 | 1303 | 90.15 | 25.66 | 1.12 |
| 9 | 505 | 1414 | 94.37 | 27.13 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2090 | 27.06 | 9.80 | 0.53 |
| 5| 2332 | 30.33 | 12.04 | 0.58 |
| 10| 3211 | 42.57 | 18.79 | 0.77 |
| 41| 7567 | 95.98 | 54.28 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.54 | 7.31 | 0.41 |
| 2| 697 | 22.62 | 7.95 | 0.42 |
| 3| 849 | 24.07 | 9.03 | 0.45 |
| 5| 1277 | 30.14 | 12.08 | 0.54 |
| 10| 1945 | 38.84 | 17.85 | 0.68 |
| 40| 6460 | 95.55 | 53.60 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 27.54 | 8.47 | 0.46 |
| 2| 832 | 29.22 | 9.61 | 0.49 |
| 3| 941 | 32.80 | 11.25 | 0.54 |
| 5| 1349 | 36.55 | 13.70 | 0.60 |
| 10| 2107 | 48.87 | 20.47 | 0.79 |
| 38| 6175 | 99.61 | 53.39 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 1026 | 38.62 | 12.83 | 0.60 |
| 5| 1314 | 43.35 | 15.49 | 0.67 |
| 10| 1939 | 52.86 | 21.43 | 0.82 |
| 30| 4929 | 98.64 | 47.51 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 27.00 | 9.07 | 0.69 |
| 2| 6054 | 36.93 | 12.45 | 0.80 |
| 3| 6206 | 46.81 | 15.83 | 0.92 |
| 4| 6198 | 54.16 | 18.19 | 0.99 |
| 5| 6451 | 63.67 | 21.44 | 1.10 |
| 6| 6680 | 75.84 | 25.67 | 1.24 |
| 7| 6769 | 84.70 | 28.57 | 1.34 |
| 8| 6880 | 92.43 | 31.15 | 1.42 |
| 9| 6920 | 98.69 | 33.19 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.68 | 37.80 | 1.54 |

