--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-22 07:18:47.193181447 UTC |
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
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 15.05 | 4.78 | 0.58 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 751 | 41.51 | 12.00 | 0.61 |
| 4 | 225 | 862 | 48.19 | 13.99 | 0.68 |
| 5 | 283 | 969 | 57.74 | 16.69 | 0.78 |
| 6 | 338 | 1081 | 69.47 | 19.87 | 0.90 |
| 7 | 393 | 1192 | 80.15 | 22.77 | 1.01 |
| 8 | 452 | 1303 | 87.15 | 24.94 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.29 | 7.69 | 0.48 |
| 2| 1883 | 24.40 | 8.39 | 0.49 |
| 3| 2101 | 28.09 | 10.09 | 0.54 |
| 5| 2439 | 32.48 | 12.64 | 0.61 |
| 10| 3044 | 38.25 | 17.60 | 0.72 |
| 37| 7005 | 89.59 | 49.88 | 1.54 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.57 | 7.32 | 0.41 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 884 | 25.09 | 9.31 | 0.46 |
| 5| 1321 | 31.40 | 12.44 | 0.55 |
| 10| 1928 | 37.88 | 17.56 | 0.67 |
| 42| 6794 | 99.53 | 56.06 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 27.54 | 8.47 | 0.46 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 1004 | 31.65 | 10.97 | 0.53 |
| 5| 1171 | 36.23 | 13.54 | 0.59 |
| 10| 2229 | 47.76 | 20.23 | 0.78 |
| 36| 5931 | 97.33 | 51.44 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 845 | 36.56 | 11.60 | 0.57 |
| 3| 1012 | 38.59 | 12.82 | 0.60 |
| 5| 1319 | 42.87 | 15.35 | 0.67 |
| 10| 2174 | 56.31 | 22.49 | 0.86 |
| 28| 4861 | 97.51 | 45.94 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5831 | 27.08 | 9.09 | 0.69 |
| 2| 5945 | 35.76 | 12.02 | 0.79 |
| 3| 6110 | 45.86 | 15.47 | 0.90 |
| 4| 6233 | 54.12 | 18.19 | 0.99 |
| 5| 6461 | 65.28 | 22.01 | 1.12 |
| 6| 6651 | 74.91 | 25.34 | 1.23 |
| 7| 6602 | 74.60 | 24.98 | 1.22 |
| 8| 6856 | 91.08 | 30.68 | 1.41 |
| 9| 6790 | 95.06 | 31.93 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

