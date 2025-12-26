--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-26 04:52:04.705682544 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.40 | 4.55 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 99.13 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10040 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 40.01 | 11.63 | 0.59 |
| 4 | 227 | 858 | 48.93 | 14.13 | 0.69 |
| 5 | 284 | 974 | 59.23 | 17.02 | 0.79 |
| 6 | 340 | 1081 | 74.76 | 21.13 | 0.95 |
| 7 | 395 | 1192 | 78.55 | 22.52 | 1.00 |
| 8 | 450 | 1303 | 87.77 | 25.09 | 1.10 |
| 9 | 505 | 1414 | 93.53 | 26.92 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.29 | 7.69 | 0.48 |
| 2| 1933 | 25.85 | 8.81 | 0.51 |
| 3| 2083 | 27.43 | 9.89 | 0.53 |
| 5| 2362 | 31.42 | 12.34 | 0.60 |
| 10| 3309 | 43.78 | 19.14 | 0.79 |
| 40| 7658 | 99.33 | 54.58 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 749 | 23.58 | 8.24 | 0.43 |
| 3| 942 | 26.90 | 9.84 | 0.48 |
| 5| 1223 | 29.07 | 11.78 | 0.52 |
| 10| 2090 | 42.30 | 18.78 | 0.72 |
| 42| 6712 | 98.44 | 55.76 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 29.17 | 8.91 | 0.48 |
| 2| 829 | 31.66 | 10.28 | 0.52 |
| 3| 972 | 33.51 | 11.47 | 0.55 |
| 5| 1302 | 35.72 | 13.46 | 0.59 |
| 10| 2154 | 46.14 | 19.75 | 0.76 |
| 35| 5913 | 97.10 | 50.69 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 832 | 35.88 | 11.39 | 0.56 |
| 3| 1018 | 39.34 | 13.05 | 0.61 |
| 5| 1348 | 43.95 | 15.68 | 0.68 |
| 10| 2015 | 54.38 | 21.91 | 0.84 |
| 29| 4826 | 97.59 | 46.60 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 27.05 | 9.08 | 0.69 |
| 2| 5929 | 35.84 | 12.05 | 0.79 |
| 3| 6114 | 45.65 | 15.42 | 0.90 |
| 4| 6287 | 54.73 | 18.43 | 1.00 |
| 5| 6250 | 55.85 | 18.66 | 1.01 |
| 6| 6664 | 75.10 | 25.35 | 1.23 |
| 7| 6718 | 79.97 | 26.95 | 1.29 |
| 8| 6870 | 92.06 | 31.10 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.72 | 10.56 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

