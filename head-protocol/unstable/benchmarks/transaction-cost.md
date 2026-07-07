--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-07 08:57:43.617763469 UTC |
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
| 1| 5834 | 10.93 | 3.49 | 0.52 |
| 2| 6041 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.88 | 4.72 | 0.58 |
| 5| 6638 | 19.10 | 6.05 | 0.64 |
| 10| 7644 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 43.68 | 12.51 | 0.63 |
| 4 | 227 | 858 | 48.12 | 13.94 | 0.68 |
| 5 | 282 | 969 | 56.02 | 16.25 | 0.76 |
| 6 | 340 | 1081 | 73.08 | 20.69 | 0.94 |
| 7 | 394 | 1192 | 84.49 | 23.94 | 1.06 |
| 8 | 450 | 1303 | 92.23 | 26.21 | 1.14 |
| 9 | 504 | 1414 | 93.85 | 27.00 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1982 | 26.91 | 9.08 | 0.52 |
| 3| 2065 | 27.31 | 9.86 | 0.53 |
| 5| 2389 | 30.96 | 12.23 | 0.59 |
| 10| 3145 | 40.38 | 18.20 | 0.75 |
| 41| 7825 | 99.88 | 55.39 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.80 | 7.38 | 0.41 |
| 2| 773 | 23.59 | 8.23 | 0.43 |
| 3| 963 | 27.08 | 9.89 | 0.48 |
| 5| 1300 | 31.02 | 12.33 | 0.55 |
| 10| 2111 | 40.89 | 18.42 | 0.71 |
| 40| 6571 | 98.90 | 54.48 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 713 | 27.51 | 8.47 | 0.46 |
| 2| 804 | 30.98 | 10.08 | 0.51 |
| 3| 952 | 33.36 | 11.43 | 0.54 |
| 5| 1209 | 34.22 | 13.01 | 0.57 |
| 10| 1938 | 47.02 | 19.92 | 0.76 |
| 37| 6013 | 98.10 | 52.29 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.79 | 10.15 | 0.53 |
| 2| 810 | 35.92 | 11.40 | 0.56 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1260 | 42.64 | 15.28 | 0.66 |
| 10| 2158 | 55.70 | 22.31 | 0.86 |
| 29| 4875 | 98.03 | 46.74 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5784 | 26.97 | 9.05 | 0.69 |
| 2| 5935 | 35.99 | 12.10 | 0.79 |
| 3| 6167 | 46.78 | 15.83 | 0.91 |
| 4| 6133 | 47.63 | 15.93 | 0.92 |
| 5| 6454 | 62.73 | 21.14 | 1.09 |
| 6| 6439 | 68.16 | 22.84 | 1.15 |
| 7| 6676 | 80.65 | 27.11 | 1.29 |
| 8| 6864 | 89.45 | 30.10 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 567 | 6172 | 39.69 | 14.52 | 0.85 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2159 | 7121 | 96.88 | 37.08 | 1.51 |

