--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-08 07:47:44.929487 UTC |
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
| 1| 5837 | 10.67 | 3.39 | 0.52 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6242 | 14.50 | 4.58 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7648 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 40.38 | 11.75 | 0.59 |
| 4 | 226 | 858 | 52.32 | 14.95 | 0.72 |
| 5 | 282 | 969 | 62.31 | 17.76 | 0.82 |
| 6 | 336 | 1085 | 68.22 | 19.65 | 0.89 |
| 7 | 394 | 1192 | 84.54 | 23.87 | 1.06 |
| 8 | 451 | 1303 | 80.42 | 23.28 | 1.03 |
| 9 | 504 | 1418 | 97.18 | 27.91 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.37 | 7.71 | 0.48 |
| 2| 1935 | 25.43 | 8.68 | 0.50 |
| 3| 2071 | 27.02 | 9.79 | 0.53 |
| 5| 2380 | 30.96 | 12.23 | 0.59 |
| 10| 3102 | 40.76 | 18.29 | 0.75 |
| 40| 7595 | 97.74 | 54.14 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 22.81 | 7.37 | 0.42 |
| 2| 733 | 23.58 | 8.23 | 0.43 |
| 3| 1004 | 28.10 | 10.19 | 0.50 |
| 5| 1244 | 29.98 | 12.04 | 0.53 |
| 10| 1915 | 36.79 | 17.26 | 0.66 |
| 40| 6672 | 99.58 | 54.75 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 841 | 31.62 | 10.27 | 0.52 |
| 3| 993 | 31.58 | 10.95 | 0.53 |
| 5| 1247 | 34.66 | 13.13 | 0.58 |
| 10| 1958 | 44.23 | 19.16 | 0.73 |
| 36| 5963 | 96.81 | 51.27 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 760 | 35.14 | 11.16 | 0.55 |
| 3| 1012 | 38.51 | 12.80 | 0.60 |
| 5| 1154 | 41.18 | 14.84 | 0.64 |
| 10| 2118 | 55.48 | 22.24 | 0.85 |
| 28| 4777 | 95.75 | 45.43 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 26.96 | 9.05 | 0.69 |
| 2| 5947 | 35.88 | 12.07 | 0.79 |
| 3| 6120 | 46.07 | 15.52 | 0.90 |
| 4| 6265 | 54.94 | 18.48 | 1.00 |
| 5| 6390 | 63.85 | 21.50 | 1.10 |
| 6| 6430 | 66.45 | 22.28 | 1.13 |
| 7| 6654 | 78.29 | 26.32 | 1.27 |
| 8| 6846 | 89.02 | 30.04 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7158 | 99.31 | 38.01 | 1.54 |

