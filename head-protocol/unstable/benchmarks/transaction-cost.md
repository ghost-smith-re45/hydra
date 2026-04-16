--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-16 07:21:59.72848709 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.70 | 4.03 | 0.55 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6645 | 19.00 | 6.01 | 0.64 |
| 10| 7647 | 29.49 | 9.31 | 0.79 |
| 43| 14282 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10041 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 43.71 | 12.51 | 0.63 |
| 4 | 226 | 858 | 49.48 | 14.30 | 0.69 |
| 5 | 283 | 969 | 62.88 | 17.93 | 0.83 |
| 6 | 340 | 1081 | 75.91 | 21.56 | 0.97 |
| 7 | 394 | 1196 | 80.32 | 22.82 | 1.02 |
| 8 | 450 | 1303 | 94.28 | 26.70 | 1.16 |
| 9 | 504 | 1414 | 94.48 | 27.15 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.40 | 8.39 | 0.49 |
| 3| 2183 | 29.54 | 10.48 | 0.56 |
| 5| 2450 | 32.07 | 12.54 | 0.61 |
| 10| 3167 | 41.20 | 18.42 | 0.76 |
| 38| 7424 | 97.16 | 52.62 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.84 | 7.38 | 0.41 |
| 2| 773 | 23.62 | 8.25 | 0.43 |
| 3| 899 | 25.03 | 9.30 | 0.46 |
| 5| 1222 | 29.04 | 11.76 | 0.52 |
| 10| 1934 | 38.64 | 17.78 | 0.68 |
| 43| 6648 | 95.69 | 55.64 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.54 | 8.47 | 0.46 |
| 2| 771 | 28.55 | 9.40 | 0.48 |
| 3| 968 | 30.94 | 10.75 | 0.52 |
| 5| 1271 | 34.85 | 13.20 | 0.58 |
| 10| 2005 | 44.34 | 19.19 | 0.74 |
| 35| 5687 | 94.43 | 49.91 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 816 | 35.89 | 11.39 | 0.56 |
| 3| 1055 | 39.30 | 13.04 | 0.61 |
| 5| 1162 | 41.11 | 14.82 | 0.64 |
| 10| 1897 | 52.71 | 21.39 | 0.81 |
| 29| 4802 | 97.35 | 46.51 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5796 | 27.13 | 9.09 | 0.69 |
| 2| 5870 | 34.96 | 11.71 | 0.78 |
| 3| 5992 | 41.25 | 13.82 | 0.85 |
| 4| 6141 | 50.23 | 16.84 | 0.95 |
| 5| 6316 | 59.54 | 19.97 | 1.05 |
| 6| 6644 | 74.52 | 25.24 | 1.23 |
| 7| 6751 | 82.01 | 27.67 | 1.31 |
| 8| 7014 | 94.85 | 32.10 | 1.46 |
| 9| 6970 | 98.50 | 33.14 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2220 | 7160 | 98.05 | 37.58 | 1.53 |

