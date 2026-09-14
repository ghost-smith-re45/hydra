--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-14 10:52:13.960757332 UTC |
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
| 1| 5838 | 10.85 | 3.45 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7650 | 29.09 | 9.17 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 42.85 | 12.34 | 0.62 |
| 4 | 226 | 858 | 48.42 | 14.07 | 0.68 |
| 5 | 284 | 969 | 64.23 | 18.22 | 0.84 |
| 6 | 340 | 1081 | 75.04 | 21.24 | 0.96 |
| 7 | 394 | 1192 | 74.19 | 21.43 | 0.96 |
| 8 | 450 | 1303 | 84.70 | 24.25 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2109 | 28.13 | 10.10 | 0.54 |
| 5| 2483 | 33.63 | 12.96 | 0.62 |
| 10| 2975 | 37.86 | 17.47 | 0.71 |
| 40| 7468 | 96.09 | 53.67 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.77 | 7.36 | 0.42 |
| 2| 770 | 24.31 | 8.47 | 0.44 |
| 3| 886 | 25.85 | 9.55 | 0.47 |
| 5| 1240 | 29.08 | 11.77 | 0.52 |
| 10| 2005 | 38.70 | 17.79 | 0.68 |
| 41| 6723 | 97.51 | 54.85 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.51 | 8.47 | 0.46 |
| 2| 791 | 30.94 | 10.07 | 0.51 |
| 3| 945 | 30.94 | 10.75 | 0.52 |
| 5| 1303 | 35.38 | 13.35 | 0.59 |
| 10| 2060 | 48.31 | 20.31 | 0.78 |
| 37| 6067 | 98.84 | 52.47 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 33.12 | 9.94 | 0.52 |
| 2| 837 | 35.85 | 11.38 | 0.56 |
| 3| 984 | 38.55 | 12.81 | 0.60 |
| 5| 1278 | 42.72 | 15.30 | 0.66 |
| 10| 1971 | 53.20 | 21.55 | 0.82 |
| 29| 4959 | 98.50 | 46.87 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 26.92 | 9.05 | 0.69 |
| 2| 5943 | 36.04 | 12.10 | 0.79 |
| 3| 6052 | 45.23 | 15.19 | 0.89 |
| 4| 6205 | 51.57 | 17.34 | 0.96 |
| 5| 6448 | 63.85 | 21.51 | 1.10 |
| 6| 6587 | 72.35 | 24.39 | 1.20 |
| 7| 6700 | 80.24 | 26.97 | 1.29 |
| 8| 6642 | 84.23 | 28.19 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 58 | 5870 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1142 | 6516 | 59.98 | 22.53 | 1.08 |
| 10 | 38 | 2164 | 7126 | 95.56 | 36.62 | 1.50 |

