--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-19 04:50:56.791854744 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6041 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.76 | 4.67 | 0.58 |
| 5| 6646 | 18.88 | 5.97 | 0.64 |
| 10| 7648 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1270 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 42.27 | 12.15 | 0.61 |
| 4 | 228 | 858 | 50.85 | 14.62 | 0.70 |
| 5 | 284 | 969 | 57.86 | 16.73 | 0.78 |
| 6 | 337 | 1081 | 65.74 | 18.97 | 0.87 |
| 7 | 394 | 1192 | 86.14 | 24.21 | 1.07 |
| 8 | 452 | 1303 | 98.40 | 27.63 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.29 | 7.69 | 0.48 |
| 2| 1924 | 25.84 | 8.78 | 0.51 |
| 3| 2055 | 27.39 | 9.88 | 0.53 |
| 5| 2328 | 30.69 | 12.14 | 0.59 |
| 10| 3084 | 39.59 | 17.97 | 0.74 |
| 39| 7553 | 97.85 | 53.52 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 750 | 24.00 | 8.38 | 0.44 |
| 3| 927 | 25.72 | 9.52 | 0.47 |
| 5| 1195 | 28.81 | 11.72 | 0.52 |
| 10| 2047 | 39.91 | 18.15 | 0.69 |
| 41| 6496 | 95.51 | 54.25 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.54 | 8.47 | 0.46 |
| 2| 774 | 28.51 | 9.39 | 0.48 |
| 3| 1005 | 31.61 | 10.96 | 0.53 |
| 5| 1320 | 35.72 | 13.46 | 0.59 |
| 10| 2108 | 48.75 | 20.45 | 0.78 |
| 37| 6348 | 99.64 | 52.77 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.83 | 10.15 | 0.53 |
| 2| 832 | 35.85 | 11.38 | 0.56 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1342 | 43.95 | 15.68 | 0.68 |
| 10| 1978 | 53.31 | 21.58 | 0.82 |
| 29| 4885 | 97.78 | 46.65 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 5916 | 34.76 | 11.63 | 0.78 |
| 3| 6105 | 45.70 | 15.42 | 0.90 |
| 4| 6374 | 56.10 | 18.92 | 1.02 |
| 5| 6407 | 64.26 | 21.65 | 1.11 |
| 6| 6384 | 67.83 | 22.82 | 1.14 |
| 7| 6645 | 78.35 | 26.29 | 1.27 |
| 8| 6949 | 96.05 | 32.47 | 1.47 |
| 9| 6880 | 90.35 | 30.23 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6002 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 567 | 6171 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 37 | 2108 | 7093 | 94.83 | 36.27 | 1.49 |

