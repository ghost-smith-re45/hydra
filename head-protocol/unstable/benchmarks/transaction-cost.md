--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-08 04:50:32.038853959 UTC |
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
| 1| 5834 | 10.76 | 3.42 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7650 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 42.62 | 12.25 | 0.62 |
| 4 | 225 | 858 | 51.14 | 14.69 | 0.71 |
| 5 | 281 | 969 | 56.33 | 16.36 | 0.77 |
| 6 | 339 | 1081 | 71.79 | 20.50 | 0.93 |
| 7 | 394 | 1192 | 78.58 | 22.44 | 1.00 |
| 8 | 448 | 1303 | 82.96 | 23.94 | 1.05 |
| 9 | 506 | 1414 | 91.01 | 26.20 | 1.14 |
| 10 | 560 | 1525 | 98.20 | 28.51 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 23.92 | 7.60 | 0.48 |
| 2| 1994 | 26.58 | 9.01 | 0.52 |
| 3| 2014 | 25.98 | 9.50 | 0.52 |
| 5| 2531 | 34.26 | 13.15 | 0.63 |
| 10| 3212 | 42.27 | 18.72 | 0.77 |
| 39| 7515 | 96.04 | 52.99 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.81 | 7.37 | 0.42 |
| 2| 795 | 23.59 | 8.23 | 0.44 |
| 3| 923 | 25.72 | 9.52 | 0.47 |
| 5| 1175 | 28.01 | 11.47 | 0.51 |
| 10| 1944 | 39.15 | 17.95 | 0.68 |
| 39| 6257 | 92.89 | 52.22 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 29.17 | 8.91 | 0.48 |
| 2| 783 | 30.98 | 10.08 | 0.51 |
| 3| 986 | 31.58 | 10.95 | 0.53 |
| 5| 1256 | 35.05 | 13.25 | 0.58 |
| 10| 2037 | 44.37 | 19.21 | 0.74 |
| 33| 5393 | 94.97 | 48.62 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 890 | 36.64 | 11.62 | 0.57 |
| 3| 993 | 38.59 | 12.82 | 0.60 |
| 5| 1258 | 42.49 | 15.24 | 0.66 |
| 10| 2015 | 54.06 | 21.81 | 0.83 |
| 29| 4902 | 98.23 | 46.76 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.09 | 0.69 |
| 2| 5774 | 28.45 | 9.35 | 0.70 |
| 3| 6037 | 42.25 | 14.18 | 0.86 |
| 4| 6141 | 46.92 | 15.66 | 0.91 |
| 5| 6355 | 60.77 | 20.41 | 1.07 |
| 6| 6596 | 73.57 | 24.79 | 1.21 |
| 7| 6708 | 79.52 | 26.73 | 1.28 |
| 8| 6871 | 89.15 | 29.97 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 37 | 2106 | 7091 | 94.83 | 36.27 | 1.49 |

