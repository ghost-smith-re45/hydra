--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-29 05:22:39.358328532 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14285 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2161 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 751 | 43.95 | 12.60 | 0.63 |
| 4 | 228 | 858 | 53.72 | 15.33 | 0.73 |
| 5 | 282 | 969 | 64.23 | 18.22 | 0.84 |
| 6 | 340 | 1081 | 69.89 | 19.97 | 0.91 |
| 7 | 395 | 1192 | 77.87 | 22.27 | 0.99 |
| 8 | 452 | 1303 | 89.59 | 25.47 | 1.12 |
| 9 | 505 | 1414 | 94.75 | 27.33 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.37 | 7.71 | 0.48 |
| 2| 1883 | 24.85 | 8.50 | 0.50 |
| 3| 2056 | 27.32 | 9.86 | 0.53 |
| 5| 2502 | 33.40 | 12.90 | 0.62 |
| 10| 3191 | 42.26 | 18.70 | 0.77 |
| 40| 7607 | 97.13 | 53.97 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 794 | 25.52 | 8.81 | 0.45 |
| 3| 948 | 27.08 | 9.89 | 0.48 |
| 5| 1134 | 28.18 | 11.52 | 0.51 |
| 10| 1913 | 38.81 | 17.84 | 0.68 |
| 42| 6559 | 95.49 | 54.92 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 27.50 | 8.46 | 0.46 |
| 2| 770 | 28.47 | 9.38 | 0.48 |
| 3| 957 | 30.90 | 10.74 | 0.52 |
| 5| 1184 | 36.24 | 13.54 | 0.59 |
| 10| 2024 | 48.15 | 20.26 | 0.77 |
| 39| 6115 | 98.91 | 53.77 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 824 | 35.81 | 11.37 | 0.56 |
| 3| 1033 | 39.34 | 13.05 | 0.61 |
| 5| 1257 | 42.45 | 15.23 | 0.66 |
| 10| 2084 | 55.50 | 22.26 | 0.85 |
| 30| 4879 | 98.75 | 47.52 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 26.96 | 9.05 | 0.69 |
| 2| 5936 | 35.84 | 12.04 | 0.79 |
| 3| 6071 | 45.03 | 15.15 | 0.89 |
| 4| 6260 | 55.12 | 18.57 | 1.00 |
| 5| 6367 | 64.53 | 21.68 | 1.11 |
| 6| 6564 | 73.09 | 24.57 | 1.21 |
| 7| 6830 | 84.06 | 28.36 | 1.33 |
| 8| 7078 | 95.15 | 32.18 | 1.46 |
| 9| 7017 | 99.03 | 33.42 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

