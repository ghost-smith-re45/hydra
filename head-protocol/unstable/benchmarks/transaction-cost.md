--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-27 07:40:14.953362921 UTC |
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
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7650 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 99.06 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 42.27 | 12.15 | 0.61 |
| 4 | 228 | 858 | 52.61 | 15.07 | 0.72 |
| 5 | 281 | 969 | 62.26 | 17.72 | 0.82 |
| 6 | 338 | 1081 | 71.42 | 20.37 | 0.92 |
| 7 | 393 | 1192 | 75.82 | 21.73 | 0.97 |
| 8 | 448 | 1303 | 93.37 | 26.42 | 1.15 |
| 9 | 505 | 1414 | 96.70 | 27.68 | 1.19 |
| 10 | 560 | 1525 | 97.15 | 28.19 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1788 | 23.92 | 7.60 | 0.48 |
| 2| 1927 | 25.47 | 8.70 | 0.50 |
| 3| 2062 | 27.35 | 9.87 | 0.53 |
| 5| 2372 | 31.40 | 12.34 | 0.60 |
| 10| 3137 | 40.17 | 18.13 | 0.74 |
| 40| 7323 | 94.91 | 53.30 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.84 | 7.39 | 0.42 |
| 2| 739 | 24.35 | 8.47 | 0.44 |
| 3| 912 | 25.45 | 9.45 | 0.46 |
| 5| 1184 | 29.03 | 11.77 | 0.52 |
| 10| 1927 | 37.73 | 17.53 | 0.67 |
| 41| 6733 | 99.42 | 55.37 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.50 | 8.46 | 0.46 |
| 2| 820 | 29.22 | 9.61 | 0.49 |
| 3| 922 | 32.72 | 11.23 | 0.54 |
| 5| 1236 | 37.02 | 13.78 | 0.60 |
| 10| 2120 | 48.48 | 20.37 | 0.78 |
| 37| 6115 | 99.58 | 52.72 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 1030 | 39.34 | 13.05 | 0.61 |
| 5| 1195 | 41.86 | 15.04 | 0.65 |
| 10| 2057 | 54.02 | 21.80 | 0.83 |
| 28| 4766 | 96.25 | 45.57 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 26.92 | 9.04 | 0.69 |
| 2| 5913 | 35.92 | 12.06 | 0.79 |
| 3| 5970 | 40.32 | 13.45 | 0.84 |
| 4| 6177 | 50.71 | 16.99 | 0.95 |
| 5| 6499 | 65.22 | 21.95 | 1.12 |
| 6| 6453 | 67.38 | 22.65 | 1.14 |
| 7| 6738 | 77.96 | 26.24 | 1.27 |
| 8| 6706 | 86.84 | 29.13 | 1.36 |
| 9| 6916 | 97.82 | 32.88 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 38 | 2163 | 7125 | 97.33 | 37.23 | 1.52 |

