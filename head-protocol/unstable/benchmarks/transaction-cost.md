--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-03 08:37:30.027868116 UTC |
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
| 1| 5837 | 10.36 | 3.28 | 0.51 |
| 2| 6037 | 12.99 | 4.13 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6646 | 18.93 | 5.98 | 0.64 |
| 10| 7651 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 42.66 | 12.27 | 0.62 |
| 4 | 226 | 858 | 51.96 | 14.86 | 0.71 |
| 5 | 282 | 969 | 56.22 | 16.33 | 0.76 |
| 6 | 338 | 1081 | 75.01 | 21.23 | 0.96 |
| 7 | 393 | 1192 | 78.11 | 22.29 | 0.99 |
| 8 | 449 | 1303 | 96.52 | 27.18 | 1.18 |
| 9 | 504 | 1418 | 87.87 | 25.50 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1981 | 26.63 | 9.02 | 0.52 |
| 3| 2107 | 28.42 | 10.17 | 0.55 |
| 5| 2367 | 31.05 | 12.25 | 0.59 |
| 10| 3238 | 43.25 | 18.98 | 0.78 |
| 42| 7862 | 99.32 | 55.94 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 801 | 25.49 | 8.78 | 0.45 |
| 3| 904 | 25.78 | 9.54 | 0.47 |
| 5| 1194 | 29.14 | 11.80 | 0.52 |
| 10| 1958 | 38.45 | 17.72 | 0.67 |
| 42| 6749 | 98.52 | 55.75 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 708 | 27.50 | 8.46 | 0.46 |
| 2| 819 | 29.18 | 9.60 | 0.49 |
| 3| 951 | 30.86 | 10.73 | 0.52 |
| 5| 1206 | 36.35 | 13.57 | 0.59 |
| 10| 1981 | 47.47 | 20.05 | 0.77 |
| 36| 5886 | 97.71 | 51.50 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.83 | 10.15 | 0.53 |
| 2| 823 | 35.92 | 11.40 | 0.56 |
| 3| 987 | 38.59 | 12.82 | 0.60 |
| 5| 1203 | 41.86 | 15.04 | 0.65 |
| 10| 1906 | 52.78 | 21.41 | 0.81 |
| 29| 4938 | 99.30 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.13 | 9.11 | 0.69 |
| 2| 5893 | 34.87 | 11.67 | 0.78 |
| 3| 6099 | 45.03 | 15.12 | 0.89 |
| 4| 6332 | 55.92 | 18.85 | 1.02 |
| 5| 6383 | 63.38 | 21.27 | 1.10 |
| 6| 6485 | 70.93 | 23.82 | 1.18 |
| 7| 6642 | 78.32 | 26.29 | 1.26 |
| 8| 7011 | 91.63 | 30.89 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 571 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1709 | 6855 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

