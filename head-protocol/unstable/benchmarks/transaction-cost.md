--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-26 10:27:51.583101199 UTC |
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
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.78 | 4.68 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10083 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 40.22 | 11.69 | 0.59 |
| 4 | 227 | 858 | 48.19 | 13.99 | 0.68 |
| 5 | 283 | 974 | 63.94 | 18.15 | 0.84 |
| 6 | 338 | 1081 | 75.27 | 21.29 | 0.96 |
| 7 | 394 | 1192 | 82.42 | 23.32 | 1.04 |
| 8 | 449 | 1303 | 81.05 | 23.58 | 1.03 |
| 10 | 560 | 1525 | 97.19 | 28.08 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.29 | 7.69 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2114 | 28.46 | 10.18 | 0.55 |
| 5| 2389 | 31.33 | 12.32 | 0.60 |
| 10| 3263 | 42.46 | 18.78 | 0.77 |
| 40| 7636 | 98.63 | 54.39 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.53 | 7.30 | 0.41 |
| 2| 723 | 22.60 | 7.95 | 0.42 |
| 3| 978 | 26.41 | 9.72 | 0.48 |
| 5| 1227 | 29.15 | 11.79 | 0.52 |
| 10| 1929 | 39.41 | 18.00 | 0.68 |
| 41| 6645 | 98.66 | 55.14 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.51 | 8.47 | 0.46 |
| 2| 778 | 30.98 | 10.08 | 0.51 |
| 3| 1034 | 31.61 | 10.96 | 0.53 |
| 5| 1256 | 34.94 | 13.22 | 0.58 |
| 10| 2191 | 50.14 | 20.87 | 0.80 |
| 37| 6157 | 99.31 | 52.67 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1248 | 42.60 | 15.27 | 0.66 |
| 10| 2019 | 54.17 | 21.83 | 0.83 |
| 30| 4993 | 99.39 | 47.74 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 26.92 | 9.05 | 0.69 |
| 2| 5941 | 35.96 | 12.08 | 0.79 |
| 3| 6025 | 41.56 | 13.90 | 0.85 |
| 4| 6303 | 54.60 | 18.44 | 1.00 |
| 5| 6398 | 63.97 | 21.55 | 1.10 |
| 6| 6543 | 74.58 | 25.09 | 1.22 |
| 7| 6845 | 84.79 | 28.63 | 1.34 |
| 8| 6708 | 82.82 | 27.81 | 1.32 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 39 | 2222 | 7161 | 99.38 | 38.04 | 1.54 |

