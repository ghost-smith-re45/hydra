--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-10 05:44:13.57248789 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 751 | 40.24 | 11.69 | 0.59 |
| 4 | 228 | 858 | 50.84 | 14.62 | 0.70 |
| 5 | 283 | 969 | 61.31 | 17.58 | 0.81 |
| 6 | 338 | 1081 | 70.28 | 20.14 | 0.91 |
| 7 | 394 | 1192 | 80.30 | 22.93 | 1.02 |
| 8 | 450 | 1307 | 92.00 | 26.10 | 1.14 |
| 9 | 506 | 1414 | 94.01 | 27.03 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1987 | 26.58 | 9.01 | 0.52 |
| 3| 2098 | 28.02 | 10.07 | 0.54 |
| 5| 2484 | 33.45 | 12.91 | 0.62 |
| 10| 3158 | 41.73 | 18.57 | 0.76 |
| 40| 7655 | 99.29 | 54.59 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.84 | 7.38 | 0.42 |
| 2| 739 | 23.58 | 8.23 | 0.43 |
| 3| 952 | 26.88 | 9.84 | 0.48 |
| 5| 1298 | 30.11 | 12.06 | 0.54 |
| 10| 1993 | 39.30 | 17.99 | 0.69 |
| 41| 6462 | 95.57 | 54.30 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 775 | 30.91 | 10.06 | 0.51 |
| 3| 902 | 30.23 | 10.54 | 0.51 |
| 5| 1206 | 34.37 | 13.04 | 0.58 |
| 10| 1916 | 43.25 | 18.88 | 0.72 |
| 36| 6002 | 96.78 | 51.30 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 809 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1274 | 42.72 | 15.30 | 0.66 |
| 10| 2051 | 54.72 | 22.01 | 0.84 |
| 29| 4950 | 99.45 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 6048 | 36.84 | 12.44 | 0.80 |
| 3| 6086 | 44.95 | 15.10 | 0.89 |
| 4| 6265 | 53.69 | 18.08 | 0.99 |
| 5| 6387 | 62.97 | 21.22 | 1.09 |
| 6| 6541 | 71.94 | 24.30 | 1.19 |
| 7| 6733 | 80.44 | 27.07 | 1.29 |
| 8| 6877 | 92.78 | 31.22 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 79.78 | 30.37 | 1.32 |
| 10 | 38 | 2161 | 7123 | 96.44 | 36.92 | 1.51 |

