--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-28 06:37:38.788364207 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.55 | 9.33 | 0.79 |
| 43| 14281 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 41.12 | 11.88 | 0.60 |
| 4 | 227 | 858 | 49.73 | 14.38 | 0.69 |
| 5 | 283 | 969 | 59.61 | 17.17 | 0.80 |
| 6 | 339 | 1081 | 66.44 | 19.22 | 0.87 |
| 7 | 395 | 1196 | 78.58 | 22.49 | 1.00 |
| 8 | 449 | 1303 | 80.97 | 23.51 | 1.03 |
| 9 | 504 | 1414 | 90.08 | 25.97 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.37 | 7.71 | 0.48 |
| 2| 1922 | 25.88 | 8.79 | 0.51 |
| 3| 2158 | 29.58 | 10.49 | 0.56 |
| 5| 2334 | 29.93 | 11.94 | 0.58 |
| 10| 3143 | 41.15 | 18.39 | 0.75 |
| 39| 7556 | 98.95 | 53.80 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 22.81 | 7.38 | 0.42 |
| 2| 761 | 24.00 | 8.38 | 0.44 |
| 3| 988 | 27.94 | 10.13 | 0.49 |
| 5| 1218 | 30.09 | 12.08 | 0.53 |
| 10| 2073 | 40.70 | 18.37 | 0.70 |
| 42| 6518 | 96.50 | 55.21 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.94 | 10.07 | 0.51 |
| 3| 902 | 30.15 | 10.52 | 0.51 |
| 5| 1328 | 38.44 | 14.21 | 0.62 |
| 10| 2029 | 45.24 | 19.47 | 0.75 |
| 36| 6067 | 99.85 | 52.18 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 818 | 35.81 | 11.37 | 0.56 |
| 3| 954 | 37.91 | 12.62 | 0.59 |
| 5| 1320 | 43.35 | 15.49 | 0.67 |
| 10| 2067 | 54.81 | 22.03 | 0.84 |
| 29| 4912 | 99.78 | 47.21 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.00 | 9.07 | 0.69 |
| 2| 5986 | 35.76 | 12.02 | 0.79 |
| 3| 6012 | 41.25 | 13.80 | 0.85 |
| 4| 6199 | 51.19 | 17.23 | 0.96 |
| 5| 6262 | 57.39 | 19.23 | 1.03 |
| 6| 6390 | 67.80 | 22.72 | 1.14 |
| 7| 6821 | 85.99 | 29.04 | 1.35 |
| 8| 6811 | 89.38 | 30.07 | 1.39 |
| 9| 6932 | 97.31 | 32.64 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 36 | 2048 | 7057 | 92.34 | 35.31 | 1.46 |

