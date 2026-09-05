--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-05 09:15:44.500717253 UTC |
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
| 1| 5837 | 10.57 | 3.36 | 0.52 |
| 2| 6035 | 13.01 | 4.14 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 43.71 | 12.51 | 0.63 |
| 4 | 228 | 858 | 49.57 | 14.29 | 0.69 |
| 5 | 284 | 969 | 56.22 | 16.33 | 0.76 |
| 6 | 338 | 1081 | 75.28 | 21.33 | 0.96 |
| 7 | 393 | 1192 | 87.17 | 24.59 | 1.08 |
| 8 | 450 | 1303 | 96.58 | 27.25 | 1.18 |
| 9 | 506 | 1414 | 91.80 | 26.51 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 23.92 | 7.60 | 0.48 |
| 2| 1992 | 26.58 | 9.01 | 0.52 |
| 3| 2013 | 26.31 | 9.58 | 0.52 |
| 5| 2452 | 32.40 | 12.62 | 0.61 |
| 10| 3099 | 39.51 | 17.95 | 0.74 |
| 39| 7536 | 97.44 | 53.39 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.57 | 7.30 | 0.41 |
| 2| 759 | 23.65 | 8.25 | 0.43 |
| 3| 830 | 24.13 | 9.05 | 0.45 |
| 5| 1166 | 28.04 | 11.48 | 0.51 |
| 10| 1999 | 38.97 | 17.87 | 0.68 |
| 43| 6782 | 97.78 | 56.24 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.50 | 8.46 | 0.46 |
| 2| 858 | 31.69 | 10.29 | 0.52 |
| 3| 868 | 31.97 | 11.01 | 0.53 |
| 5| 1246 | 36.95 | 13.76 | 0.60 |
| 10| 2107 | 49.04 | 20.54 | 0.79 |
| 38| 6156 | 99.17 | 53.27 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.87 | 10.16 | 0.53 |
| 2| 886 | 36.64 | 11.62 | 0.57 |
| 3| 1004 | 38.66 | 12.84 | 0.60 |
| 5| 1241 | 42.64 | 15.28 | 0.66 |
| 10| 1966 | 53.54 | 21.64 | 0.83 |
| 30| 4940 | 99.76 | 47.85 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5782 | 27.13 | 9.11 | 0.69 |
| 2| 5961 | 35.76 | 12.01 | 0.79 |
| 3| 6044 | 41.33 | 13.83 | 0.85 |
| 4| 6310 | 54.34 | 18.36 | 1.00 |
| 5| 6532 | 66.42 | 22.43 | 1.14 |
| 6| 6529 | 72.26 | 24.32 | 1.20 |
| 7| 6566 | 78.02 | 26.18 | 1.26 |
| 8| 6798 | 90.11 | 30.43 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 39 | 2223 | 7162 | 98.17 | 37.63 | 1.53 |

