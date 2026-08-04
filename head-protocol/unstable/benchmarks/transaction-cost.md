--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-04 07:42:10.129613187 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6042 | 12.67 | 4.01 | 0.55 |
| 3| 6240 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7651 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 42.34 | 12.17 | 0.61 |
| 4 | 225 | 858 | 53.57 | 15.25 | 0.73 |
| 5 | 282 | 969 | 62.00 | 17.68 | 0.82 |
| 6 | 339 | 1081 | 65.20 | 18.96 | 0.86 |
| 7 | 395 | 1192 | 81.27 | 23.22 | 1.03 |
| 8 | 450 | 1303 | 82.88 | 23.96 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.29 | 7.69 | 0.48 |
| 2| 1927 | 25.88 | 8.79 | 0.51 |
| 3| 2103 | 27.93 | 10.05 | 0.54 |
| 5| 2420 | 31.99 | 12.52 | 0.61 |
| 10| 3282 | 42.78 | 18.86 | 0.78 |
| 41| 7783 | 99.71 | 55.36 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.54 | 7.30 | 0.41 |
| 2| 741 | 24.04 | 8.40 | 0.44 |
| 3| 991 | 27.72 | 10.08 | 0.49 |
| 5| 1266 | 30.93 | 12.32 | 0.54 |
| 10| 1972 | 37.89 | 17.57 | 0.67 |
| 45| 6891 | 98.97 | 57.89 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 964 | 33.47 | 11.46 | 0.55 |
| 5| 1300 | 37.81 | 14.01 | 0.61 |
| 10| 2129 | 46.40 | 19.82 | 0.76 |
| 37| 6077 | 99.80 | 52.77 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 811 | 35.89 | 11.39 | 0.56 |
| 3| 1065 | 39.30 | 13.04 | 0.61 |
| 5| 1246 | 42.68 | 15.29 | 0.66 |
| 10| 1926 | 52.52 | 21.35 | 0.81 |
| 28| 4703 | 95.55 | 45.36 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.92 | 9.04 | 0.69 |
| 2| 5981 | 37.13 | 12.50 | 0.80 |
| 3| 6122 | 45.93 | 15.45 | 0.90 |
| 4| 6287 | 54.90 | 18.48 | 1.00 |
| 5| 6421 | 61.70 | 20.73 | 1.08 |
| 6| 6523 | 70.21 | 23.62 | 1.17 |
| 7| 6663 | 84.13 | 28.35 | 1.33 |
| 8| 6844 | 93.05 | 31.37 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6003 | 27.58 | 9.82 | 0.71 |
| 10 | 20 | 1138 | 6512 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1708 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2216 | 7156 | 98.49 | 37.73 | 1.53 |

