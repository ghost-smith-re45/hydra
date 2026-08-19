--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-19 05:55:35.694112846 UTC |
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
| 1| 5837 | 10.26 | 3.25 | 0.51 |
| 2| 6037 | 12.70 | 4.03 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 42.57 | 12.25 | 0.62 |
| 4 | 227 | 858 | 50.95 | 14.67 | 0.71 |
| 5 | 282 | 969 | 57.69 | 16.65 | 0.78 |
| 6 | 342 | 1081 | 69.62 | 19.90 | 0.90 |
| 7 | 394 | 1192 | 78.01 | 22.30 | 0.99 |
| 8 | 452 | 1303 | 85.69 | 24.64 | 1.08 |
| 9 | 507 | 1414 | 91.34 | 26.45 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1951 | 25.85 | 8.78 | 0.51 |
| 3| 2174 | 29.17 | 10.39 | 0.56 |
| 5| 2360 | 31.41 | 12.34 | 0.60 |
| 10| 3318 | 43.80 | 19.15 | 0.79 |
| 41| 7627 | 97.32 | 54.68 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 785 | 25.47 | 8.78 | 0.45 |
| 3| 898 | 25.16 | 9.33 | 0.46 |
| 5| 1320 | 31.90 | 12.59 | 0.56 |
| 10| 1926 | 37.43 | 17.44 | 0.66 |
| 39| 6585 | 99.46 | 54.08 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.50 | 8.46 | 0.46 |
| 2| 775 | 30.94 | 10.07 | 0.51 |
| 3| 910 | 32.76 | 11.24 | 0.54 |
| 5| 1285 | 35.08 | 13.26 | 0.59 |
| 10| 2047 | 47.85 | 20.18 | 0.77 |
| 37| 6128 | 99.95 | 52.81 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.87 | 10.16 | 0.53 |
| 2| 837 | 35.92 | 11.40 | 0.56 |
| 3| 993 | 38.59 | 12.82 | 0.60 |
| 5| 1342 | 43.28 | 15.47 | 0.67 |
| 10| 2035 | 53.79 | 21.72 | 0.83 |
| 29| 4905 | 99.62 | 47.17 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5809 | 27.08 | 9.08 | 0.69 |
| 2| 5967 | 35.76 | 12.02 | 0.79 |
| 3| 6251 | 47.02 | 15.89 | 0.92 |
| 4| 6195 | 51.79 | 17.38 | 0.97 |
| 5| 6334 | 62.68 | 21.07 | 1.09 |
| 6| 6549 | 73.36 | 24.66 | 1.21 |
| 7| 6727 | 83.92 | 28.35 | 1.33 |
| 8| 6839 | 89.39 | 30.09 | 1.39 |
| 9| 6922 | 96.38 | 32.47 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.52 | 6.86 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1134 | 6508 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.49 | 37.73 | 1.53 |

