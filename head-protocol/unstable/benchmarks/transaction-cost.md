--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-21 04:40:21.520647104 UTC |
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
| 1| 5834 | 10.36 | 3.28 | 0.51 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6643 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 635 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 751 | 42.50 | 12.23 | 0.61 |
| 4 | 228 | 862 | 53.86 | 15.37 | 0.73 |
| 5 | 282 | 969 | 61.46 | 17.56 | 0.82 |
| 6 | 338 | 1085 | 66.30 | 19.15 | 0.87 |
| 7 | 394 | 1196 | 74.18 | 21.39 | 0.96 |
| 8 | 448 | 1303 | 80.71 | 23.39 | 1.03 |
| 9 | 504 | 1414 | 92.52 | 26.80 | 1.15 |
| 10 | 560 | 1525 | 97.99 | 28.34 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.29 | 7.69 | 0.48 |
| 2| 1949 | 25.43 | 8.68 | 0.50 |
| 3| 2082 | 27.39 | 9.88 | 0.53 |
| 5| 2387 | 31.07 | 12.26 | 0.59 |
| 10| 3241 | 42.80 | 18.89 | 0.77 |
| 40| 7658 | 98.16 | 54.23 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.81 | 7.38 | 0.42 |
| 2| 838 | 25.37 | 8.75 | 0.46 |
| 3| 944 | 26.95 | 9.86 | 0.48 |
| 5| 1297 | 32.30 | 12.69 | 0.56 |
| 10| 1957 | 38.73 | 17.80 | 0.68 |
| 42| 6666 | 98.24 | 55.71 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 29.17 | 8.91 | 0.48 |
| 2| 819 | 29.15 | 9.59 | 0.49 |
| 3| 972 | 33.39 | 11.44 | 0.55 |
| 5| 1277 | 37.73 | 13.99 | 0.61 |
| 10| 2251 | 47.51 | 20.17 | 0.78 |
| 36| 5711 | 98.73 | 51.67 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 835 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.13 | 12.38 | 0.58 |
| 5| 1279 | 42.45 | 15.23 | 0.66 |
| 10| 2080 | 54.80 | 22.03 | 0.84 |
| 29| 4864 | 96.92 | 46.38 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.09 | 9.09 | 0.69 |
| 2| 5920 | 32.57 | 10.89 | 0.75 |
| 3| 6184 | 45.79 | 15.44 | 0.90 |
| 4| 6181 | 54.35 | 18.27 | 0.99 |
| 5| 6447 | 65.05 | 21.94 | 1.12 |
| 6| 6563 | 74.81 | 25.18 | 1.22 |
| 7| 6752 | 82.01 | 27.66 | 1.31 |
| 8| 6806 | 91.63 | 30.79 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2214 | 7154 | 99.31 | 38.01 | 1.54 |

