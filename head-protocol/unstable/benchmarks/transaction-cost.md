--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-11 04:50:42.641908817 UTC |
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
| 1| 5837 | 10.93 | 3.49 | 0.52 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 14.84 | 4.71 | 0.58 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7646 | 29.26 | 9.23 | 0.79 |
| 43| 14279 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 42.62 | 12.26 | 0.62 |
| 4 | 226 | 858 | 52.29 | 14.97 | 0.72 |
| 5 | 282 | 969 | 56.37 | 16.34 | 0.77 |
| 6 | 337 | 1081 | 65.85 | 19.03 | 0.87 |
| 7 | 394 | 1192 | 86.21 | 24.27 | 1.07 |
| 8 | 450 | 1303 | 89.80 | 25.57 | 1.12 |
| 10 | 561 | 1525 | 96.75 | 28.04 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 1927 | 25.43 | 8.69 | 0.50 |
| 3| 2060 | 27.39 | 9.88 | 0.53 |
| 5| 2275 | 29.19 | 11.72 | 0.57 |
| 10| 3055 | 38.67 | 17.71 | 0.72 |
| 40| 7704 | 99.79 | 54.71 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.31 | 0.41 |
| 2| 801 | 25.39 | 8.76 | 0.45 |
| 3| 881 | 25.16 | 9.35 | 0.46 |
| 5| 1134 | 28.11 | 11.51 | 0.51 |
| 10| 2102 | 40.88 | 18.43 | 0.71 |
| 43| 6742 | 98.15 | 56.32 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 27.50 | 8.46 | 0.46 |
| 2| 862 | 31.62 | 10.28 | 0.52 |
| 3| 906 | 32.72 | 11.23 | 0.54 |
| 5| 1227 | 37.02 | 13.77 | 0.60 |
| 10| 2171 | 46.54 | 19.87 | 0.77 |
| 36| 5872 | 97.96 | 51.58 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 848 | 36.56 | 11.60 | 0.57 |
| 3| 965 | 37.88 | 12.61 | 0.59 |
| 5| 1212 | 42.01 | 15.08 | 0.65 |
| 10| 2070 | 54.65 | 21.99 | 0.84 |
| 29| 4928 | 98.39 | 46.82 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.08 | 9.09 | 0.69 |
| 2| 5991 | 36.98 | 12.45 | 0.80 |
| 3| 6211 | 46.77 | 15.82 | 0.92 |
| 4| 6258 | 55.09 | 18.54 | 1.00 |
| 5| 6480 | 65.46 | 22.03 | 1.12 |
| 6| 6618 | 74.70 | 25.17 | 1.23 |
| 7| 6666 | 80.51 | 27.15 | 1.29 |
| 8| 6762 | 87.80 | 29.50 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2218 | 7158 | 98.24 | 37.65 | 1.53 |

