--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-30 04:49:35.85061183 UTC |
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
| 1| 5840 | 10.85 | 3.45 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6243 | 14.40 | 4.55 | 0.57 |
| 5| 6638 | 19.00 | 6.01 | 0.64 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 99.06 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.34 | 9.42 | 0.51 |
| 3 | 171 | 751 | 41.38 | 11.97 | 0.60 |
| 4 | 227 | 862 | 53.94 | 15.39 | 0.73 |
| 5 | 283 | 969 | 59.89 | 17.21 | 0.80 |
| 6 | 337 | 1081 | 71.68 | 20.43 | 0.92 |
| 7 | 392 | 1192 | 72.74 | 21.17 | 0.94 |
| 8 | 450 | 1303 | 85.51 | 24.55 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 24.37 | 7.71 | 0.48 |
| 2| 1956 | 25.85 | 8.78 | 0.51 |
| 3| 2013 | 25.98 | 9.50 | 0.52 |
| 5| 2333 | 30.53 | 12.09 | 0.59 |
| 10| 3162 | 40.58 | 18.25 | 0.75 |
| 40| 7688 | 98.49 | 54.38 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.77 | 7.36 | 0.42 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 912 | 25.72 | 9.52 | 0.47 |
| 5| 1221 | 29.04 | 11.76 | 0.52 |
| 10| 1975 | 39.45 | 18.00 | 0.69 |
| 42| 6911 | 99.25 | 56.01 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 27.47 | 8.46 | 0.46 |
| 2| 770 | 28.47 | 9.38 | 0.48 |
| 3| 968 | 33.47 | 11.46 | 0.55 |
| 5| 1288 | 37.81 | 14.01 | 0.61 |
| 10| 2168 | 47.15 | 20.05 | 0.77 |
| 37| 6152 | 98.43 | 52.39 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.16 | 0.53 |
| 2| 808 | 35.85 | 11.38 | 0.56 |
| 3| 1001 | 38.55 | 12.81 | 0.60 |
| 5| 1311 | 43.32 | 15.49 | 0.67 |
| 10| 2034 | 54.29 | 21.86 | 0.84 |
| 28| 4646 | 94.52 | 45.04 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5891 | 35.02 | 11.72 | 0.78 |
| 3| 6016 | 43.79 | 14.67 | 0.87 |
| 4| 6245 | 55.25 | 18.63 | 1.01 |
| 5| 6249 | 55.92 | 18.73 | 1.01 |
| 6| 6662 | 74.75 | 25.18 | 1.23 |
| 7| 6825 | 86.36 | 29.18 | 1.36 |
| 8| 6814 | 87.14 | 29.39 | 1.37 |
| 9| 6683 | 85.81 | 28.66 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 78.71 | 30.00 | 1.30 |
| 10 | 39 | 2222 | 7161 | 98.49 | 37.73 | 1.53 |

