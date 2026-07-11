--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-11 07:32:45.883774512 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 13.10 | 4.17 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.88 | 5.97 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 169 | 747 | 42.73 | 12.31 | 0.62 |
| 4 | 225 | 858 | 49.27 | 14.22 | 0.69 |
| 5 | 282 | 969 | 62.37 | 17.74 | 0.82 |
| 6 | 338 | 1081 | 73.01 | 20.68 | 0.94 |
| 7 | 393 | 1192 | 84.95 | 23.97 | 1.06 |
| 8 | 449 | 1303 | 91.62 | 26.00 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.37 | 7.71 | 0.48 |
| 2| 1935 | 25.89 | 8.79 | 0.51 |
| 3| 2055 | 27.39 | 9.88 | 0.53 |
| 5| 2335 | 30.33 | 12.04 | 0.58 |
| 10| 3173 | 41.89 | 18.61 | 0.76 |
| 40| 7533 | 98.41 | 54.27 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.54 | 7.30 | 0.41 |
| 2| 805 | 25.55 | 8.81 | 0.46 |
| 3| 1041 | 28.13 | 10.18 | 0.50 |
| 5| 1201 | 28.35 | 11.57 | 0.52 |
| 10| 2084 | 41.59 | 18.62 | 0.71 |
| 41| 6461 | 98.35 | 55.01 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.17 | 8.91 | 0.48 |
| 2| 821 | 29.22 | 9.61 | 0.49 |
| 3| 982 | 31.62 | 10.96 | 0.53 |
| 5| 1221 | 37.14 | 13.81 | 0.60 |
| 10| 2051 | 47.70 | 20.13 | 0.77 |
| 36| 5891 | 95.88 | 51.00 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.83 | 10.15 | 0.53 |
| 2| 861 | 36.60 | 11.61 | 0.57 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1200 | 41.82 | 15.03 | 0.65 |
| 10| 1940 | 52.63 | 21.37 | 0.81 |
| 28| 4893 | 98.41 | 46.24 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.08 | 9.08 | 0.69 |
| 2| 5935 | 35.99 | 12.08 | 0.79 |
| 3| 6039 | 44.03 | 14.75 | 0.88 |
| 4| 6094 | 49.09 | 16.41 | 0.93 |
| 5| 6431 | 61.27 | 20.60 | 1.08 |
| 6| 6744 | 75.93 | 25.65 | 1.25 |
| 7| 6840 | 84.77 | 28.69 | 1.34 |
| 8| 6826 | 90.32 | 30.44 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6003 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1136 | 6511 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.24 | 37.65 | 1.53 |

