--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-24 04:52:12.263153975 UTC |
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
| 1| 5834 | 11.12 | 3.55 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6645 | 18.79 | 5.94 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 751 | 40.27 | 11.70 | 0.59 |
| 4 | 227 | 858 | 54.03 | 15.41 | 0.74 |
| 5 | 281 | 969 | 60.27 | 17.27 | 0.80 |
| 6 | 338 | 1081 | 73.87 | 20.96 | 0.95 |
| 7 | 394 | 1192 | 76.62 | 22.02 | 0.98 |
| 8 | 452 | 1303 | 91.51 | 25.98 | 1.13 |
| 9 | 505 | 1414 | 95.90 | 27.43 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 24.00 | 7.62 | 0.48 |
| 2| 1936 | 25.39 | 8.68 | 0.50 |
| 3| 2101 | 28.51 | 10.19 | 0.55 |
| 5| 2338 | 30.30 | 12.03 | 0.58 |
| 10| 3208 | 41.55 | 18.52 | 0.76 |
| 40| 7751 | 99.26 | 54.58 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.80 | 7.37 | 0.41 |
| 2| 768 | 24.00 | 8.40 | 0.44 |
| 3| 964 | 27.00 | 9.87 | 0.48 |
| 5| 1202 | 29.88 | 12.03 | 0.53 |
| 10| 2001 | 38.28 | 17.68 | 0.68 |
| 43| 6757 | 99.69 | 56.73 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 29.09 | 8.89 | 0.48 |
| 2| 787 | 30.91 | 10.06 | 0.51 |
| 3| 998 | 31.61 | 10.96 | 0.53 |
| 5| 1429 | 36.95 | 13.84 | 0.61 |
| 10| 2059 | 48.27 | 20.29 | 0.78 |
| 36| 5849 | 96.85 | 51.26 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 33.12 | 9.94 | 0.52 |
| 2| 761 | 35.21 | 11.18 | 0.55 |
| 3| 896 | 37.13 | 12.38 | 0.58 |
| 5| 1328 | 43.31 | 15.48 | 0.67 |
| 10| 2121 | 54.88 | 22.07 | 0.85 |
| 29| 4759 | 96.83 | 46.34 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.00 | 9.07 | 0.69 |
| 2| 5925 | 35.96 | 12.09 | 0.79 |
| 3| 6132 | 45.82 | 15.45 | 0.90 |
| 4| 6214 | 53.95 | 18.13 | 0.99 |
| 5| 6433 | 61.45 | 20.69 | 1.08 |
| 6| 6371 | 65.20 | 21.82 | 1.11 |
| 7| 6597 | 79.23 | 26.57 | 1.27 |
| 8| 6975 | 91.43 | 30.83 | 1.42 |
| 9| 6964 | 97.88 | 32.91 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6854 | 79.78 | 30.37 | 1.32 |
| 10 | 38 | 2160 | 7122 | 96.44 | 36.92 | 1.51 |

