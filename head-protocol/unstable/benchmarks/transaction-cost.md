--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-04 05:05:03.254508079 UTC |
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
| 1| 5836 | 10.78 | 3.43 | 0.52 |
| 2| 6039 | 12.34 | 3.90 | 0.54 |
| 3| 6240 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 19.34 | 6.13 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 169 | 747 | 42.46 | 12.20 | 0.61 |
| 4 | 226 | 858 | 54.07 | 15.42 | 0.74 |
| 5 | 282 | 969 | 64.02 | 18.17 | 0.84 |
| 6 | 337 | 1081 | 69.72 | 19.96 | 0.91 |
| 7 | 395 | 1192 | 81.13 | 23.15 | 1.03 |
| 8 | 450 | 1303 | 83.16 | 23.93 | 1.05 |
| 9 | 506 | 1414 | 97.04 | 27.82 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1825 | 24.00 | 7.62 | 0.48 |
| 2| 1924 | 25.39 | 8.68 | 0.50 |
| 3| 2179 | 29.10 | 10.38 | 0.56 |
| 5| 2317 | 29.89 | 11.93 | 0.58 |
| 10| 3190 | 41.43 | 18.49 | 0.76 |
| 43| 7770 | 98.94 | 56.42 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 846 | 25.36 | 8.75 | 0.46 |
| 3| 857 | 24.11 | 9.04 | 0.45 |
| 5| 1251 | 30.10 | 12.06 | 0.54 |
| 10| 2050 | 40.96 | 18.43 | 0.70 |
| 42| 6660 | 97.48 | 55.52 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 29.13 | 8.90 | 0.48 |
| 2| 812 | 30.94 | 10.07 | 0.51 |
| 3| 906 | 30.15 | 10.52 | 0.51 |
| 5| 1131 | 35.60 | 13.34 | 0.58 |
| 10| 2021 | 47.63 | 20.09 | 0.77 |
| 36| 6025 | 99.82 | 52.21 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.87 | 10.16 | 0.53 |
| 2| 830 | 35.92 | 11.40 | 0.56 |
| 3| 948 | 37.95 | 12.63 | 0.59 |
| 5| 1204 | 41.93 | 15.06 | 0.65 |
| 10| 2049 | 54.46 | 21.93 | 0.84 |
| 30| 4989 | 99.68 | 47.81 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 26.92 | 9.04 | 0.69 |
| 2| 6014 | 36.93 | 12.44 | 0.80 |
| 3| 6039 | 44.73 | 15.05 | 0.89 |
| 4| 6366 | 57.53 | 19.42 | 1.04 |
| 5| 6338 | 62.63 | 21.05 | 1.09 |
| 6| 6626 | 74.73 | 25.17 | 1.23 |
| 7| 6737 | 83.74 | 28.22 | 1.33 |
| 8| 6787 | 90.44 | 30.33 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

