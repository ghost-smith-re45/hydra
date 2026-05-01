--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-01 07:53:20.4216621 UTC |
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
| 1| 5841 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.69 | 4.65 | 0.58 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 171 | 747 | 41.29 | 11.92 | 0.60 |
| 4 | 227 | 858 | 51.17 | 14.70 | 0.71 |
| 5 | 282 | 969 | 59.47 | 17.11 | 0.80 |
| 6 | 341 | 1081 | 73.84 | 20.95 | 0.95 |
| 7 | 395 | 1192 | 72.96 | 21.27 | 0.95 |
| 8 | 449 | 1303 | 92.04 | 26.11 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1925 | 25.51 | 8.70 | 0.50 |
| 3| 2067 | 27.23 | 9.84 | 0.53 |
| 5| 2275 | 28.97 | 11.67 | 0.57 |
| 10| 3096 | 40.00 | 18.07 | 0.74 |
| 40| 7636 | 99.94 | 54.72 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.81 | 7.37 | 0.42 |
| 2| 778 | 24.25 | 8.44 | 0.44 |
| 3| 830 | 24.02 | 9.03 | 0.45 |
| 5| 1244 | 31.37 | 12.43 | 0.55 |
| 10| 2037 | 41.46 | 18.56 | 0.71 |
| 42| 6808 | 99.87 | 56.16 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.17 | 8.91 | 0.48 |
| 2| 779 | 30.87 | 10.05 | 0.51 |
| 3| 986 | 31.69 | 10.98 | 0.53 |
| 5| 1202 | 34.41 | 13.05 | 0.58 |
| 10| 2158 | 46.33 | 19.80 | 0.76 |
| 36| 5960 | 95.81 | 50.98 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 711 | 33.87 | 10.16 | 0.53 |
| 2| 862 | 36.56 | 11.60 | 0.57 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1316 | 43.20 | 15.45 | 0.67 |
| 10| 2112 | 54.70 | 22.01 | 0.84 |
| 29| 4751 | 96.50 | 46.24 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5800 | 27.09 | 9.09 | 0.69 |
| 2| 5882 | 32.52 | 10.88 | 0.75 |
| 3| 6085 | 44.41 | 14.95 | 0.88 |
| 4| 6294 | 54.85 | 18.47 | 1.00 |
| 5| 6481 | 64.70 | 21.88 | 1.12 |
| 6| 6600 | 70.81 | 23.83 | 1.18 |
| 7| 6731 | 82.10 | 27.69 | 1.31 |
| 8| 6904 | 90.20 | 30.36 | 1.40 |
| 9| 7029 | 94.37 | 31.76 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 39 | 2219 | 7159 | 99.38 | 38.04 | 1.54 |

