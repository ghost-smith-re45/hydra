--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-23 04:58:25.350825037 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6042 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14286 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 40.13 | 11.66 | 0.59 |
| 4 | 228 | 858 | 50.68 | 14.56 | 0.70 |
| 5 | 282 | 969 | 56.14 | 16.31 | 0.76 |
| 6 | 337 | 1081 | 66.36 | 19.16 | 0.87 |
| 7 | 395 | 1192 | 78.22 | 22.40 | 1.00 |
| 8 | 448 | 1303 | 80.79 | 23.41 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.37 | 7.71 | 0.48 |
| 2| 1948 | 25.39 | 8.68 | 0.50 |
| 3| 2014 | 25.87 | 9.47 | 0.52 |
| 5| 2372 | 31.12 | 12.27 | 0.59 |
| 10| 3030 | 39.07 | 17.81 | 0.73 |
| 40| 7528 | 97.90 | 54.15 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.38 | 0.41 |
| 2| 845 | 25.37 | 8.75 | 0.46 |
| 3| 830 | 24.06 | 9.03 | 0.45 |
| 5| 1192 | 29.69 | 11.96 | 0.53 |
| 10| 2055 | 39.43 | 18.00 | 0.69 |
| 40| 6354 | 96.81 | 53.93 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.54 | 8.47 | 0.46 |
| 2| 816 | 29.26 | 9.62 | 0.49 |
| 3| 952 | 30.90 | 10.74 | 0.52 |
| 5| 1291 | 35.64 | 13.44 | 0.59 |
| 10| 2147 | 46.61 | 19.89 | 0.76 |
| 37| 6110 | 98.97 | 52.56 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 828 | 35.92 | 11.40 | 0.56 |
| 3| 937 | 37.91 | 12.62 | 0.59 |
| 5| 1212 | 41.90 | 15.05 | 0.65 |
| 10| 1945 | 52.67 | 21.38 | 0.82 |
| 28| 4864 | 98.05 | 46.10 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.96 | 9.05 | 0.69 |
| 2| 5924 | 35.96 | 12.08 | 0.79 |
| 3| 6208 | 46.76 | 15.81 | 0.92 |
| 4| 6304 | 55.87 | 18.88 | 1.02 |
| 5| 6403 | 63.78 | 21.53 | 1.10 |
| 6| 6471 | 71.09 | 23.93 | 1.18 |
| 7| 6698 | 80.86 | 27.28 | 1.29 |
| 8| 6876 | 91.72 | 30.83 | 1.42 |
| 9| 6887 | 97.79 | 32.89 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.99 | 7.82 | 0.65 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 36 | 2048 | 7056 | 92.34 | 35.31 | 1.46 |

