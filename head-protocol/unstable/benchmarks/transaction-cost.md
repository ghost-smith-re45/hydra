--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-03 04:47:49.063693191 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.76 | 4.67 | 0.58 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 744 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 43.45 | 12.44 | 0.62 |
| 4 | 226 | 858 | 54.12 | 15.43 | 0.74 |
| 5 | 284 | 974 | 57.48 | 16.57 | 0.78 |
| 6 | 341 | 1081 | 68.18 | 19.56 | 0.89 |
| 7 | 393 | 1196 | 86.67 | 24.38 | 1.08 |
| 8 | 450 | 1303 | 88.67 | 25.25 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1994 | 26.42 | 8.96 | 0.52 |
| 3| 2068 | 27.32 | 9.86 | 0.53 |
| 5| 2346 | 29.89 | 11.93 | 0.58 |
| 10| 3177 | 42.12 | 18.66 | 0.76 |
| 41| 7905 | 99.50 | 55.31 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.53 | 7.31 | 0.41 |
| 2| 744 | 24.35 | 8.48 | 0.44 |
| 3| 944 | 26.98 | 9.87 | 0.48 |
| 5| 1158 | 28.16 | 11.51 | 0.51 |
| 10| 2182 | 44.15 | 19.32 | 0.74 |
| 43| 6530 | 94.36 | 55.28 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.51 | 8.47 | 0.46 |
| 2| 799 | 30.94 | 10.07 | 0.51 |
| 3| 911 | 32.80 | 11.25 | 0.54 |
| 5| 1251 | 36.87 | 13.74 | 0.60 |
| 10| 1953 | 44.00 | 19.10 | 0.73 |
| 35| 5865 | 96.75 | 50.58 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.12 | 9.94 | 0.52 |
| 2| 809 | 35.85 | 11.38 | 0.56 |
| 3| 1009 | 38.66 | 12.84 | 0.60 |
| 5| 1379 | 44.07 | 15.71 | 0.68 |
| 10| 2058 | 54.88 | 22.05 | 0.84 |
| 29| 4859 | 98.00 | 46.71 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.00 | 9.06 | 0.69 |
| 2| 5984 | 36.73 | 12.38 | 0.80 |
| 3| 6143 | 46.70 | 15.80 | 0.91 |
| 4| 6167 | 52.63 | 17.70 | 0.97 |
| 5| 6476 | 65.94 | 22.30 | 1.13 |
| 6| 6564 | 72.17 | 24.27 | 1.20 |
| 7| 6836 | 85.72 | 28.91 | 1.35 |
| 8| 6795 | 85.61 | 28.85 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 58.21 | 21.92 | 1.07 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

