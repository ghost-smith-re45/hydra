--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-14 07:26:15.896311936 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6041 | 12.82 | 4.07 | 0.55 |
| 3| 6243 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.33 | 9.66 | 0.52 |
| 3 | 169 | 747 | 41.18 | 11.91 | 0.60 |
| 4 | 226 | 858 | 51.18 | 14.73 | 0.71 |
| 5 | 282 | 974 | 57.55 | 16.59 | 0.78 |
| 6 | 339 | 1085 | 73.29 | 20.82 | 0.94 |
| 7 | 394 | 1192 | 82.76 | 23.53 | 1.04 |
| 8 | 449 | 1307 | 99.29 | 27.95 | 1.21 |
| 9 | 507 | 1414 | 96.29 | 27.58 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1955 | 25.76 | 8.76 | 0.51 |
| 3| 2013 | 26.36 | 9.59 | 0.52 |
| 5| 2418 | 32.19 | 12.57 | 0.61 |
| 10| 3207 | 42.06 | 18.67 | 0.77 |
| 39| 7627 | 98.80 | 53.80 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.81 | 7.37 | 0.42 |
| 2| 747 | 24.31 | 8.45 | 0.44 |
| 3| 832 | 24.06 | 9.02 | 0.45 |
| 5| 1387 | 33.08 | 12.90 | 0.57 |
| 10| 2040 | 40.20 | 18.24 | 0.70 |
| 42| 6679 | 96.85 | 55.33 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.13 | 8.90 | 0.48 |
| 2| 860 | 29.89 | 9.82 | 0.50 |
| 3| 1043 | 34.22 | 11.68 | 0.56 |
| 5| 1173 | 36.27 | 13.55 | 0.59 |
| 10| 2040 | 47.48 | 20.05 | 0.77 |
| 36| 6010 | 98.21 | 51.72 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.87 | 10.16 | 0.53 |
| 2| 856 | 36.56 | 11.60 | 0.57 |
| 3| 1014 | 38.66 | 12.84 | 0.60 |
| 5| 1299 | 43.36 | 15.49 | 0.67 |
| 10| 1931 | 52.67 | 21.38 | 0.81 |
| 28| 4681 | 95.12 | 45.21 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 27.16 | 9.13 | 0.69 |
| 2| 5846 | 31.63 | 10.52 | 0.74 |
| 3| 6157 | 45.72 | 15.42 | 0.90 |
| 4| 6356 | 57.55 | 19.44 | 1.04 |
| 5| 6420 | 64.36 | 21.73 | 1.11 |
| 6| 6440 | 66.84 | 22.49 | 1.14 |
| 7| 6650 | 83.27 | 27.98 | 1.32 |
| 8| 6929 | 91.32 | 30.92 | 1.42 |
| 9| 6974 | 98.55 | 33.17 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 20 | 1139 | 6513 | 59.28 | 22.29 | 1.08 |
| 10 | 40 | 2273 | 7189 | 99.40 | 38.15 | 1.54 |

