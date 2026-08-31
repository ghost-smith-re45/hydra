--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-31 11:52:16.625009257 UTC |
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
| 1| 5834 | 10.57 | 3.36 | 0.52 |
| 2| 6035 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 19.02 | 6.02 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 640 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 747 | 43.61 | 12.48 | 0.63 |
| 4 | 228 | 858 | 49.58 | 14.30 | 0.69 |
| 5 | 284 | 969 | 56.87 | 16.52 | 0.77 |
| 6 | 339 | 1081 | 69.46 | 19.86 | 0.90 |
| 7 | 395 | 1192 | 84.54 | 23.87 | 1.06 |
| 8 | 449 | 1303 | 82.92 | 23.93 | 1.05 |
| 9 | 504 | 1414 | 92.27 | 26.68 | 1.15 |
| 10 | 560 | 1525 | 96.56 | 27.87 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1931 | 25.55 | 8.71 | 0.50 |
| 3| 2119 | 28.10 | 10.09 | 0.54 |
| 5| 2425 | 32.79 | 12.73 | 0.61 |
| 10| 3247 | 42.78 | 18.86 | 0.77 |
| 39| 7541 | 96.49 | 53.12 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.53 | 7.30 | 0.41 |
| 2| 786 | 24.05 | 8.39 | 0.44 |
| 3| 872 | 25.16 | 9.33 | 0.46 |
| 5| 1198 | 29.18 | 11.80 | 0.52 |
| 10| 1957 | 37.36 | 17.42 | 0.66 |
| 40| 6461 | 96.99 | 54.02 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 26.79 | 8.25 | 0.45 |
| 2| 771 | 28.47 | 9.38 | 0.48 |
| 3| 1007 | 31.61 | 10.96 | 0.53 |
| 5| 1327 | 35.61 | 13.43 | 0.59 |
| 10| 2119 | 48.86 | 20.47 | 0.79 |
| 37| 6176 | 99.46 | 52.70 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.79 | 10.15 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 979 | 38.66 | 12.84 | 0.60 |
| 5| 1261 | 42.57 | 15.26 | 0.66 |
| 10| 2091 | 54.69 | 22.00 | 0.84 |
| 30| 4915 | 98.38 | 47.41 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.16 | 9.13 | 0.69 |
| 2| 5937 | 35.80 | 12.03 | 0.79 |
| 3| 6122 | 45.65 | 15.40 | 0.90 |
| 4| 6309 | 54.63 | 18.40 | 1.00 |
| 5| 6513 | 65.93 | 22.35 | 1.13 |
| 6| 6383 | 64.28 | 21.54 | 1.11 |
| 7| 6673 | 78.05 | 26.25 | 1.26 |
| 8| 6857 | 88.56 | 29.84 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 58 | 5870 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 285 | 6004 | 31.12 | 11.04 | 0.75 |
| 10 | 10 | 568 | 6172 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2220 | 7159 | 98.24 | 37.65 | 1.53 |

