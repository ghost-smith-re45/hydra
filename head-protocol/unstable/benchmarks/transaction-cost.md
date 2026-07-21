--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-21 07:48:43.251469071 UTC |
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
| 2| 6041 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 751 | 41.48 | 11.99 | 0.60 |
| 4 | 226 | 858 | 53.83 | 15.31 | 0.73 |
| 5 | 282 | 969 | 64.04 | 18.14 | 0.84 |
| 6 | 337 | 1081 | 68.01 | 19.52 | 0.89 |
| 7 | 395 | 1192 | 84.00 | 23.74 | 1.05 |
| 8 | 449 | 1303 | 81.05 | 23.48 | 1.03 |
| 9 | 505 | 1414 | 87.85 | 25.39 | 1.11 |
| 10 | 561 | 1525 | 98.06 | 28.54 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 23.30 | 7.41 | 0.47 |
| 2| 1924 | 25.39 | 8.68 | 0.50 |
| 3| 2011 | 26.32 | 9.58 | 0.52 |
| 5| 2508 | 33.32 | 12.88 | 0.62 |
| 10| 3201 | 42.64 | 18.81 | 0.77 |
| 40| 7705 | 98.08 | 54.24 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.53 | 7.30 | 0.41 |
| 2| 743 | 23.62 | 8.23 | 0.43 |
| 3| 955 | 25.98 | 9.57 | 0.47 |
| 5| 1251 | 30.70 | 12.24 | 0.54 |
| 10| 1923 | 37.55 | 17.47 | 0.66 |
| 40| 6421 | 95.51 | 53.62 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.09 | 8.89 | 0.48 |
| 2| 850 | 29.86 | 9.81 | 0.50 |
| 3| 986 | 31.69 | 10.98 | 0.53 |
| 5| 1210 | 36.94 | 13.75 | 0.60 |
| 10| 2097 | 46.02 | 19.70 | 0.76 |
| 37| 6066 | 99.84 | 52.78 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.12 | 9.94 | 0.52 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 937 | 37.80 | 12.59 | 0.59 |
| 5| 1395 | 43.96 | 15.68 | 0.68 |
| 10| 2032 | 54.14 | 21.83 | 0.83 |
| 30| 5018 | 99.68 | 47.81 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.12 | 9.10 | 0.69 |
| 2| 6024 | 36.92 | 12.47 | 0.80 |
| 3| 6093 | 42.29 | 14.22 | 0.86 |
| 4| 6353 | 55.97 | 18.86 | 1.02 |
| 5| 6401 | 63.91 | 21.49 | 1.10 |
| 6| 6608 | 74.16 | 25.01 | 1.22 |
| 7| 6812 | 84.62 | 28.51 | 1.34 |
| 8| 6798 | 87.78 | 29.48 | 1.37 |
| 9| 7047 | 99.56 | 33.49 | 1.51 |
| 10| 6928 | 99.78 | 33.53 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 286 | 6006 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2222 | 7162 | 98.49 | 37.73 | 1.53 |

