--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-09 06:23:59.702226488 UTC |
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
| 1| 5837 | 10.35 | 3.28 | 0.51 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 747 | 41.35 | 11.98 | 0.60 |
| 4 | 228 | 858 | 53.89 | 15.37 | 0.73 |
| 5 | 284 | 969 | 56.08 | 16.27 | 0.76 |
| 6 | 341 | 1081 | 74.69 | 21.08 | 0.95 |
| 7 | 394 | 1192 | 78.39 | 22.44 | 1.00 |
| 8 | 451 | 1303 | 84.87 | 24.39 | 1.07 |
| 9 | 504 | 1414 | 96.96 | 27.80 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.37 | 7.71 | 0.48 |
| 2| 1877 | 24.43 | 8.40 | 0.49 |
| 3| 2136 | 27.89 | 10.04 | 0.54 |
| 5| 2441 | 32.32 | 12.60 | 0.61 |
| 10| 3219 | 42.96 | 18.91 | 0.78 |
| 40| 7744 | 99.90 | 54.73 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 722 | 22.56 | 7.94 | 0.42 |
| 3| 979 | 26.95 | 9.86 | 0.48 |
| 5| 1287 | 30.75 | 12.26 | 0.54 |
| 10| 1883 | 37.42 | 17.43 | 0.66 |
| 40| 6370 | 93.53 | 53.04 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 29.17 | 8.91 | 0.48 |
| 2| 804 | 29.22 | 9.61 | 0.49 |
| 3| 990 | 31.61 | 10.96 | 0.53 |
| 5| 1172 | 36.39 | 13.58 | 0.59 |
| 10| 1949 | 46.76 | 19.83 | 0.76 |
| 37| 5880 | 96.41 | 51.75 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.89 | 11.39 | 0.56 |
| 3| 1012 | 38.63 | 12.83 | 0.60 |
| 5| 1325 | 43.40 | 15.50 | 0.67 |
| 10| 1928 | 52.60 | 21.37 | 0.81 |
| 28| 4887 | 98.71 | 46.28 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5929 | 36.04 | 12.10 | 0.79 |
| 3| 6101 | 45.13 | 15.18 | 0.89 |
| 4| 6232 | 51.67 | 17.35 | 0.97 |
| 5| 6498 | 64.17 | 21.59 | 1.11 |
| 6| 6583 | 71.37 | 24.06 | 1.19 |
| 7| 6798 | 84.95 | 28.76 | 1.34 |
| 8| 6819 | 93.33 | 31.38 | 1.43 |
| 9| 6857 | 97.91 | 32.93 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 571 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1706 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

