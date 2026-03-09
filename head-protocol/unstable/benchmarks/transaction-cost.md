--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-09 06:40:36.545019622 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6041 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6645 | 18.81 | 5.94 | 0.64 |
| 10| 7646 | 29.49 | 9.31 | 0.79 |
| 43| 14286 | 99.33 | 31.06 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 41.49 | 11.99 | 0.60 |
| 4 | 226 | 858 | 50.88 | 14.65 | 0.70 |
| 5 | 283 | 969 | 59.89 | 17.25 | 0.80 |
| 6 | 340 | 1081 | 69.70 | 19.96 | 0.90 |
| 7 | 394 | 1192 | 77.18 | 22.24 | 0.99 |
| 8 | 450 | 1303 | 97.99 | 27.43 | 1.20 |
| 9 | 505 | 1414 | 95.73 | 27.28 | 1.18 |
| 10 | 562 | 1525 | 98.36 | 28.61 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.37 | 7.71 | 0.48 |
| 2| 1930 | 25.84 | 8.78 | 0.51 |
| 3| 2084 | 26.94 | 9.77 | 0.53 |
| 5| 2434 | 32.63 | 12.69 | 0.61 |
| 10| 3310 | 44.00 | 19.19 | 0.79 |
| 40| 7650 | 97.88 | 54.17 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.81 | 7.37 | 0.42 |
| 2| 843 | 25.44 | 8.77 | 0.46 |
| 3| 919 | 26.63 | 9.78 | 0.48 |
| 5| 1242 | 30.53 | 12.21 | 0.54 |
| 10| 2049 | 39.57 | 18.04 | 0.69 |
| 43| 6742 | 98.22 | 56.37 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.54 | 8.47 | 0.46 |
| 2| 814 | 30.98 | 10.08 | 0.51 |
| 3| 1066 | 32.33 | 11.18 | 0.54 |
| 5| 1378 | 36.47 | 13.68 | 0.60 |
| 10| 1999 | 46.79 | 19.84 | 0.76 |
| 37| 6128 | 99.86 | 52.81 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 866 | 36.60 | 11.61 | 0.57 |
| 3| 961 | 37.91 | 12.62 | 0.59 |
| 5| 1315 | 43.43 | 15.51 | 0.67 |
| 10| 2034 | 53.89 | 21.76 | 0.83 |
| 29| 4741 | 96.57 | 46.28 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.96 | 9.06 | 0.69 |
| 2| 5916 | 34.83 | 11.65 | 0.78 |
| 3| 6082 | 45.08 | 15.16 | 0.89 |
| 4| 6095 | 49.27 | 16.51 | 0.94 |
| 5| 6553 | 66.63 | 22.55 | 1.14 |
| 6| 6507 | 70.66 | 23.80 | 1.18 |
| 7| 6580 | 75.79 | 25.46 | 1.24 |
| 8| 6967 | 92.39 | 31.19 | 1.43 |
| 9| 7121 | 99.94 | 33.73 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1709 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2222 | 7162 | 98.05 | 37.58 | 1.53 |

