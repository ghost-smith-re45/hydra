--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-12 09:33:28.868082659 UTC |
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
| 1| 5836 | 10.95 | 3.49 | 0.52 |
| 2| 6037 | 12.80 | 4.07 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7648 | 28.81 | 9.07 | 0.79 |
| 43| 14285 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2166 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 43.75 | 12.51 | 0.63 |
| 4 | 226 | 858 | 51.27 | 14.75 | 0.71 |
| 5 | 282 | 969 | 60.87 | 17.44 | 0.81 |
| 6 | 339 | 1081 | 73.03 | 20.72 | 0.94 |
| 7 | 393 | 1192 | 84.80 | 23.98 | 1.06 |
| 8 | 450 | 1303 | 94.76 | 26.86 | 1.17 |
| 9 | 504 | 1414 | 88.69 | 25.70 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1922 | 25.39 | 8.68 | 0.50 |
| 3| 2069 | 26.94 | 9.77 | 0.53 |
| 5| 2363 | 31.16 | 12.28 | 0.59 |
| 10| 3115 | 40.74 | 18.29 | 0.75 |
| 42| 7800 | 99.50 | 55.96 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 22.57 | 7.31 | 0.41 |
| 2| 744 | 24.31 | 8.47 | 0.44 |
| 3| 903 | 25.14 | 9.33 | 0.46 |
| 5| 1201 | 30.02 | 12.04 | 0.53 |
| 10| 1988 | 38.86 | 17.84 | 0.68 |
| 41| 6474 | 94.85 | 54.08 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.17 | 8.91 | 0.48 |
| 2| 803 | 30.95 | 10.07 | 0.51 |
| 3| 958 | 30.98 | 10.76 | 0.52 |
| 5| 1219 | 37.10 | 13.79 | 0.60 |
| 10| 1969 | 46.69 | 19.82 | 0.76 |
| 36| 5717 | 99.21 | 51.81 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.88 | 11.39 | 0.56 |
| 3| 994 | 38.55 | 12.81 | 0.60 |
| 5| 1210 | 41.89 | 15.05 | 0.65 |
| 10| 2060 | 54.77 | 22.02 | 0.84 |
| 29| 4884 | 97.95 | 46.70 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.09 | 9.09 | 0.69 |
| 2| 5974 | 36.97 | 12.44 | 0.80 |
| 3| 6114 | 46.03 | 15.49 | 0.90 |
| 4| 6330 | 55.76 | 18.86 | 1.02 |
| 5| 6406 | 64.06 | 21.63 | 1.11 |
| 6| 6577 | 74.98 | 25.35 | 1.23 |
| 7| 6631 | 76.33 | 25.65 | 1.24 |
| 8| 6927 | 93.93 | 31.78 | 1.44 |
| 9| 6936 | 94.51 | 31.73 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 40 | 2279 | 7195 | 99.84 | 38.30 | 1.55 |

