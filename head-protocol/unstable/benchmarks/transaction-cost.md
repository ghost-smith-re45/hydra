--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-08 10:12:08.941938221 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.92 | 4.11 | 0.55 |
| 3| 6242 | 14.50 | 4.58 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.49 | 9.31 | 0.79 |
| 43| 14279 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1272 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 43.77 | 12.52 | 0.63 |
| 4 | 228 | 858 | 48.38 | 14.06 | 0.68 |
| 5 | 283 | 969 | 55.78 | 16.25 | 0.76 |
| 6 | 341 | 1081 | 66.77 | 19.30 | 0.88 |
| 7 | 393 | 1192 | 82.87 | 23.52 | 1.04 |
| 8 | 449 | 1303 | 95.94 | 26.94 | 1.18 |
| 10 | 560 | 1525 | 99.05 | 28.52 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 23.92 | 7.60 | 0.48 |
| 2| 1923 | 25.55 | 8.71 | 0.50 |
| 3| 2090 | 26.98 | 9.78 | 0.53 |
| 5| 2335 | 30.26 | 12.02 | 0.58 |
| 10| 3103 | 39.56 | 17.96 | 0.74 |
| 39| 7407 | 94.59 | 52.60 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 751 | 24.08 | 8.39 | 0.44 |
| 3| 930 | 25.06 | 9.31 | 0.46 |
| 5| 1254 | 30.21 | 12.09 | 0.54 |
| 10| 1906 | 37.68 | 17.51 | 0.66 |
| 40| 6510 | 95.46 | 53.58 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.17 | 8.91 | 0.48 |
| 2| 771 | 28.55 | 9.40 | 0.48 |
| 3| 1007 | 31.69 | 10.98 | 0.53 |
| 5| 1223 | 37.06 | 13.79 | 0.60 |
| 10| 2102 | 48.79 | 20.45 | 0.78 |
| 37| 5964 | 97.43 | 52.05 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 900 | 37.20 | 12.40 | 0.58 |
| 5| 1354 | 44.03 | 15.70 | 0.68 |
| 10| 2026 | 54.10 | 21.82 | 0.83 |
| 30| 5026 | 99.73 | 47.84 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 26.97 | 9.05 | 0.69 |
| 2| 6053 | 36.97 | 12.46 | 0.81 |
| 3| 6140 | 45.74 | 15.41 | 0.90 |
| 4| 6305 | 55.56 | 18.83 | 1.01 |
| 5| 6394 | 60.66 | 20.43 | 1.07 |
| 6| 6560 | 73.83 | 24.83 | 1.21 |
| 7| 6700 | 82.47 | 27.78 | 1.31 |
| 8| 6730 | 86.36 | 28.91 | 1.35 |
| 9| 6787 | 91.52 | 30.72 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 40 | 2279 | 7195 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2220 | 7159 | 97.16 | 37.28 | 1.52 |

