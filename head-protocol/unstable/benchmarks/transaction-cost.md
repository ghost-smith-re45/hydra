--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-22 04:38:23.089687858 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6236 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14286 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 751 | 42.55 | 12.23 | 0.62 |
| 4 | 227 | 858 | 51.15 | 14.70 | 0.71 |
| 5 | 282 | 969 | 62.30 | 17.72 | 0.82 |
| 6 | 339 | 1081 | 64.03 | 18.60 | 0.85 |
| 7 | 393 | 1192 | 79.17 | 22.67 | 1.01 |
| 8 | 452 | 1307 | 81.47 | 23.73 | 1.04 |
| 9 | 504 | 1414 | 94.04 | 26.99 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.77 | 8.48 | 0.49 |
| 3| 2124 | 28.17 | 10.11 | 0.54 |
| 5| 2420 | 32.33 | 12.60 | 0.61 |
| 10| 3240 | 42.58 | 18.81 | 0.77 |
| 38| 7421 | 95.61 | 52.22 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 622 | 22.84 | 7.38 | 0.42 |
| 2| 755 | 24.00 | 8.37 | 0.44 |
| 3| 943 | 26.97 | 9.86 | 0.48 |
| 5| 1092 | 27.00 | 11.20 | 0.50 |
| 10| 1946 | 37.81 | 17.55 | 0.67 |
| 41| 6704 | 99.70 | 55.45 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.54 | 8.47 | 0.46 |
| 2| 833 | 29.19 | 9.60 | 0.49 |
| 3| 953 | 30.90 | 10.74 | 0.52 |
| 5| 1227 | 36.87 | 13.74 | 0.60 |
| 10| 2002 | 44.52 | 19.25 | 0.74 |
| 35| 5873 | 95.96 | 50.43 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 822 | 35.92 | 11.40 | 0.56 |
| 3| 997 | 38.63 | 12.83 | 0.60 |
| 5| 1342 | 43.99 | 15.69 | 0.68 |
| 10| 2010 | 54.02 | 21.80 | 0.83 |
| 29| 4923 | 97.96 | 46.70 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.93 | 7.56 | 0.64 |
| 2| 5982 | 37.13 | 12.49 | 0.80 |
| 3| 5994 | 43.60 | 14.62 | 0.87 |
| 4| 6175 | 53.70 | 18.08 | 0.99 |
| 5| 6457 | 63.95 | 21.50 | 1.11 |
| 6| 6664 | 75.24 | 25.40 | 1.23 |
| 7| 6658 | 79.49 | 26.68 | 1.28 |
| 8| 6752 | 92.75 | 31.25 | 1.42 |
| 9| 6931 | 97.25 | 32.67 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 56 | 5867 | 21.66 | 7.36 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

