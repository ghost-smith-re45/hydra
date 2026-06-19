--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-19 10:25:21.864258448 UTC |
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
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7651 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 751 | 40.10 | 11.64 | 0.59 |
| 4 | 227 | 858 | 50.83 | 14.62 | 0.70 |
| 5 | 281 | 969 | 58.71 | 16.89 | 0.79 |
| 6 | 338 | 1081 | 75.26 | 21.22 | 0.96 |
| 7 | 394 | 1192 | 71.97 | 20.94 | 0.94 |
| 8 | 450 | 1303 | 87.51 | 25.02 | 1.09 |
| 9 | 504 | 1414 | 92.03 | 26.57 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1955 | 25.76 | 8.76 | 0.51 |
| 3| 2054 | 27.28 | 9.85 | 0.53 |
| 5| 2450 | 32.20 | 12.57 | 0.61 |
| 10| 3068 | 39.90 | 18.04 | 0.74 |
| 38| 7327 | 94.14 | 51.79 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 22.81 | 7.38 | 0.42 |
| 2| 743 | 24.35 | 8.47 | 0.44 |
| 3| 829 | 24.02 | 9.01 | 0.45 |
| 5| 1370 | 32.82 | 12.83 | 0.57 |
| 10| 1933 | 37.50 | 17.46 | 0.66 |
| 41| 6553 | 96.59 | 54.56 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 771 | 30.91 | 10.06 | 0.51 |
| 3| 924 | 32.75 | 11.24 | 0.54 |
| 5| 1399 | 36.43 | 13.67 | 0.60 |
| 10| 2010 | 44.98 | 19.39 | 0.74 |
| 36| 5901 | 97.45 | 51.47 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.83 | 10.15 | 0.53 |
| 2| 761 | 35.14 | 11.16 | 0.55 |
| 3| 940 | 37.95 | 12.63 | 0.59 |
| 5| 1200 | 42.01 | 15.08 | 0.65 |
| 10| 1927 | 52.56 | 21.36 | 0.81 |
| 28| 4717 | 95.22 | 45.27 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.08 | 9.09 | 0.69 |
| 2| 5997 | 37.08 | 12.49 | 0.80 |
| 3| 6176 | 45.72 | 15.41 | 0.90 |
| 4| 6279 | 54.97 | 18.52 | 1.00 |
| 5| 6484 | 66.64 | 22.50 | 1.14 |
| 6| 6424 | 65.73 | 22.00 | 1.12 |
| 7| 6499 | 74.51 | 25.00 | 1.22 |
| 8| 6800 | 87.46 | 29.40 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 60.87 | 22.83 | 1.09 |
| 10 | 37 | 2105 | 7091 | 95.21 | 36.40 | 1.49 |

