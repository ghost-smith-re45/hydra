--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-20 04:39:13.495603844 UTC |
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
| 1| 5841 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6242 | 14.69 | 4.65 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.49 | 31.12 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 42.35 | 12.18 | 0.61 |
| 4 | 227 | 858 | 47.93 | 13.90 | 0.68 |
| 5 | 282 | 969 | 63.04 | 17.97 | 0.83 |
| 6 | 340 | 1085 | 70.01 | 20.04 | 0.91 |
| 7 | 393 | 1196 | 75.63 | 21.77 | 0.97 |
| 8 | 451 | 1303 | 96.45 | 27.16 | 1.18 |
| 9 | 506 | 1414 | 93.45 | 26.73 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1931 | 25.43 | 8.68 | 0.50 |
| 3| 2069 | 27.43 | 9.89 | 0.53 |
| 5| 2553 | 34.32 | 13.16 | 0.63 |
| 10| 3024 | 38.78 | 17.73 | 0.72 |
| 38| 7405 | 96.60 | 52.46 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.77 | 7.36 | 0.42 |
| 2| 755 | 24.27 | 8.45 | 0.44 |
| 3| 959 | 26.68 | 9.79 | 0.48 |
| 5| 1172 | 28.08 | 11.49 | 0.51 |
| 10| 2096 | 40.72 | 18.36 | 0.70 |
| 41| 6578 | 99.47 | 55.32 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 712 | 27.51 | 8.47 | 0.46 |
| 2| 823 | 29.19 | 9.60 | 0.49 |
| 3| 1022 | 31.69 | 10.98 | 0.53 |
| 5| 1403 | 36.47 | 13.68 | 0.61 |
| 10| 2132 | 46.44 | 19.83 | 0.76 |
| 35| 6042 | 98.14 | 51.04 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.83 | 10.16 | 0.53 |
| 2| 806 | 35.92 | 11.40 | 0.56 |
| 3| 1011 | 38.66 | 12.84 | 0.60 |
| 5| 1217 | 41.82 | 15.03 | 0.65 |
| 10| 2213 | 56.12 | 22.44 | 0.86 |
| 29| 4850 | 97.53 | 46.53 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 26.97 | 9.05 | 0.69 |
| 2| 6017 | 36.98 | 12.45 | 0.80 |
| 3| 6135 | 45.97 | 15.50 | 0.90 |
| 4| 6295 | 52.15 | 17.56 | 0.98 |
| 5| 6239 | 58.74 | 19.62 | 1.04 |
| 6| 6478 | 68.76 | 23.05 | 1.16 |
| 7| 6517 | 78.16 | 26.23 | 1.26 |
| 8| 6904 | 90.14 | 30.35 | 1.40 |
| 9| 6881 | 93.80 | 31.49 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 29.28 | 10.41 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 40 | 2279 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

