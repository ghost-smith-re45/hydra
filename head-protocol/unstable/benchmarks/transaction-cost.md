--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-18 05:48:16.748558739 UTC |
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
| 1| 5837 | 10.93 | 3.49 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 15.14 | 4.81 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 226 | 858 | 52.88 | 15.16 | 0.72 |
| 5 | 284 | 969 | 60.81 | 17.43 | 0.81 |
| 6 | 336 | 1081 | 70.93 | 20.18 | 0.92 |
| 7 | 395 | 1192 | 72.63 | 21.06 | 0.94 |
| 8 | 449 | 1303 | 89.06 | 25.34 | 1.11 |
| 9 | 505 | 1414 | 90.63 | 26.05 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.37 | 7.71 | 0.48 |
| 2| 1943 | 25.80 | 8.77 | 0.51 |
| 3| 2014 | 26.24 | 9.56 | 0.52 |
| 5| 2446 | 32.41 | 12.62 | 0.61 |
| 10| 3093 | 40.16 | 18.11 | 0.74 |
| 39| 7494 | 96.93 | 53.24 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 630 | 22.84 | 7.38 | 0.42 |
| 2| 722 | 22.56 | 7.94 | 0.42 |
| 3| 946 | 26.20 | 9.64 | 0.47 |
| 5| 1175 | 28.95 | 11.73 | 0.52 |
| 10| 1887 | 36.63 | 17.21 | 0.65 |
| 40| 6580 | 99.69 | 54.73 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 27.54 | 8.47 | 0.46 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 902 | 30.23 | 10.54 | 0.51 |
| 5| 1276 | 35.12 | 13.27 | 0.59 |
| 10| 1953 | 44.19 | 19.15 | 0.73 |
| 35| 5755 | 96.29 | 50.45 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.15 | 0.53 |
| 2| 820 | 35.89 | 11.39 | 0.56 |
| 3| 982 | 38.63 | 12.83 | 0.60 |
| 5| 1257 | 42.53 | 15.25 | 0.66 |
| 10| 1945 | 53.27 | 21.57 | 0.82 |
| 28| 4678 | 94.70 | 45.09 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.12 | 9.10 | 0.69 |
| 2| 5912 | 32.52 | 10.87 | 0.75 |
| 3| 6199 | 45.76 | 15.44 | 0.90 |
| 4| 6254 | 55.05 | 18.59 | 1.00 |
| 5| 6406 | 61.57 | 20.76 | 1.08 |
| 6| 6590 | 70.51 | 23.69 | 1.18 |
| 7| 6534 | 78.04 | 26.15 | 1.26 |
| 8| 6961 | 92.62 | 31.27 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

