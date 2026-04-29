--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-29 07:35:25.173682968 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 15.05 | 4.78 | 0.58 |
| 5| 6640 | 18.79 | 5.94 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 40.20 | 11.70 | 0.59 |
| 4 | 227 | 858 | 53.87 | 15.37 | 0.73 |
| 5 | 283 | 969 | 64.21 | 18.21 | 0.84 |
| 6 | 338 | 1081 | 75.23 | 21.25 | 0.96 |
| 7 | 394 | 1192 | 80.56 | 22.92 | 1.02 |
| 8 | 448 | 1303 | 80.89 | 23.44 | 1.03 |
| 9 | 505 | 1414 | 93.30 | 26.75 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1883 | 24.80 | 8.49 | 0.49 |
| 3| 2015 | 26.32 | 9.58 | 0.52 |
| 5| 2373 | 31.49 | 12.36 | 0.60 |
| 10| 3192 | 41.42 | 18.49 | 0.76 |
| 41| 7736 | 99.42 | 55.24 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.84 | 7.38 | 0.42 |
| 2| 703 | 22.62 | 7.96 | 0.42 |
| 3| 914 | 26.12 | 9.61 | 0.47 |
| 5| 1270 | 30.11 | 12.06 | 0.54 |
| 10| 2023 | 39.71 | 18.09 | 0.69 |
| 40| 6456 | 95.90 | 53.73 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 868 | 32.01 | 11.01 | 0.53 |
| 5| 1279 | 35.05 | 13.25 | 0.59 |
| 10| 1972 | 46.54 | 19.78 | 0.76 |
| 36| 6048 | 97.92 | 51.61 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.15 | 0.53 |
| 2| 818 | 35.85 | 11.38 | 0.56 |
| 3| 937 | 37.91 | 12.62 | 0.59 |
| 5| 1385 | 43.92 | 15.67 | 0.68 |
| 10| 2175 | 55.21 | 22.17 | 0.85 |
| 29| 4926 | 99.06 | 47.01 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.05 | 9.07 | 0.69 |
| 2| 5871 | 32.61 | 10.87 | 0.75 |
| 3| 6116 | 46.04 | 15.51 | 0.90 |
| 4| 6166 | 50.55 | 16.94 | 0.95 |
| 5| 6590 | 67.29 | 22.77 | 1.15 |
| 6| 6483 | 69.31 | 23.30 | 1.16 |
| 7| 6653 | 80.91 | 27.22 | 1.29 |
| 8| 7048 | 94.53 | 31.95 | 1.45 |
| 9| 6852 | 92.91 | 31.17 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 39 | 2223 | 7163 | 98.93 | 37.88 | 1.54 |

