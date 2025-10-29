--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-29 04:41:42.40527479 UTC |
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
| 1| 5836 | 10.26 | 3.25 | 0.51 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 15.05 | 4.78 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 169 | 751 | 41.40 | 11.97 | 0.60 |
| 4 | 227 | 858 | 48.38 | 14.06 | 0.68 |
| 5 | 283 | 969 | 64.09 | 18.15 | 0.84 |
| 6 | 338 | 1081 | 74.72 | 21.08 | 0.95 |
| 7 | 397 | 1192 | 79.72 | 22.75 | 1.01 |
| 8 | 448 | 1303 | 95.55 | 26.85 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1969 | 26.92 | 9.08 | 0.52 |
| 3| 2013 | 26.32 | 9.58 | 0.52 |
| 5| 2440 | 32.57 | 12.66 | 0.61 |
| 10| 3173 | 42.30 | 18.71 | 0.77 |
| 39| 7551 | 98.66 | 53.72 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 22.50 | 7.30 | 0.41 |
| 2| 835 | 25.57 | 8.81 | 0.46 |
| 3| 969 | 26.57 | 9.76 | 0.48 |
| 5| 1284 | 30.15 | 12.07 | 0.54 |
| 10| 2078 | 41.94 | 18.71 | 0.72 |
| 42| 6636 | 97.42 | 55.44 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 29.13 | 8.90 | 0.48 |
| 2| 821 | 29.22 | 9.61 | 0.49 |
| 3| 1011 | 31.62 | 10.96 | 0.53 |
| 5| 1259 | 36.95 | 13.76 | 0.60 |
| 10| 1942 | 46.65 | 19.81 | 0.76 |
| 35| 6044 | 97.13 | 50.79 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.79 | 10.15 | 0.53 |
| 2| 821 | 35.88 | 11.39 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1200 | 42.01 | 15.08 | 0.65 |
| 10| 1984 | 53.34 | 21.59 | 0.82 |
| 28| 4879 | 98.03 | 46.13 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 26.92 | 9.04 | 0.69 |
| 2| 5961 | 37.00 | 12.48 | 0.80 |
| 3| 5993 | 43.76 | 14.68 | 0.87 |
| 4| 6285 | 54.93 | 18.54 | 1.00 |
| 5| 6408 | 63.62 | 21.43 | 1.10 |
| 6| 6552 | 74.17 | 24.99 | 1.22 |
| 7| 6726 | 83.42 | 28.12 | 1.32 |
| 8| 6995 | 94.98 | 32.09 | 1.46 |
| 9| 7011 | 99.38 | 33.48 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1136 | 6510 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1705 | 6851 | 80.04 | 30.46 | 1.32 |
| 10 | 36 | 2052 | 7060 | 92.34 | 35.31 | 1.46 |

