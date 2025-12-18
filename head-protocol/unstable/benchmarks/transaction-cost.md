--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-18 04:50:00.05724334 UTC |
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
| 1| 5837 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6243 | 14.50 | 4.58 | 0.58 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7648 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.38 | 9.43 | 0.51 |
| 3 | 169 | 747 | 42.22 | 12.14 | 0.61 |
| 4 | 227 | 858 | 51.32 | 14.76 | 0.71 |
| 5 | 282 | 969 | 59.79 | 17.22 | 0.80 |
| 6 | 339 | 1081 | 73.18 | 20.72 | 0.94 |
| 7 | 397 | 1192 | 82.01 | 23.26 | 1.03 |
| 8 | 449 | 1303 | 96.63 | 27.26 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1925 | 25.92 | 8.80 | 0.51 |
| 3| 2128 | 28.02 | 10.07 | 0.54 |
| 5| 2386 | 30.97 | 12.23 | 0.59 |
| 10| 3161 | 40.94 | 18.34 | 0.75 |
| 41| 7785 | 99.96 | 55.40 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.84 | 7.39 | 0.42 |
| 2| 753 | 24.04 | 8.39 | 0.44 |
| 3| 834 | 24.13 | 9.06 | 0.45 |
| 5| 1230 | 28.93 | 11.73 | 0.52 |
| 10| 2192 | 44.50 | 19.40 | 0.75 |
| 43| 6623 | 94.11 | 55.20 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 949 | 30.98 | 10.76 | 0.52 |
| 5| 1320 | 38.45 | 14.21 | 0.62 |
| 10| 2048 | 44.76 | 19.33 | 0.74 |
| 36| 6027 | 98.23 | 51.70 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 33.87 | 10.16 | 0.53 |
| 2| 802 | 35.92 | 11.40 | 0.56 |
| 3| 941 | 37.84 | 12.60 | 0.59 |
| 5| 1281 | 42.79 | 15.33 | 0.66 |
| 10| 2043 | 53.95 | 21.78 | 0.83 |
| 29| 4874 | 98.61 | 46.90 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 27.05 | 9.07 | 0.69 |
| 2| 5893 | 34.98 | 11.71 | 0.78 |
| 3| 5990 | 41.29 | 13.81 | 0.85 |
| 4| 6303 | 55.04 | 18.56 | 1.01 |
| 5| 6241 | 58.72 | 19.65 | 1.04 |
| 6| 6604 | 74.28 | 24.98 | 1.22 |
| 7| 6663 | 81.15 | 27.27 | 1.30 |
| 8| 6783 | 89.74 | 30.17 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

