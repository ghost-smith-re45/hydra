--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-20 08:54:10.167608433 UTC |
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
| 1| 5836 | 11.04 | 3.52 | 0.52 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.98 | 4.75 | 0.58 |
| 5| 6641 | 18.60 | 5.87 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1284 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 169 | 747 | 43.83 | 12.55 | 0.63 |
| 4 | 226 | 858 | 48.08 | 13.96 | 0.68 |
| 5 | 283 | 969 | 55.85 | 16.21 | 0.76 |
| 6 | 340 | 1081 | 75.16 | 21.23 | 0.96 |
| 7 | 396 | 1192 | 72.66 | 21.11 | 0.94 |
| 8 | 450 | 1303 | 87.38 | 25.04 | 1.09 |
| 9 | 505 | 1414 | 88.51 | 25.66 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.37 | 7.71 | 0.48 |
| 2| 1967 | 26.55 | 9.00 | 0.52 |
| 3| 2122 | 28.77 | 10.27 | 0.55 |
| 5| 2501 | 33.34 | 12.89 | 0.62 |
| 10| 3074 | 40.03 | 18.08 | 0.74 |
| 38| 7154 | 91.08 | 50.94 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.80 | 7.37 | 0.41 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 904 | 25.74 | 9.52 | 0.47 |
| 5| 1337 | 32.41 | 12.71 | 0.56 |
| 10| 2043 | 39.47 | 18.01 | 0.69 |
| 41| 6550 | 96.15 | 54.41 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.09 | 8.89 | 0.48 |
| 2| 771 | 28.51 | 9.39 | 0.48 |
| 3| 961 | 33.36 | 11.42 | 0.54 |
| 5| 1308 | 37.99 | 14.08 | 0.62 |
| 10| 2011 | 44.96 | 19.38 | 0.74 |
| 36| 5835 | 96.55 | 51.15 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.79 | 10.15 | 0.53 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 1001 | 38.59 | 12.82 | 0.60 |
| 5| 1201 | 41.97 | 15.07 | 0.65 |
| 10| 2090 | 54.88 | 22.05 | 0.84 |
| 30| 4955 | 99.44 | 47.77 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5970 | 35.96 | 12.08 | 0.79 |
| 3| 6035 | 45.00 | 15.11 | 0.89 |
| 4| 6208 | 53.83 | 18.08 | 0.99 |
| 5| 6524 | 65.82 | 22.24 | 1.13 |
| 6| 6481 | 69.84 | 23.44 | 1.17 |
| 7| 6517 | 77.38 | 25.90 | 1.25 |
| 8| 6862 | 91.86 | 30.94 | 1.42 |
| 10| 6921 | 98.60 | 33.18 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.59 | 7.34 | 0.64 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.47 | 22.36 | 1.08 |
| 10 | 30 | 1711 | 6858 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2219 | 7158 | 98.05 | 37.58 | 1.53 |

