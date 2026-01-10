--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-10 04:49:15.374720988 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.98 | 4.75 | 0.58 |
| 5| 6641 | 19.19 | 6.08 | 0.64 |
| 10| 7650 | 28.81 | 9.07 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 42.34 | 12.19 | 0.61 |
| 4 | 227 | 862 | 53.93 | 15.36 | 0.73 |
| 5 | 281 | 969 | 64.61 | 18.34 | 0.85 |
| 6 | 338 | 1081 | 68.28 | 19.62 | 0.89 |
| 7 | 396 | 1192 | 72.72 | 21.12 | 0.94 |
| 8 | 449 | 1303 | 96.55 | 27.29 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1973 | 26.50 | 8.99 | 0.52 |
| 3| 2013 | 25.98 | 9.50 | 0.52 |
| 5| 2442 | 32.08 | 12.54 | 0.61 |
| 10| 3297 | 43.86 | 19.17 | 0.79 |
| 38| 7540 | 99.07 | 53.18 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 22.54 | 7.31 | 0.41 |
| 2| 808 | 25.49 | 8.78 | 0.46 |
| 3| 871 | 25.58 | 9.50 | 0.46 |
| 5| 1215 | 29.82 | 11.99 | 0.53 |
| 10| 2207 | 43.54 | 19.15 | 0.74 |
| 41| 6540 | 99.02 | 55.20 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 873 | 29.82 | 9.80 | 0.50 |
| 3| 1032 | 34.11 | 11.65 | 0.56 |
| 5| 1181 | 36.28 | 13.55 | 0.59 |
| 10| 2092 | 45.61 | 19.58 | 0.75 |
| 37| 6067 | 98.05 | 52.28 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 1019 | 38.51 | 12.80 | 0.60 |
| 5| 1273 | 42.61 | 15.27 | 0.66 |
| 10| 1998 | 53.50 | 21.65 | 0.83 |
| 28| 4840 | 96.89 | 45.79 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5982 | 36.77 | 12.40 | 0.80 |
| 3| 6129 | 46.10 | 15.54 | 0.90 |
| 4| 6297 | 55.38 | 18.74 | 1.01 |
| 5| 6270 | 59.87 | 20.06 | 1.05 |
| 6| 6564 | 73.50 | 24.73 | 1.21 |
| 7| 6780 | 82.07 | 27.75 | 1.31 |
| 8| 6764 | 88.45 | 29.75 | 1.38 |
| 9| 6996 | 98.71 | 33.32 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2162 | 7125 | 96.44 | 36.92 | 1.51 |

