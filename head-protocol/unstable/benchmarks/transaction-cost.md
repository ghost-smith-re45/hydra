--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-10 09:25:55.384560577 UTC |
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
| 1| 5836 | 10.28 | 3.25 | 0.51 |
| 2| 6041 | 12.82 | 4.07 | 0.55 |
| 3| 6242 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 19.00 | 6.01 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 40.24 | 11.69 | 0.59 |
| 4 | 227 | 858 | 54.07 | 15.42 | 0.74 |
| 5 | 283 | 974 | 61.35 | 17.53 | 0.82 |
| 6 | 338 | 1081 | 71.28 | 20.26 | 0.92 |
| 7 | 395 | 1192 | 80.07 | 22.80 | 1.01 |
| 8 | 450 | 1307 | 83.07 | 23.96 | 1.05 |
| 9 | 504 | 1414 | 95.98 | 27.51 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1824 | 24.29 | 7.69 | 0.48 |
| 2| 1940 | 25.51 | 8.70 | 0.50 |
| 3| 2066 | 27.27 | 9.85 | 0.53 |
| 5| 2315 | 30.22 | 12.01 | 0.58 |
| 10| 3282 | 43.10 | 18.94 | 0.78 |
| 39| 7435 | 97.39 | 53.32 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.54 | 7.30 | 0.41 |
| 2| 760 | 23.51 | 8.21 | 0.43 |
| 3| 942 | 26.14 | 9.61 | 0.47 |
| 5| 1092 | 27.15 | 11.24 | 0.50 |
| 10| 1848 | 37.49 | 17.48 | 0.66 |
| 42| 6763 | 99.95 | 56.17 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 29.13 | 8.90 | 0.48 |
| 2| 830 | 29.19 | 9.60 | 0.49 |
| 3| 948 | 30.86 | 10.73 | 0.52 |
| 5| 1172 | 36.20 | 13.53 | 0.59 |
| 10| 1882 | 46.16 | 19.66 | 0.75 |
| 34| 5685 | 98.94 | 50.50 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 837 | 35.85 | 11.38 | 0.56 |
| 3| 941 | 37.87 | 12.61 | 0.59 |
| 5| 1157 | 41.11 | 14.82 | 0.64 |
| 10| 1964 | 53.41 | 21.61 | 0.82 |
| 28| 5007 | 99.68 | 46.63 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 6023 | 36.92 | 12.46 | 0.80 |
| 3| 6084 | 45.00 | 15.10 | 0.89 |
| 4| 6233 | 53.84 | 18.12 | 0.99 |
| 5| 6323 | 60.74 | 20.40 | 1.07 |
| 6| 6619 | 74.35 | 25.00 | 1.22 |
| 7| 6769 | 82.63 | 27.88 | 1.32 |
| 8| 6973 | 91.25 | 30.77 | 1.42 |
| 9| 7059 | 99.76 | 33.60 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1705 | 6851 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2218 | 7158 | 98.49 | 37.73 | 1.53 |

