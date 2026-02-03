--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-03 05:31:13.892761614 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.73 | 4.04 | 0.55 |
| 3| 6243 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 751 | 40.21 | 11.69 | 0.59 |
| 4 | 227 | 858 | 51.01 | 14.66 | 0.71 |
| 5 | 282 | 969 | 62.93 | 17.97 | 0.83 |
| 6 | 337 | 1081 | 64.80 | 18.79 | 0.86 |
| 7 | 395 | 1192 | 80.68 | 22.95 | 1.02 |
| 8 | 450 | 1303 | 89.59 | 25.57 | 1.12 |
| 9 | 506 | 1414 | 92.17 | 26.60 | 1.15 |
| 10 | 561 | 1525 | 97.23 | 28.15 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.37 | 7.71 | 0.48 |
| 2| 1999 | 26.76 | 9.04 | 0.52 |
| 3| 2171 | 28.89 | 10.32 | 0.55 |
| 5| 2551 | 34.22 | 13.14 | 0.63 |
| 10| 3167 | 40.97 | 18.34 | 0.75 |
| 40| 7641 | 99.16 | 54.52 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 764 | 23.63 | 8.24 | 0.43 |
| 3| 930 | 27.10 | 9.91 | 0.48 |
| 5| 1278 | 32.46 | 12.72 | 0.56 |
| 10| 1873 | 37.32 | 17.44 | 0.66 |
| 41| 6656 | 99.19 | 55.29 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 27.50 | 8.46 | 0.46 |
| 2| 823 | 29.19 | 9.60 | 0.49 |
| 3| 948 | 30.94 | 10.75 | 0.52 |
| 5| 1238 | 34.30 | 13.02 | 0.58 |
| 10| 2051 | 48.26 | 20.28 | 0.78 |
| 36| 6023 | 98.76 | 51.84 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.83 | 10.15 | 0.53 |
| 2| 875 | 36.48 | 11.58 | 0.57 |
| 3| 991 | 38.51 | 12.80 | 0.60 |
| 5| 1205 | 42.01 | 15.08 | 0.65 |
| 10| 2021 | 54.13 | 21.82 | 0.83 |
| 29| 4884 | 98.05 | 46.72 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.09 | 9.09 | 0.69 |
| 2| 6023 | 36.76 | 12.41 | 0.80 |
| 3| 6102 | 45.00 | 15.13 | 0.89 |
| 4| 6255 | 55.02 | 18.55 | 1.00 |
| 5| 6317 | 59.90 | 20.09 | 1.06 |
| 6| 6533 | 69.48 | 23.38 | 1.17 |
| 7| 6769 | 80.35 | 27.09 | 1.29 |
| 8| 6800 | 89.53 | 30.10 | 1.39 |
| 9| 6983 | 98.69 | 33.18 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 39 | 2219 | 7158 | 99.82 | 38.19 | 1.55 |

