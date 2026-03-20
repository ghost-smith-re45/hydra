--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-20 06:32:34.403953597 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.60 | 12.24 | 0.62 |
| 4 | 226 | 858 | 53.76 | 15.32 | 0.73 |
| 5 | 282 | 974 | 59.45 | 17.10 | 0.80 |
| 6 | 339 | 1081 | 74.33 | 21.18 | 0.95 |
| 7 | 395 | 1192 | 86.29 | 24.29 | 1.07 |
| 8 | 449 | 1307 | 92.05 | 26.12 | 1.14 |
| 9 | 505 | 1414 | 94.22 | 27.03 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.37 | 7.71 | 0.48 |
| 2| 1925 | 25.84 | 8.78 | 0.51 |
| 3| 2132 | 28.06 | 10.08 | 0.54 |
| 5| 2273 | 28.82 | 11.63 | 0.57 |
| 10| 3225 | 41.46 | 18.50 | 0.76 |
| 41| 7660 | 98.17 | 54.92 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.50 | 7.29 | 0.41 |
| 2| 837 | 25.13 | 8.70 | 0.45 |
| 3| 923 | 25.52 | 9.48 | 0.47 |
| 5| 1259 | 30.70 | 12.24 | 0.54 |
| 10| 1932 | 37.38 | 17.42 | 0.66 |
| 40| 6598 | 98.77 | 54.54 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.09 | 8.89 | 0.48 |
| 2| 832 | 29.18 | 9.60 | 0.49 |
| 3| 1006 | 31.57 | 10.95 | 0.53 |
| 5| 1293 | 37.91 | 14.05 | 0.61 |
| 10| 2046 | 44.83 | 19.35 | 0.74 |
| 36| 5566 | 97.24 | 51.22 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.83 | 10.16 | 0.53 |
| 2| 807 | 35.89 | 11.39 | 0.56 |
| 3| 994 | 38.51 | 12.80 | 0.60 |
| 5| 1292 | 42.53 | 15.25 | 0.66 |
| 10| 1970 | 53.49 | 21.63 | 0.83 |
| 29| 4859 | 97.40 | 46.54 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 27.13 | 9.09 | 0.69 |
| 2| 5937 | 35.87 | 12.06 | 0.79 |
| 3| 6040 | 44.73 | 15.04 | 0.89 |
| 4| 6153 | 50.25 | 16.85 | 0.95 |
| 5| 6382 | 59.92 | 20.21 | 1.06 |
| 6| 6620 | 75.20 | 25.40 | 1.23 |
| 7| 6654 | 78.68 | 26.40 | 1.27 |
| 8| 6786 | 87.06 | 29.27 | 1.36 |
| 9| 6851 | 96.91 | 32.55 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.68 | 6.24 | 0.60 |
| 10 | 5 | 284 | 6003 | 28.21 | 10.04 | 0.71 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2165 | 7127 | 96.88 | 37.08 | 1.51 |

