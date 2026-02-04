--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-04 05:23:57.003782542 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 13.10 | 4.17 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.90 | 9.10 | 0.79 |
| 43| 14279 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 43.81 | 12.53 | 0.63 |
| 4 | 226 | 858 | 52.43 | 14.98 | 0.72 |
| 5 | 282 | 969 | 61.02 | 17.42 | 0.81 |
| 6 | 339 | 1085 | 68.58 | 19.77 | 0.89 |
| 7 | 395 | 1192 | 78.41 | 22.44 | 1.00 |
| 8 | 450 | 1303 | 96.76 | 27.29 | 1.19 |
| 9 | 504 | 1414 | 88.41 | 25.58 | 1.11 |
| 10 | 560 | 1525 | 97.89 | 28.32 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1953 | 25.47 | 8.70 | 0.50 |
| 3| 2014 | 26.36 | 9.59 | 0.52 |
| 5| 2383 | 30.80 | 12.19 | 0.59 |
| 10| 3044 | 39.07 | 17.81 | 0.73 |
| 40| 7567 | 99.58 | 54.60 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.77 | 7.36 | 0.42 |
| 2| 764 | 23.59 | 8.23 | 0.43 |
| 3| 875 | 25.85 | 9.56 | 0.47 |
| 5| 1179 | 29.18 | 11.81 | 0.52 |
| 10| 2026 | 40.20 | 18.24 | 0.70 |
| 40| 6442 | 96.62 | 53.92 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.47 | 8.46 | 0.46 |
| 2| 796 | 30.98 | 10.08 | 0.51 |
| 3| 984 | 31.61 | 10.96 | 0.53 |
| 5| 1372 | 38.56 | 14.24 | 0.62 |
| 10| 2024 | 44.93 | 19.37 | 0.74 |
| 36| 6070 | 98.86 | 51.86 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.79 | 10.15 | 0.53 |
| 2| 824 | 35.85 | 11.38 | 0.56 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1198 | 41.90 | 15.05 | 0.65 |
| 10| 1972 | 53.42 | 21.61 | 0.82 |
| 28| 4837 | 96.98 | 45.77 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5783 | 27.13 | 9.11 | 0.69 |
| 2| 5973 | 35.91 | 12.07 | 0.79 |
| 3| 6180 | 45.86 | 15.44 | 0.90 |
| 4| 6271 | 55.03 | 18.49 | 1.00 |
| 5| 6263 | 55.74 | 18.60 | 1.01 |
| 6| 6639 | 74.66 | 25.22 | 1.23 |
| 7| 6569 | 76.55 | 25.72 | 1.24 |
| 8| 6698 | 85.70 | 28.78 | 1.34 |
| 9| 7007 | 99.00 | 33.26 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 568 | 6172 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2216 | 7155 | 99.12 | 37.95 | 1.54 |

