--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-17 10:29:23.951813873 UTC |
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
| 1| 5838 | 10.61 | 3.37 | 0.52 |
| 2| 6039 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 41.23 | 11.93 | 0.60 |
| 4 | 226 | 858 | 50.83 | 14.64 | 0.70 |
| 5 | 282 | 974 | 64.90 | 18.42 | 0.85 |
| 6 | 340 | 1081 | 71.33 | 20.27 | 0.92 |
| 7 | 394 | 1192 | 85.34 | 24.20 | 1.07 |
| 8 | 451 | 1303 | 85.95 | 24.70 | 1.08 |
| 9 | 506 | 1414 | 98.19 | 27.87 | 1.21 |
| 10 | 560 | 1525 | 97.69 | 28.27 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.92 | 7.32 | 0.47 |
| 2| 1880 | 24.47 | 8.41 | 0.49 |
| 3| 2155 | 29.14 | 10.39 | 0.56 |
| 5| 2273 | 29.01 | 11.68 | 0.57 |
| 10| 3079 | 39.57 | 17.96 | 0.73 |
| 42| 7860 | 98.96 | 55.81 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 605 | 22.84 | 7.39 | 0.41 |
| 2| 754 | 23.62 | 8.25 | 0.43 |
| 3| 986 | 28.07 | 10.17 | 0.49 |
| 5| 1254 | 30.90 | 12.30 | 0.54 |
| 10| 1944 | 39.34 | 17.99 | 0.68 |
| 41| 6458 | 94.55 | 53.98 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 29.17 | 8.91 | 0.48 |
| 2| 836 | 29.22 | 9.61 | 0.49 |
| 3| 1038 | 32.40 | 11.20 | 0.54 |
| 5| 1318 | 35.65 | 13.44 | 0.59 |
| 10| 2040 | 44.78 | 19.34 | 0.74 |
| 35| 5624 | 93.04 | 49.46 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.83 | 10.15 | 0.53 |
| 2| 838 | 35.89 | 11.39 | 0.56 |
| 3| 934 | 37.95 | 12.63 | 0.59 |
| 5| 1345 | 44.07 | 15.71 | 0.68 |
| 10| 1986 | 53.41 | 21.63 | 0.83 |
| 30| 4921 | 99.61 | 47.75 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5842 | 27.08 | 9.09 | 0.69 |
| 2| 5941 | 35.92 | 12.06 | 0.79 |
| 3| 6109 | 45.90 | 15.49 | 0.90 |
| 4| 5999 | 42.67 | 14.14 | 0.86 |
| 5| 6523 | 66.04 | 22.35 | 1.13 |
| 6| 6700 | 75.29 | 25.38 | 1.24 |
| 7| 6664 | 79.94 | 26.99 | 1.28 |
| 8| 6690 | 83.51 | 28.00 | 1.32 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1710 | 6857 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2217 | 7156 | 99.82 | 38.19 | 1.55 |

