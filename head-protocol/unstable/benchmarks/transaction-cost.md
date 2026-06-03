--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-03 09:57:24.603821672 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14279 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10033 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.55 | 12.23 | 0.62 |
| 4 | 227 | 858 | 48.25 | 14.02 | 0.68 |
| 5 | 282 | 969 | 57.72 | 16.66 | 0.78 |
| 6 | 338 | 1081 | 72.93 | 20.69 | 0.94 |
| 7 | 394 | 1192 | 80.63 | 22.98 | 1.02 |
| 8 | 450 | 1303 | 85.51 | 24.60 | 1.08 |
| 9 | 505 | 1414 | 96.08 | 27.42 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 24.00 | 7.62 | 0.48 |
| 2| 1984 | 26.84 | 9.06 | 0.52 |
| 3| 2013 | 26.32 | 9.58 | 0.52 |
| 5| 2371 | 31.33 | 12.32 | 0.60 |
| 10| 3306 | 43.62 | 19.10 | 0.79 |
| 39| 7453 | 94.86 | 52.67 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.54 | 7.30 | 0.41 |
| 2| 774 | 24.05 | 8.39 | 0.44 |
| 3| 893 | 25.85 | 9.57 | 0.47 |
| 5| 1193 | 29.18 | 11.81 | 0.52 |
| 10| 2020 | 39.06 | 17.89 | 0.68 |
| 40| 6431 | 95.11 | 53.51 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 27.54 | 8.47 | 0.46 |
| 2| 812 | 29.26 | 9.62 | 0.49 |
| 3| 987 | 31.62 | 10.96 | 0.53 |
| 5| 1358 | 38.48 | 14.22 | 0.62 |
| 10| 1963 | 44.12 | 19.13 | 0.73 |
| 37| 5879 | 95.69 | 51.57 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.83 | 10.15 | 0.53 |
| 2| 833 | 35.88 | 11.39 | 0.56 |
| 3| 996 | 38.47 | 12.79 | 0.60 |
| 5| 1253 | 42.53 | 15.25 | 0.66 |
| 10| 2056 | 54.42 | 21.92 | 0.84 |
| 28| 4553 | 92.99 | 44.59 | 1.42 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 26.96 | 9.06 | 0.69 |
| 2| 5994 | 36.89 | 12.48 | 0.80 |
| 3| 6107 | 44.81 | 15.04 | 0.89 |
| 4| 6163 | 50.51 | 16.94 | 0.95 |
| 5| 6437 | 63.94 | 21.53 | 1.11 |
| 6| 6713 | 75.89 | 25.68 | 1.24 |
| 7| 6659 | 82.78 | 27.83 | 1.31 |
| 8| 6910 | 90.51 | 30.49 | 1.41 |
| 9| 6851 | 96.27 | 32.35 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1138 | 6513 | 58.40 | 21.99 | 1.07 |
| 10 | 38 | 2157 | 7119 | 95.56 | 36.62 | 1.50 |

