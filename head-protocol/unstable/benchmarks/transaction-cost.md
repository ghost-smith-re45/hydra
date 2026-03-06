--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-06 06:31:37.404299506 UTC |
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
| 1| 5834 | 11.04 | 3.52 | 0.52 |
| 2| 6038 | 13.01 | 4.14 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6646 | 18.81 | 5.94 | 0.64 |
| 10| 7644 | 28.90 | 9.10 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 40.01 | 11.63 | 0.59 |
| 4 | 225 | 858 | 50.73 | 14.57 | 0.70 |
| 5 | 280 | 969 | 63.50 | 18.01 | 0.84 |
| 6 | 339 | 1081 | 75.76 | 21.45 | 0.96 |
| 7 | 393 | 1192 | 76.55 | 22.00 | 0.98 |
| 8 | 451 | 1303 | 96.56 | 27.19 | 1.18 |
| 10 | 561 | 1529 | 99.55 | 28.65 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.29 | 7.69 | 0.48 |
| 2| 1918 | 25.85 | 8.78 | 0.51 |
| 3| 2073 | 27.24 | 9.84 | 0.53 |
| 5| 2322 | 30.00 | 11.96 | 0.58 |
| 10| 3279 | 42.94 | 18.90 | 0.78 |
| 39| 7734 | 99.93 | 54.10 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 742 | 23.65 | 8.25 | 0.43 |
| 3| 899 | 25.07 | 9.31 | 0.46 |
| 5| 1293 | 30.98 | 12.32 | 0.55 |
| 10| 1987 | 39.64 | 18.07 | 0.69 |
| 42| 6870 | 99.20 | 56.00 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.94 | 10.07 | 0.51 |
| 3| 940 | 32.72 | 11.23 | 0.54 |
| 5| 1247 | 36.95 | 13.76 | 0.60 |
| 10| 1985 | 47.33 | 20.01 | 0.76 |
| 35| 5688 | 99.68 | 51.30 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 982 | 38.59 | 12.82 | 0.60 |
| 5| 1261 | 42.64 | 15.28 | 0.66 |
| 10| 2192 | 55.60 | 22.27 | 0.86 |
| 30| 4959 | 99.55 | 47.76 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.00 | 9.08 | 0.69 |
| 2| 5882 | 32.49 | 10.87 | 0.75 |
| 3| 6064 | 43.83 | 14.68 | 0.88 |
| 4| 6141 | 52.81 | 17.69 | 0.97 |
| 5| 6452 | 65.24 | 21.98 | 1.12 |
| 6| 6657 | 74.51 | 25.13 | 1.23 |
| 7| 6677 | 79.04 | 26.56 | 1.27 |
| 8| 6751 | 86.97 | 29.18 | 1.36 |
| 10| 6750 | 90.35 | 30.09 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1709 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2164 | 7127 | 97.33 | 37.23 | 1.52 |

