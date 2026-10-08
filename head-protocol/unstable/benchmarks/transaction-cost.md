--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-08 12:26:44.815599856 UTC |
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
| 1| 5837 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14286 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 41.12 | 11.90 | 0.60 |
| 4 | 226 | 858 | 53.86 | 15.34 | 0.73 |
| 5 | 284 | 974 | 56.21 | 16.30 | 0.76 |
| 6 | 339 | 1081 | 66.30 | 19.18 | 0.87 |
| 7 | 396 | 1196 | 86.18 | 24.26 | 1.07 |
| 8 | 451 | 1303 | 85.40 | 24.57 | 1.07 |
| 10 | 560 | 1525 | 99.44 | 28.68 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.00 | 7.62 | 0.48 |
| 2| 1924 | 25.80 | 8.77 | 0.51 |
| 3| 2055 | 27.32 | 9.86 | 0.53 |
| 5| 2359 | 31.16 | 12.28 | 0.59 |
| 10| 3190 | 41.69 | 18.56 | 0.76 |
| 41| 7685 | 98.89 | 55.13 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.81 | 7.37 | 0.42 |
| 2| 774 | 23.63 | 8.24 | 0.43 |
| 3| 936 | 27.06 | 9.90 | 0.48 |
| 5| 1233 | 29.58 | 11.94 | 0.53 |
| 10| 1952 | 38.72 | 17.79 | 0.68 |
| 40| 6428 | 94.61 | 53.37 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 29.17 | 8.91 | 0.48 |
| 2| 843 | 31.66 | 10.29 | 0.52 |
| 3| 958 | 33.40 | 11.43 | 0.54 |
| 5| 1222 | 37.10 | 13.79 | 0.60 |
| 10| 1928 | 43.33 | 18.90 | 0.72 |
| 38| 5963 | 97.53 | 52.73 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.87 | 10.16 | 0.53 |
| 2| 871 | 36.60 | 11.61 | 0.57 |
| 3| 1035 | 39.38 | 13.06 | 0.61 |
| 5| 1296 | 43.40 | 15.50 | 0.67 |
| 10| 2104 | 55.18 | 22.16 | 0.85 |
| 29| 4893 | 98.93 | 47.00 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5985 | 35.88 | 12.05 | 0.79 |
| 3| 5900 | 37.01 | 12.29 | 0.80 |
| 4| 6166 | 50.04 | 16.81 | 0.95 |
| 5| 6288 | 59.25 | 19.89 | 1.05 |
| 6| 6564 | 71.94 | 24.33 | 1.20 |
| 7| 6588 | 81.24 | 27.28 | 1.29 |
| 8| 6882 | 91.90 | 30.96 | 1.42 |
| 9| 6623 | 81.71 | 27.20 | 1.30 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 56 | 5867 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1138 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 99.82 | 38.19 | 1.55 |

