--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-20 07:34:24.041216558 UTC |
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
| 1| 5836 | 10.64 | 3.38 | 0.52 |
| 2| 6035 | 12.92 | 4.11 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6646 | 18.58 | 5.86 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10041 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 42.50 | 12.22 | 0.61 |
| 4 | 225 | 862 | 53.79 | 15.30 | 0.73 |
| 5 | 281 | 969 | 57.68 | 16.65 | 0.78 |
| 6 | 340 | 1081 | 68.08 | 19.57 | 0.89 |
| 7 | 394 | 1192 | 77.30 | 22.27 | 0.99 |
| 8 | 449 | 1303 | 88.67 | 25.20 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 23.92 | 7.60 | 0.48 |
| 2| 1988 | 26.96 | 9.10 | 0.52 |
| 3| 2013 | 25.91 | 9.48 | 0.52 |
| 5| 2486 | 32.45 | 12.63 | 0.61 |
| 10| 3127 | 41.06 | 18.37 | 0.75 |
| 40| 7663 | 97.52 | 54.10 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.84 | 7.37 | 0.41 |
| 2| 743 | 23.66 | 8.26 | 0.43 |
| 3| 934 | 26.94 | 9.85 | 0.48 |
| 5| 1257 | 30.85 | 12.29 | 0.54 |
| 10| 1962 | 40.15 | 18.22 | 0.69 |
| 40| 6379 | 93.74 | 53.09 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 27.54 | 8.47 | 0.46 |
| 2| 771 | 28.55 | 9.40 | 0.48 |
| 3| 957 | 30.94 | 10.75 | 0.52 |
| 5| 1228 | 34.41 | 13.05 | 0.58 |
| 10| 2154 | 45.30 | 19.51 | 0.75 |
| 38| 6120 | 98.78 | 53.15 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 825 | 35.89 | 11.39 | 0.56 |
| 3| 963 | 37.84 | 12.60 | 0.59 |
| 5| 1209 | 41.86 | 15.04 | 0.65 |
| 10| 2031 | 54.09 | 21.82 | 0.83 |
| 29| 5075 | 99.92 | 47.32 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5840 | 27.05 | 9.08 | 0.69 |
| 2| 6024 | 36.97 | 12.45 | 0.80 |
| 3| 6105 | 45.82 | 15.43 | 0.90 |
| 4| 6200 | 50.24 | 16.82 | 0.95 |
| 5| 6529 | 65.99 | 22.31 | 1.13 |
| 6| 6504 | 72.50 | 24.34 | 1.20 |
| 7| 6509 | 74.63 | 25.01 | 1.22 |
| 8| 6759 | 88.36 | 29.69 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 37 | 2107 | 7092 | 94.13 | 36.03 | 1.48 |

