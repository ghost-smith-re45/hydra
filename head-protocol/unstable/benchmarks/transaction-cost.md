--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-27 04:40:07.189306796 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6039 | 12.80 | 4.07 | 0.55 |
| 3| 6240 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 226 | 858 | 51.44 | 14.82 | 0.71 |
| 5 | 283 | 969 | 57.49 | 16.57 | 0.78 |
| 6 | 337 | 1085 | 70.50 | 20.19 | 0.91 |
| 7 | 394 | 1192 | 76.26 | 21.84 | 0.98 |
| 8 | 452 | 1307 | 82.71 | 23.82 | 1.05 |
| 9 | 506 | 1414 | 99.08 | 28.30 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.00 | 7.62 | 0.48 |
| 2| 2001 | 26.96 | 9.09 | 0.52 |
| 3| 2062 | 27.31 | 9.86 | 0.53 |
| 5| 2436 | 32.51 | 12.66 | 0.61 |
| 10| 3233 | 43.13 | 18.97 | 0.78 |
| 41| 7745 | 97.31 | 54.71 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 22.81 | 7.38 | 0.42 |
| 2| 772 | 24.05 | 8.39 | 0.44 |
| 3| 870 | 25.55 | 9.49 | 0.46 |
| 5| 1413 | 33.43 | 13.00 | 0.58 |
| 10| 2023 | 40.22 | 18.23 | 0.70 |
| 43| 6752 | 99.26 | 56.66 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 27.54 | 8.47 | 0.46 |
| 2| 855 | 31.69 | 10.29 | 0.52 |
| 3| 982 | 33.47 | 11.45 | 0.55 |
| 5| 1315 | 35.80 | 13.48 | 0.59 |
| 10| 2029 | 45.57 | 19.57 | 0.75 |
| 35| 5991 | 98.65 | 51.17 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 877 | 36.52 | 11.59 | 0.57 |
| 3| 1053 | 39.26 | 13.03 | 0.61 |
| 5| 1356 | 43.32 | 15.48 | 0.67 |
| 10| 2052 | 54.81 | 22.03 | 0.84 |
| 30| 4917 | 98.64 | 47.53 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 26.96 | 9.05 | 0.69 |
| 2| 5917 | 34.76 | 11.63 | 0.78 |
| 3| 6069 | 44.61 | 14.99 | 0.89 |
| 4| 6175 | 48.11 | 16.14 | 0.93 |
| 5| 6547 | 65.81 | 22.23 | 1.13 |
| 6| 6692 | 74.75 | 25.22 | 1.23 |
| 7| 6615 | 74.74 | 25.04 | 1.23 |
| 8| 7034 | 95.24 | 32.19 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 20 | 1138 | 6512 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

