--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-05 07:05:24.616563605 UTC |
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
| 1| 5841 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7648 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 41.12 | 11.88 | 0.60 |
| 4 | 226 | 858 | 51.13 | 14.69 | 0.71 |
| 5 | 283 | 969 | 57.79 | 16.68 | 0.78 |
| 6 | 337 | 1081 | 68.74 | 19.77 | 0.90 |
| 7 | 394 | 1192 | 84.64 | 23.94 | 1.06 |
| 8 | 449 | 1303 | 91.93 | 26.08 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1752 | 23.30 | 7.41 | 0.47 |
| 2| 1978 | 26.84 | 9.06 | 0.52 |
| 3| 2115 | 28.13 | 10.10 | 0.54 |
| 5| 2372 | 31.04 | 12.25 | 0.59 |
| 10| 3053 | 38.88 | 17.76 | 0.73 |
| 39| 7364 | 94.81 | 52.65 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 611 | 22.84 | 7.37 | 0.41 |
| 2| 754 | 23.65 | 8.25 | 0.43 |
| 3| 893 | 25.55 | 9.46 | 0.46 |
| 5| 1267 | 30.86 | 12.29 | 0.54 |
| 10| 1870 | 36.97 | 17.31 | 0.66 |
| 43| 6635 | 97.62 | 56.15 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 29.17 | 8.91 | 0.48 |
| 2| 770 | 30.94 | 10.07 | 0.51 |
| 3| 951 | 30.90 | 10.74 | 0.52 |
| 5| 1263 | 34.97 | 13.23 | 0.58 |
| 10| 1984 | 44.37 | 19.20 | 0.73 |
| 36| 6075 | 98.58 | 51.81 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 943 | 37.91 | 12.62 | 0.59 |
| 5| 1361 | 43.99 | 15.69 | 0.68 |
| 10| 2036 | 54.01 | 21.80 | 0.83 |
| 29| 4879 | 98.57 | 46.85 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5844 | 27.00 | 9.07 | 0.69 |
| 2| 5845 | 31.48 | 10.47 | 0.74 |
| 3| 5998 | 41.29 | 13.82 | 0.85 |
| 4| 6163 | 50.44 | 16.89 | 0.95 |
| 5| 6214 | 56.00 | 18.70 | 1.01 |
| 6| 6600 | 71.84 | 24.27 | 1.20 |
| 7| 6546 | 78.10 | 26.18 | 1.26 |
| 8| 6970 | 94.55 | 31.97 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6511 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2217 | 7156 | 98.93 | 37.88 | 1.54 |

