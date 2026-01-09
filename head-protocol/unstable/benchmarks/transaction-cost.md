--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-09 04:55:52.009758789 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7646 | 29.55 | 9.33 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 40.05 | 11.65 | 0.59 |
| 4 | 227 | 858 | 51.00 | 14.64 | 0.71 |
| 5 | 284 | 969 | 59.84 | 17.17 | 0.80 |
| 6 | 339 | 1081 | 75.38 | 21.36 | 0.96 |
| 7 | 393 | 1192 | 86.39 | 24.27 | 1.08 |
| 8 | 449 | 1303 | 82.98 | 23.99 | 1.05 |
| 9 | 504 | 1418 | 91.91 | 26.48 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1825 | 24.37 | 7.71 | 0.48 |
| 2| 1996 | 26.58 | 9.01 | 0.52 |
| 3| 2084 | 26.94 | 9.77 | 0.53 |
| 5| 2391 | 31.34 | 12.32 | 0.60 |
| 10| 3248 | 42.83 | 18.87 | 0.78 |
| 39| 7711 | 98.60 | 53.74 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 768 | 23.59 | 8.23 | 0.43 |
| 3| 897 | 25.10 | 9.32 | 0.46 |
| 5| 1291 | 30.04 | 12.04 | 0.54 |
| 10| 2125 | 43.27 | 19.08 | 0.73 |
| 40| 6353 | 93.91 | 53.13 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 29.13 | 8.90 | 0.48 |
| 2| 834 | 31.62 | 10.28 | 0.52 |
| 3| 958 | 30.90 | 10.74 | 0.52 |
| 5| 1127 | 35.56 | 13.34 | 0.58 |
| 10| 1930 | 43.47 | 18.93 | 0.72 |
| 36| 6130 | 99.67 | 52.10 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1221 | 41.89 | 15.05 | 0.65 |
| 10| 2176 | 56.14 | 22.44 | 0.86 |
| 29| 4956 | 99.21 | 47.05 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5798 | 27.09 | 9.10 | 0.69 |
| 2| 5856 | 32.57 | 10.86 | 0.75 |
| 3| 6127 | 45.66 | 15.41 | 0.90 |
| 4| 6251 | 53.82 | 18.06 | 0.99 |
| 5| 6377 | 60.52 | 20.34 | 1.07 |
| 6| 6576 | 74.09 | 25.04 | 1.22 |
| 7| 6725 | 82.95 | 27.92 | 1.32 |
| 8| 6869 | 90.30 | 30.46 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.05 | 6.02 | 0.60 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1706 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2222 | 7161 | 98.93 | 37.88 | 1.54 |

