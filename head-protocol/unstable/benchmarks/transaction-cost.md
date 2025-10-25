--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-25 04:38:17.884415604 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.84 | 4.08 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6646 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 99.51 | 31.12 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 171 | 747 | 43.44 | 12.44 | 0.62 |
| 4 | 227 | 862 | 49.50 | 14.30 | 0.69 |
| 5 | 281 | 969 | 59.46 | 17.11 | 0.80 |
| 6 | 339 | 1081 | 69.98 | 19.99 | 0.91 |
| 7 | 394 | 1192 | 85.00 | 24.03 | 1.06 |
| 8 | 451 | 1307 | 80.41 | 23.22 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.29 | 7.69 | 0.48 |
| 2| 1932 | 25.92 | 8.80 | 0.51 |
| 3| 2081 | 27.43 | 9.89 | 0.53 |
| 5| 2401 | 31.12 | 12.27 | 0.60 |
| 10| 3063 | 38.56 | 17.68 | 0.72 |
| 41| 7731 | 99.82 | 55.40 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 984 | 26.10 | 9.60 | 0.47 |
| 5| 1298 | 32.50 | 12.74 | 0.56 |
| 10| 1934 | 39.29 | 17.98 | 0.68 |
| 41| 6571 | 98.51 | 55.09 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 27.54 | 8.47 | 0.46 |
| 2| 834 | 29.18 | 9.60 | 0.49 |
| 3| 956 | 30.90 | 10.74 | 0.52 |
| 5| 1274 | 35.01 | 13.24 | 0.58 |
| 10| 1973 | 47.48 | 20.05 | 0.77 |
| 37| 6161 | 99.01 | 52.55 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 812 | 35.85 | 11.38 | 0.56 |
| 3| 959 | 37.84 | 12.60 | 0.59 |
| 5| 1162 | 41.18 | 14.84 | 0.64 |
| 10| 1987 | 54.09 | 21.82 | 0.83 |
| 29| 4912 | 98.23 | 46.77 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 5937 | 36.03 | 12.12 | 0.79 |
| 3| 6205 | 46.75 | 15.81 | 0.91 |
| 4| 6275 | 55.14 | 18.57 | 1.01 |
| 5| 6505 | 64.82 | 21.92 | 1.12 |
| 6| 6627 | 73.86 | 24.91 | 1.22 |
| 7| 6660 | 82.67 | 27.80 | 1.31 |
| 8| 6747 | 85.22 | 28.52 | 1.34 |
| 9| 6736 | 92.68 | 31.03 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 284 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 30 | 1706 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2166 | 7128 | 96.19 | 36.84 | 1.51 |

