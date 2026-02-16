--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-16 05:43:11.997179108 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.93 | 5.98 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 41.51 | 12.00 | 0.61 |
| 4 | 227 | 858 | 53.73 | 15.31 | 0.73 |
| 5 | 282 | 969 | 59.64 | 17.12 | 0.80 |
| 6 | 338 | 1085 | 64.79 | 18.79 | 0.86 |
| 7 | 394 | 1192 | 72.66 | 21.07 | 0.94 |
| 8 | 451 | 1303 | 98.52 | 27.66 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.00 | 7.62 | 0.48 |
| 2| 1955 | 25.39 | 8.68 | 0.50 |
| 3| 2189 | 29.10 | 10.38 | 0.56 |
| 5| 2337 | 29.88 | 11.93 | 0.58 |
| 10| 3254 | 42.43 | 18.76 | 0.77 |
| 42| 7891 | 99.30 | 55.94 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 621 | 22.57 | 7.32 | 0.41 |
| 2| 812 | 25.57 | 8.80 | 0.46 |
| 3| 873 | 25.51 | 9.46 | 0.46 |
| 5| 1206 | 29.11 | 11.78 | 0.52 |
| 10| 1896 | 36.55 | 17.19 | 0.65 |
| 42| 6680 | 97.26 | 55.43 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 710 | 27.54 | 8.47 | 0.47 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 924 | 32.68 | 11.22 | 0.54 |
| 5| 1287 | 35.79 | 13.48 | 0.59 |
| 10| 2135 | 49.61 | 20.70 | 0.79 |
| 37| 6175 | 99.35 | 52.70 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 891 | 37.13 | 12.38 | 0.58 |
| 5| 1366 | 44.07 | 15.71 | 0.68 |
| 10| 1991 | 53.16 | 21.54 | 0.82 |
| 30| 4866 | 98.91 | 47.59 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.09 | 9.09 | 0.69 |
| 2| 5983 | 35.84 | 12.04 | 0.79 |
| 3| 6128 | 45.93 | 15.47 | 0.90 |
| 4| 6357 | 55.89 | 18.91 | 1.02 |
| 5| 6622 | 66.77 | 22.64 | 1.14 |
| 6| 6490 | 66.84 | 22.51 | 1.14 |
| 7| 6606 | 75.08 | 25.21 | 1.23 |
| 8| 6936 | 93.38 | 31.51 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6003 | 30.67 | 10.88 | 0.74 |
| 10 | 10 | 568 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2166 | 7128 | 96.44 | 36.92 | 1.51 |

