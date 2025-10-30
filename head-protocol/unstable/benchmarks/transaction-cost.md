--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-30 04:37:27.200372374 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 13.10 | 4.17 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14285 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 639 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 41.48 | 11.99 | 0.60 |
| 4 | 227 | 862 | 51.01 | 14.66 | 0.71 |
| 5 | 281 | 969 | 62.27 | 17.72 | 0.82 |
| 6 | 337 | 1081 | 75.33 | 21.27 | 0.96 |
| 7 | 395 | 1192 | 76.46 | 21.98 | 0.98 |
| 8 | 451 | 1303 | 85.02 | 24.47 | 1.07 |
| 9 | 504 | 1414 | 92.97 | 26.62 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.00 | 7.62 | 0.48 |
| 2| 1924 | 25.47 | 8.70 | 0.50 |
| 3| 2132 | 27.97 | 10.06 | 0.54 |
| 5| 2374 | 31.04 | 12.25 | 0.59 |
| 10| 3206 | 42.26 | 18.70 | 0.77 |
| 38| 7367 | 95.35 | 52.11 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 630 | 22.84 | 7.38 | 0.42 |
| 2| 701 | 22.62 | 7.95 | 0.42 |
| 3| 1002 | 28.00 | 10.15 | 0.49 |
| 5| 1275 | 31.00 | 12.32 | 0.55 |
| 10| 2095 | 40.50 | 18.30 | 0.70 |
| 42| 6549 | 95.94 | 55.04 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 27.54 | 8.47 | 0.46 |
| 2| 782 | 30.91 | 10.06 | 0.51 |
| 3| 973 | 30.87 | 10.74 | 0.52 |
| 5| 1211 | 36.98 | 13.76 | 0.60 |
| 10| 1946 | 44.03 | 19.11 | 0.73 |
| 36| 6036 | 97.55 | 51.49 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.83 | 10.15 | 0.53 |
| 2| 828 | 35.85 | 11.38 | 0.56 |
| 3| 988 | 38.66 | 12.84 | 0.60 |
| 5| 1158 | 41.11 | 14.82 | 0.64 |
| 10| 2028 | 54.02 | 21.80 | 0.83 |
| 28| 4855 | 96.86 | 45.76 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 27.08 | 9.08 | 0.69 |
| 2| 5932 | 35.80 | 12.03 | 0.79 |
| 3| 6143 | 45.97 | 15.50 | 0.90 |
| 4| 6258 | 54.80 | 18.46 | 1.00 |
| 5| 6548 | 66.19 | 22.49 | 1.14 |
| 6| 6526 | 70.40 | 23.71 | 1.18 |
| 7| 6861 | 85.13 | 28.83 | 1.35 |
| 8| 6931 | 90.74 | 30.67 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 568 | 6172 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1710 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2222 | 7162 | 97.79 | 37.50 | 1.53 |

