--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-05 08:47:20.247729759 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.92 | 4.11 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.71 | 5.91 | 0.64 |
| 10| 7644 | 29.49 | 9.31 | 0.79 |
| 43| 14281 | 99.40 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10039 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.39 | 9.43 | 0.51 |
| 3 | 171 | 747 | 39.96 | 11.62 | 0.59 |
| 4 | 227 | 862 | 50.69 | 14.56 | 0.70 |
| 5 | 282 | 969 | 59.20 | 16.98 | 0.79 |
| 6 | 338 | 1081 | 72.92 | 20.66 | 0.94 |
| 7 | 394 | 1192 | 75.02 | 21.68 | 0.97 |
| 8 | 451 | 1303 | 85.75 | 24.66 | 1.08 |
| 10 | 563 | 1525 | 99.94 | 28.80 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 22.92 | 7.32 | 0.47 |
| 2| 1883 | 24.40 | 8.39 | 0.49 |
| 3| 2127 | 27.98 | 10.06 | 0.54 |
| 5| 2317 | 30.16 | 12.00 | 0.58 |
| 10| 3230 | 41.72 | 18.57 | 0.76 |
| 40| 7376 | 95.22 | 53.42 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.81 | 7.37 | 0.42 |
| 2| 696 | 22.58 | 7.96 | 0.42 |
| 3| 872 | 25.12 | 9.33 | 0.46 |
| 5| 1182 | 28.12 | 11.50 | 0.51 |
| 10| 2031 | 41.15 | 18.47 | 0.71 |
| 40| 6651 | 98.54 | 54.44 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 1074 | 32.32 | 11.18 | 0.54 |
| 5| 1160 | 33.66 | 12.83 | 0.57 |
| 10| 1996 | 44.33 | 19.19 | 0.73 |
| 37| 6135 | 99.21 | 52.64 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 846 | 36.56 | 11.60 | 0.57 |
| 3| 991 | 38.66 | 12.84 | 0.60 |
| 5| 1259 | 42.61 | 15.27 | 0.66 |
| 10| 2029 | 54.17 | 21.84 | 0.83 |
| 30| 4868 | 99.57 | 47.74 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.08 | 9.08 | 0.69 |
| 2| 5891 | 35.02 | 11.72 | 0.78 |
| 3| 6085 | 44.99 | 15.12 | 0.89 |
| 4| 6396 | 56.56 | 19.15 | 1.03 |
| 5| 6355 | 60.10 | 20.18 | 1.06 |
| 6| 6473 | 66.72 | 22.42 | 1.14 |
| 7| 6693 | 79.75 | 26.89 | 1.28 |
| 8| 6721 | 85.51 | 28.76 | 1.34 |
| 9| 6925 | 98.18 | 32.97 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6854 | 79.15 | 30.16 | 1.31 |
| 10 | 37 | 2105 | 7091 | 95.28 | 36.42 | 1.49 |

