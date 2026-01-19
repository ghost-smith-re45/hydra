--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-19 05:07:59.155705749 UTC |
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
| 1| 5840 | 10.40 | 3.30 | 0.52 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7651 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 43.75 | 12.55 | 0.63 |
| 4 | 227 | 858 | 49.42 | 14.25 | 0.69 |
| 5 | 283 | 969 | 56.46 | 16.36 | 0.77 |
| 6 | 338 | 1081 | 65.93 | 19.06 | 0.87 |
| 7 | 394 | 1196 | 80.20 | 22.87 | 1.02 |
| 8 | 448 | 1303 | 81.27 | 23.58 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 23.92 | 7.60 | 0.48 |
| 2| 1924 | 25.39 | 8.68 | 0.50 |
| 3| 2017 | 26.32 | 9.58 | 0.52 |
| 5| 2436 | 32.25 | 12.58 | 0.61 |
| 10| 3125 | 40.47 | 18.20 | 0.75 |
| 39| 7336 | 95.53 | 52.81 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.84 | 7.37 | 0.41 |
| 2| 744 | 24.08 | 8.40 | 0.44 |
| 3| 984 | 28.11 | 10.17 | 0.49 |
| 5| 1205 | 29.14 | 11.80 | 0.52 |
| 10| 2058 | 41.95 | 18.70 | 0.71 |
| 40| 6439 | 97.53 | 54.13 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 27.54 | 8.47 | 0.46 |
| 2| 796 | 30.95 | 10.07 | 0.51 |
| 3| 910 | 32.75 | 11.24 | 0.54 |
| 5| 1179 | 36.31 | 13.56 | 0.59 |
| 10| 2049 | 44.86 | 19.36 | 0.74 |
| 34| 5792 | 95.62 | 49.69 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.83 | 10.15 | 0.53 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 948 | 37.88 | 12.61 | 0.59 |
| 5| 1158 | 41.26 | 14.85 | 0.64 |
| 10| 2116 | 55.48 | 22.24 | 0.85 |
| 28| 5050 | 99.23 | 46.49 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.12 | 9.10 | 0.69 |
| 2| 5936 | 35.81 | 12.05 | 0.79 |
| 3| 6038 | 41.55 | 13.91 | 0.85 |
| 4| 6293 | 54.77 | 18.43 | 1.00 |
| 5| 6453 | 64.71 | 21.87 | 1.11 |
| 6| 6612 | 72.23 | 24.31 | 1.20 |
| 7| 6653 | 76.47 | 25.68 | 1.25 |
| 8| 6751 | 88.64 | 29.76 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.15 | 7.19 | 0.63 |
| 10 | 20 | 1140 | 6515 | 60.42 | 22.68 | 1.09 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

