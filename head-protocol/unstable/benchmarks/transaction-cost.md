--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-25 04:57:33.445115453 UTC |
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
| 1| 5838 | 10.59 | 3.36 | 0.52 |
| 2| 6042 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.58 | 5.86 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 40.10 | 11.64 | 0.59 |
| 4 | 226 | 858 | 52.28 | 14.94 | 0.72 |
| 5 | 284 | 969 | 61.48 | 17.60 | 0.82 |
| 6 | 336 | 1081 | 66.39 | 19.17 | 0.87 |
| 7 | 393 | 1192 | 83.13 | 23.62 | 1.04 |
| 8 | 450 | 1303 | 80.94 | 23.50 | 1.03 |
| 9 | 506 | 1414 | 91.29 | 26.33 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.92 | 8.80 | 0.51 |
| 3| 2064 | 26.87 | 9.75 | 0.53 |
| 5| 2362 | 30.99 | 12.24 | 0.59 |
| 10| 3100 | 40.08 | 18.09 | 0.74 |
| 38| 7324 | 93.20 | 51.54 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.84 | 7.37 | 0.41 |
| 2| 799 | 23.63 | 8.24 | 0.44 |
| 3| 902 | 25.45 | 9.45 | 0.46 |
| 5| 1175 | 29.03 | 11.75 | 0.52 |
| 10| 2038 | 38.81 | 17.82 | 0.68 |
| 40| 6310 | 93.14 | 52.92 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.50 | 8.46 | 0.46 |
| 2| 892 | 29.97 | 9.84 | 0.50 |
| 3| 980 | 33.69 | 11.53 | 0.55 |
| 5| 1327 | 38.56 | 14.24 | 0.62 |
| 10| 1925 | 46.61 | 19.79 | 0.75 |
| 35| 5695 | 98.62 | 51.00 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 33.15 | 9.95 | 0.52 |
| 2| 860 | 36.64 | 11.62 | 0.57 |
| 3| 1013 | 38.51 | 12.80 | 0.60 |
| 5| 1201 | 41.86 | 15.04 | 0.65 |
| 10| 2095 | 55.02 | 22.10 | 0.85 |
| 28| 4587 | 94.53 | 45.03 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 23.01 | 7.58 | 0.64 |
| 2| 6013 | 37.05 | 12.48 | 0.80 |
| 3| 6044 | 41.20 | 13.79 | 0.85 |
| 4| 6339 | 56.56 | 19.15 | 1.02 |
| 5| 6354 | 60.49 | 20.33 | 1.07 |
| 6| 6622 | 74.29 | 25.06 | 1.22 |
| 7| 6678 | 83.82 | 28.26 | 1.33 |
| 8| 6797 | 89.32 | 30.05 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2215 | 7154 | 98.05 | 37.58 | 1.53 |

