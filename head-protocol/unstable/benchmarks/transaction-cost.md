--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-27 09:13:28.619946415 UTC |
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
| 1| 5834 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6646 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 751 | 40.11 | 11.68 | 0.59 |
| 4 | 227 | 858 | 49.58 | 14.34 | 0.69 |
| 5 | 281 | 969 | 57.61 | 16.67 | 0.78 |
| 6 | 338 | 1081 | 64.36 | 18.64 | 0.85 |
| 7 | 394 | 1192 | 74.37 | 21.43 | 0.96 |
| 8 | 449 | 1303 | 82.80 | 23.90 | 1.05 |
| 9 | 508 | 1414 | 98.47 | 28.05 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1825 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.40 | 8.40 | 0.49 |
| 3| 2017 | 26.24 | 9.56 | 0.52 |
| 5| 2336 | 30.26 | 12.02 | 0.58 |
| 10| 3165 | 41.80 | 18.58 | 0.76 |
| 41| 7815 | 99.89 | 55.42 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 22.57 | 7.33 | 0.41 |
| 2| 818 | 25.17 | 8.70 | 0.45 |
| 3| 914 | 26.71 | 9.79 | 0.48 |
| 5| 1256 | 31.43 | 12.45 | 0.55 |
| 10| 1995 | 38.62 | 17.77 | 0.68 |
| 40| 6734 | 99.74 | 54.80 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 732 | 30.19 | 9.84 | 0.50 |
| 3| 959 | 33.43 | 11.44 | 0.55 |
| 5| 1274 | 35.08 | 13.26 | 0.59 |
| 10| 2027 | 47.21 | 19.98 | 0.76 |
| 35| 5788 | 95.11 | 50.13 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 761 | 35.14 | 11.16 | 0.55 |
| 3| 994 | 38.47 | 12.79 | 0.60 |
| 5| 1204 | 42.01 | 15.08 | 0.65 |
| 10| 2057 | 53.99 | 21.79 | 0.83 |
| 27| 4648 | 94.00 | 44.29 | 1.43 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.09 | 9.09 | 0.69 |
| 2| 5999 | 37.05 | 12.47 | 0.80 |
| 3| 6190 | 47.13 | 15.94 | 0.92 |
| 4| 6364 | 56.06 | 18.94 | 1.02 |
| 5| 6359 | 62.65 | 21.11 | 1.09 |
| 6| 6482 | 72.21 | 24.25 | 1.19 |
| 7| 6848 | 84.58 | 28.52 | 1.34 |
| 8| 6943 | 95.32 | 32.18 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 22.29 | 7.58 | 0.64 |
| 10 | 10 | 568 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.49 | 37.73 | 1.53 |

