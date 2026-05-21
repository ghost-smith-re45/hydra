--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-21 09:01:47.460232149 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6645 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 42.37 | 12.20 | 0.61 |
| 4 | 228 | 858 | 51.10 | 14.68 | 0.71 |
| 5 | 280 | 969 | 62.56 | 17.82 | 0.83 |
| 6 | 338 | 1081 | 69.82 | 19.95 | 0.91 |
| 7 | 393 | 1192 | 77.61 | 22.43 | 0.99 |
| 8 | 451 | 1303 | 80.67 | 23.48 | 1.03 |
| 9 | 505 | 1414 | 93.75 | 26.86 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 23.92 | 7.60 | 0.48 |
| 2| 1924 | 25.92 | 8.80 | 0.51 |
| 3| 2013 | 25.95 | 9.49 | 0.52 |
| 5| 2373 | 30.88 | 12.19 | 0.59 |
| 10| 3279 | 42.99 | 18.91 | 0.78 |
| 39| 7713 | 99.56 | 53.97 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.84 | 7.38 | 0.41 |
| 2| 830 | 25.57 | 8.80 | 0.46 |
| 3| 937 | 26.13 | 9.61 | 0.47 |
| 5| 1238 | 29.71 | 11.97 | 0.53 |
| 10| 1958 | 39.64 | 18.07 | 0.69 |
| 41| 6644 | 98.66 | 55.11 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 29.13 | 8.90 | 0.48 |
| 2| 839 | 29.26 | 9.62 | 0.49 |
| 3| 923 | 32.72 | 11.23 | 0.54 |
| 5| 1168 | 33.58 | 12.81 | 0.57 |
| 10| 2019 | 44.59 | 19.29 | 0.74 |
| 37| 6194 | 98.78 | 52.51 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 817 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.16 | 12.39 | 0.58 |
| 5| 1330 | 43.28 | 15.47 | 0.67 |
| 10| 1901 | 52.45 | 21.33 | 0.81 |
| 29| 4836 | 96.75 | 46.34 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.05 | 9.07 | 0.69 |
| 2| 6014 | 37.01 | 12.46 | 0.80 |
| 3| 6066 | 44.84 | 15.07 | 0.89 |
| 4| 6278 | 54.38 | 18.38 | 1.00 |
| 5| 6512 | 66.25 | 22.39 | 1.13 |
| 6| 6576 | 73.93 | 24.93 | 1.22 |
| 7| 6744 | 84.73 | 28.61 | 1.34 |
| 8| 6706 | 87.89 | 29.50 | 1.37 |
| 9| 7007 | 97.55 | 32.80 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6856 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2223 | 7162 | 98.49 | 37.73 | 1.53 |

