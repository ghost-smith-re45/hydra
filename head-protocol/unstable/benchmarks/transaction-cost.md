--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-17 04:42:37.876676109 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 39.92 | 11.61 | 0.59 |
| 4 | 227 | 858 | 48.07 | 13.96 | 0.68 |
| 5 | 283 | 969 | 62.46 | 17.79 | 0.83 |
| 6 | 339 | 1081 | 66.15 | 19.11 | 0.87 |
| 7 | 394 | 1192 | 86.63 | 24.37 | 1.08 |
| 8 | 449 | 1303 | 92.35 | 26.24 | 1.14 |
| 9 | 505 | 1414 | 90.84 | 26.16 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 23.92 | 7.60 | 0.48 |
| 2| 1967 | 26.58 | 9.01 | 0.52 |
| 3| 2113 | 28.42 | 10.17 | 0.55 |
| 5| 2388 | 30.99 | 12.24 | 0.59 |
| 10| 3241 | 42.63 | 18.82 | 0.77 |
| 44| 7944 | 99.95 | 57.40 | 1.72 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.50 | 7.29 | 0.41 |
| 2| 802 | 25.36 | 8.75 | 0.45 |
| 3| 854 | 24.11 | 9.04 | 0.45 |
| 5| 1294 | 30.95 | 12.30 | 0.55 |
| 10| 1961 | 38.72 | 17.81 | 0.68 |
| 43| 6759 | 99.17 | 56.59 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.13 | 8.90 | 0.48 |
| 2| 817 | 29.18 | 9.60 | 0.49 |
| 3| 925 | 32.65 | 11.21 | 0.54 |
| 5| 1310 | 35.64 | 13.44 | 0.59 |
| 10| 2037 | 45.12 | 19.44 | 0.74 |
| 36| 5882 | 95.90 | 51.00 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 33.83 | 10.16 | 0.53 |
| 2| 848 | 36.56 | 11.60 | 0.57 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1272 | 42.72 | 15.30 | 0.66 |
| 10| 1976 | 53.31 | 21.58 | 0.82 |
| 29| 5050 | 99.60 | 47.22 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.09 | 9.08 | 0.69 |
| 2| 5937 | 36.00 | 12.10 | 0.79 |
| 3| 6153 | 45.81 | 15.44 | 0.90 |
| 4| 6239 | 54.78 | 18.48 | 1.00 |
| 5| 6468 | 63.73 | 21.49 | 1.10 |
| 6| 6470 | 69.82 | 23.47 | 1.17 |
| 7| 6757 | 81.10 | 27.28 | 1.30 |
| 8| 6880 | 86.98 | 29.26 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2162 | 7124 | 97.33 | 37.23 | 1.52 |

