--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-22 05:05:15.858391937 UTC |
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
| 1| 5836 | 10.78 | 3.43 | 0.52 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14286 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 747 | 39.92 | 11.61 | 0.59 |
| 4 | 228 | 862 | 48.23 | 13.99 | 0.68 |
| 5 | 282 | 969 | 57.73 | 16.66 | 0.78 |
| 6 | 338 | 1081 | 69.29 | 19.78 | 0.90 |
| 7 | 396 | 1196 | 76.11 | 21.81 | 0.97 |
| 8 | 448 | 1303 | 79.92 | 23.10 | 1.02 |
| 9 | 505 | 1414 | 93.81 | 26.99 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 23.92 | 7.60 | 0.48 |
| 2| 1966 | 26.83 | 9.06 | 0.52 |
| 3| 2011 | 25.95 | 9.49 | 0.52 |
| 5| 2386 | 31.52 | 12.37 | 0.60 |
| 10| 3072 | 38.79 | 17.74 | 0.73 |
| 39| 7581 | 98.87 | 53.76 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 22.81 | 7.37 | 0.42 |
| 2| 768 | 24.27 | 8.46 | 0.44 |
| 3| 872 | 25.13 | 9.34 | 0.46 |
| 5| 1214 | 29.18 | 11.81 | 0.52 |
| 10| 2095 | 41.14 | 18.48 | 0.71 |
| 41| 6583 | 99.31 | 55.26 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 29.17 | 8.91 | 0.48 |
| 2| 813 | 29.15 | 9.59 | 0.49 |
| 3| 1007 | 31.69 | 10.98 | 0.53 |
| 5| 1384 | 36.47 | 13.68 | 0.60 |
| 10| 1970 | 44.38 | 19.20 | 0.73 |
| 35| 6051 | 98.57 | 51.19 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 1007 | 38.96 | 12.93 | 0.60 |
| 5| 1286 | 42.49 | 15.24 | 0.66 |
| 10| 2182 | 56.14 | 22.46 | 0.86 |
| 29| 4815 | 97.67 | 46.59 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.09 | 9.08 | 0.69 |
| 2| 5846 | 31.44 | 10.45 | 0.74 |
| 3| 5988 | 41.60 | 13.90 | 0.85 |
| 4| 6206 | 51.14 | 17.20 | 0.96 |
| 5| 6458 | 64.94 | 21.91 | 1.12 |
| 6| 6476 | 68.97 | 23.20 | 1.16 |
| 7| 6526 | 77.61 | 25.98 | 1.25 |
| 8| 6962 | 89.44 | 30.09 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1710 | 6857 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2162 | 7124 | 96.88 | 37.08 | 1.51 |

