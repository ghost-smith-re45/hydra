--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-26 07:49:12.708874457 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 19.36 | 6.14 | 0.64 |
| 10| 7644 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 40.21 | 11.69 | 0.59 |
| 4 | 228 | 858 | 50.54 | 14.57 | 0.70 |
| 5 | 283 | 969 | 63.15 | 18.00 | 0.83 |
| 6 | 337 | 1081 | 66.42 | 19.17 | 0.87 |
| 7 | 396 | 1192 | 86.68 | 24.43 | 1.08 |
| 8 | 450 | 1303 | 91.40 | 26.00 | 1.13 |
| 10 | 560 | 1529 | 96.61 | 27.94 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1941 | 25.47 | 8.70 | 0.50 |
| 3| 2185 | 28.96 | 10.34 | 0.56 |
| 5| 2464 | 32.94 | 12.79 | 0.62 |
| 10| 3253 | 42.31 | 18.75 | 0.77 |
| 41| 7553 | 95.01 | 54.04 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.50 | 7.30 | 0.41 |
| 2| 693 | 22.62 | 7.95 | 0.42 |
| 3| 895 | 24.99 | 9.29 | 0.46 |
| 5| 1134 | 28.69 | 11.67 | 0.52 |
| 10| 1989 | 38.70 | 17.79 | 0.68 |
| 40| 6516 | 97.96 | 54.28 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.51 | 8.47 | 0.46 |
| 2| 813 | 29.15 | 9.59 | 0.49 |
| 3| 952 | 33.47 | 11.45 | 0.55 |
| 5| 1248 | 35.12 | 13.27 | 0.58 |
| 10| 2040 | 45.13 | 19.42 | 0.74 |
| 35| 6077 | 98.64 | 51.20 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.83 | 10.16 | 0.53 |
| 2| 867 | 36.48 | 11.58 | 0.57 |
| 3| 937 | 37.91 | 12.62 | 0.59 |
| 5| 1312 | 43.27 | 15.47 | 0.67 |
| 10| 2195 | 56.48 | 22.57 | 0.87 |
| 30| 4946 | 98.92 | 47.60 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 27.08 | 9.08 | 0.69 |
| 2| 5915 | 35.80 | 12.01 | 0.79 |
| 3| 6046 | 41.45 | 13.88 | 0.85 |
| 4| 6094 | 49.34 | 16.51 | 0.94 |
| 5| 6554 | 66.29 | 22.41 | 1.14 |
| 6| 6731 | 74.99 | 25.36 | 1.24 |
| 7| 6660 | 78.98 | 26.67 | 1.27 |
| 8| 6862 | 89.42 | 30.26 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 81.11 | 30.83 | 1.33 |
| 10 | 38 | 2165 | 7127 | 96.44 | 36.92 | 1.51 |

