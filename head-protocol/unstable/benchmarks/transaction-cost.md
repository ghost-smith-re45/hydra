--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-24 04:50:59.23236437 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.32 | 3.89 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2166 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 751 | 40.02 | 11.62 | 0.59 |
| 4 | 228 | 862 | 54.12 | 15.43 | 0.74 |
| 5 | 284 | 969 | 64.41 | 18.29 | 0.85 |
| 6 | 339 | 1081 | 66.04 | 19.05 | 0.87 |
| 7 | 395 | 1192 | 78.65 | 22.55 | 1.00 |
| 8 | 448 | 1303 | 92.38 | 26.24 | 1.14 |
| 10 | 560 | 1525 | 97.95 | 28.33 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1974 | 27.00 | 9.10 | 0.52 |
| 3| 2013 | 25.95 | 9.49 | 0.52 |
| 5| 2405 | 32.48 | 12.64 | 0.61 |
| 10| 3157 | 41.27 | 18.42 | 0.76 |
| 41| 7779 | 99.10 | 55.19 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.54 | 7.30 | 0.41 |
| 2| 769 | 24.28 | 8.45 | 0.44 |
| 3| 974 | 26.17 | 9.62 | 0.47 |
| 5| 1257 | 30.93 | 12.31 | 0.54 |
| 10| 1992 | 38.73 | 17.80 | 0.68 |
| 40| 6342 | 91.69 | 52.55 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.17 | 8.91 | 0.48 |
| 2| 864 | 31.54 | 10.26 | 0.52 |
| 3| 906 | 32.76 | 11.24 | 0.54 |
| 5| 1276 | 34.94 | 13.22 | 0.58 |
| 10| 1963 | 43.92 | 19.06 | 0.73 |
| 38| 6177 | 98.33 | 53.00 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 864 | 36.60 | 11.61 | 0.57 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1217 | 41.82 | 15.03 | 0.65 |
| 10| 2090 | 54.96 | 22.07 | 0.85 |
| 30| 5093 | 99.88 | 47.88 | 1.53 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 27.00 | 9.07 | 0.69 |
| 2| 5980 | 36.81 | 12.42 | 0.80 |
| 3| 6062 | 44.52 | 14.99 | 0.88 |
| 4| 6163 | 53.04 | 17.77 | 0.98 |
| 5| 6368 | 58.09 | 19.53 | 1.04 |
| 6| 6367 | 71.30 | 23.87 | 1.18 |
| 7| 6556 | 78.27 | 26.24 | 1.26 |
| 8| 6843 | 93.29 | 31.40 | 1.43 |
| 9| 6917 | 98.89 | 33.29 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 283 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1709 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 99.38 | 38.04 | 1.54 |

