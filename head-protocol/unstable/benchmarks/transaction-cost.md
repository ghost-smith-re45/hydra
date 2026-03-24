--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-24 06:44:28.888869893 UTC |
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
| 2| 6042 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7650 | 29.11 | 9.17 | 0.79 |
| 43| 14286 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 41.42 | 11.99 | 0.60 |
| 4 | 228 | 858 | 49.74 | 14.38 | 0.69 |
| 5 | 283 | 969 | 55.88 | 16.22 | 0.76 |
| 6 | 338 | 1081 | 69.46 | 19.86 | 0.90 |
| 7 | 392 | 1192 | 83.23 | 23.65 | 1.05 |
| 8 | 452 | 1303 | 91.75 | 26.04 | 1.14 |
| 9 | 505 | 1414 | 98.59 | 28.19 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1999 | 26.92 | 9.08 | 0.52 |
| 3| 2053 | 27.39 | 9.88 | 0.53 |
| 5| 2365 | 31.32 | 12.32 | 0.60 |
| 10| 3039 | 38.90 | 17.76 | 0.73 |
| 40| 7725 | 97.75 | 54.17 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 611 | 22.57 | 7.32 | 0.41 |
| 2| 779 | 25.35 | 8.74 | 0.45 |
| 3| 875 | 25.74 | 9.54 | 0.47 |
| 5| 1272 | 31.21 | 12.37 | 0.55 |
| 10| 2059 | 40.72 | 18.35 | 0.70 |
| 40| 6526 | 96.40 | 53.85 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.54 | 8.47 | 0.46 |
| 2| 823 | 29.18 | 9.60 | 0.49 |
| 3| 1018 | 31.58 | 10.95 | 0.53 |
| 5| 1313 | 35.75 | 13.46 | 0.59 |
| 10| 1903 | 46.16 | 19.64 | 0.75 |
| 37| 6199 | 99.40 | 52.69 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 832 | 35.89 | 11.39 | 0.56 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1328 | 43.40 | 15.50 | 0.67 |
| 10| 1998 | 54.02 | 21.80 | 0.83 |
| 30| 4946 | 99.60 | 47.79 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.58 | 0.64 |
| 2| 5891 | 34.87 | 11.66 | 0.78 |
| 3| 6147 | 46.08 | 15.53 | 0.91 |
| 4| 6331 | 56.16 | 18.98 | 1.02 |
| 5| 6395 | 64.39 | 21.66 | 1.11 |
| 6| 6513 | 71.76 | 24.10 | 1.19 |
| 7| 6817 | 83.88 | 28.28 | 1.33 |
| 8| 6745 | 85.33 | 28.66 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

