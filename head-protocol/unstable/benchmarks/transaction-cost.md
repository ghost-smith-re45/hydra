--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-10 11:47:49.908937651 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.88 | 4.72 | 0.58 |
| 5| 6638 | 18.91 | 5.98 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 42.64 | 12.27 | 0.62 |
| 4 | 227 | 858 | 52.60 | 15.09 | 0.72 |
| 5 | 283 | 969 | 55.98 | 16.24 | 0.76 |
| 6 | 340 | 1081 | 68.01 | 19.52 | 0.89 |
| 7 | 395 | 1192 | 84.54 | 23.95 | 1.06 |
| 8 | 450 | 1303 | 96.27 | 27.12 | 1.18 |
| 9 | 504 | 1414 | 95.16 | 27.38 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1747 | 22.92 | 7.32 | 0.47 |
| 2| 1882 | 24.40 | 8.40 | 0.49 |
| 3| 2080 | 26.90 | 9.76 | 0.53 |
| 5| 2407 | 31.42 | 12.34 | 0.60 |
| 10| 3085 | 39.59 | 17.97 | 0.74 |
| 38| 7314 | 93.92 | 51.75 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.53 | 7.30 | 0.41 |
| 2| 792 | 25.59 | 8.80 | 0.46 |
| 3| 830 | 24.13 | 9.06 | 0.45 |
| 5| 1244 | 30.10 | 12.07 | 0.54 |
| 10| 1958 | 39.73 | 18.08 | 0.69 |
| 41| 6526 | 97.48 | 54.76 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.51 | 8.47 | 0.46 |
| 2| 833 | 31.61 | 10.27 | 0.52 |
| 3| 864 | 31.97 | 11.00 | 0.53 |
| 5| 1282 | 37.73 | 13.99 | 0.61 |
| 10| 2023 | 48.01 | 20.22 | 0.77 |
| 35| 5684 | 94.71 | 49.99 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 33.79 | 10.15 | 0.53 |
| 2| 811 | 35.88 | 11.39 | 0.56 |
| 3| 968 | 37.84 | 12.60 | 0.59 |
| 5| 1351 | 44.11 | 15.72 | 0.68 |
| 10| 2070 | 54.85 | 22.04 | 0.84 |
| 29| 4976 | 99.42 | 47.16 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.05 | 9.08 | 0.69 |
| 2| 5937 | 35.88 | 12.06 | 0.79 |
| 3| 6023 | 41.48 | 13.88 | 0.85 |
| 4| 6188 | 50.50 | 16.95 | 0.95 |
| 5| 6501 | 65.56 | 22.21 | 1.13 |
| 6| 6624 | 74.26 | 25.03 | 1.22 |
| 7| 6642 | 79.86 | 26.93 | 1.28 |
| 8| 6802 | 88.86 | 29.90 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 10 | 569 | 6174 | 37.74 | 13.85 | 0.83 |
| 10 | 20 | 1138 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1705 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7160 | 97.16 | 37.28 | 1.52 |

