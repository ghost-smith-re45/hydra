--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-30 09:11:03.941633269 UTC |
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
| 1| 5837 | 10.64 | 3.38 | 0.52 |
| 2| 6037 | 12.91 | 4.10 | 0.55 |
| 3| 6236 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 19.26 | 6.10 | 0.64 |
| 10| 7651 | 29.49 | 9.31 | 0.79 |
| 43| 14283 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 747 | 43.64 | 12.50 | 0.63 |
| 4 | 226 | 858 | 48.12 | 13.94 | 0.68 |
| 5 | 282 | 969 | 56.36 | 16.37 | 0.77 |
| 6 | 338 | 1081 | 66.25 | 19.10 | 0.87 |
| 7 | 397 | 1192 | 86.80 | 24.46 | 1.08 |
| 8 | 451 | 1303 | 93.76 | 26.52 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1826 | 24.37 | 7.71 | 0.48 |
| 2| 2010 | 26.76 | 9.04 | 0.52 |
| 3| 2118 | 27.94 | 10.05 | 0.54 |
| 5| 2453 | 32.11 | 12.55 | 0.61 |
| 10| 3126 | 39.73 | 18.00 | 0.74 |
| 40| 7550 | 97.22 | 54.00 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.81 | 7.37 | 0.42 |
| 2| 763 | 23.58 | 8.22 | 0.43 |
| 3| 828 | 24.13 | 9.04 | 0.45 |
| 5| 1340 | 32.38 | 12.69 | 0.56 |
| 10| 1909 | 38.46 | 17.73 | 0.67 |
| 42| 6571 | 97.03 | 55.34 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 859 | 29.94 | 9.83 | 0.50 |
| 3| 973 | 33.47 | 11.46 | 0.55 |
| 5| 1249 | 35.04 | 13.25 | 0.58 |
| 10| 2028 | 48.01 | 20.22 | 0.77 |
| 37| 6045 | 99.01 | 52.55 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 839 | 35.88 | 11.39 | 0.56 |
| 3| 1011 | 38.62 | 12.83 | 0.60 |
| 5| 1293 | 43.28 | 15.48 | 0.67 |
| 10| 2139 | 55.59 | 22.27 | 0.85 |
| 28| 4628 | 94.43 | 44.98 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.05 | 9.07 | 0.69 |
| 2| 5979 | 37.08 | 12.50 | 0.80 |
| 3| 6132 | 45.75 | 15.43 | 0.90 |
| 4| 6349 | 56.02 | 18.88 | 1.02 |
| 5| 6357 | 64.11 | 21.60 | 1.10 |
| 6| 6528 | 69.46 | 23.32 | 1.17 |
| 7| 6727 | 81.38 | 27.54 | 1.30 |
| 8| 6819 | 88.94 | 29.93 | 1.38 |
| 9| 7081 | 99.97 | 33.71 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6854 | 79.78 | 30.37 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

