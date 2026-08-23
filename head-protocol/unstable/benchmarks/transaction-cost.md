--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-23 05:56:20.424116704 UTC |
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
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6643 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 58 | 526 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.56 | 12.27 | 0.62 |
| 4 | 227 | 858 | 53.69 | 15.31 | 0.73 |
| 5 | 282 | 969 | 57.78 | 16.70 | 0.78 |
| 6 | 339 | 1081 | 70.26 | 20.13 | 0.91 |
| 7 | 394 | 1192 | 76.25 | 21.84 | 0.98 |
| 8 | 451 | 1307 | 98.75 | 27.72 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1931 | 25.84 | 8.78 | 0.51 |
| 3| 2119 | 27.94 | 10.05 | 0.54 |
| 5| 2408 | 32.31 | 12.60 | 0.61 |
| 10| 3192 | 42.11 | 18.66 | 0.77 |
| 40| 7580 | 99.39 | 54.58 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 837 | 25.10 | 8.69 | 0.45 |
| 3| 1041 | 28.21 | 10.20 | 0.50 |
| 5| 1294 | 31.83 | 12.56 | 0.55 |
| 10| 1928 | 38.31 | 17.70 | 0.67 |
| 43| 6960 | 99.24 | 56.65 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 29.17 | 8.91 | 0.48 |
| 2| 782 | 30.94 | 10.07 | 0.51 |
| 3| 864 | 32.08 | 11.03 | 0.53 |
| 5| 1260 | 37.62 | 13.97 | 0.61 |
| 10| 2041 | 45.05 | 19.41 | 0.74 |
| 34| 5620 | 98.02 | 50.21 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 875 | 36.64 | 11.62 | 0.57 |
| 3| 967 | 37.80 | 12.59 | 0.59 |
| 5| 1235 | 41.89 | 15.05 | 0.65 |
| 10| 2195 | 56.23 | 22.47 | 0.86 |
| 29| 4826 | 97.53 | 46.55 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5941 | 35.99 | 12.10 | 0.79 |
| 3| 6236 | 47.05 | 15.94 | 0.92 |
| 4| 6259 | 54.73 | 18.44 | 1.00 |
| 5| 6355 | 60.27 | 20.28 | 1.06 |
| 6| 6533 | 69.62 | 23.45 | 1.17 |
| 7| 6643 | 77.96 | 26.19 | 1.26 |
| 8| 7006 | 95.78 | 32.37 | 1.47 |
| 9| 6895 | 97.10 | 32.69 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.52 | 6.86 | 0.62 |
| 10 | 10 | 569 | 6173 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1139 | 6514 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1706 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2160 | 7122 | 96.44 | 36.92 | 1.51 |

