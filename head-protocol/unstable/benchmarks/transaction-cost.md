--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-07 10:08:00.536880226 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6242 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 43.88 | 12.56 | 0.63 |
| 4 | 227 | 858 | 51.30 | 14.78 | 0.71 |
| 5 | 281 | 969 | 57.85 | 16.72 | 0.78 |
| 6 | 338 | 1085 | 71.64 | 20.39 | 0.92 |
| 7 | 397 | 1196 | 77.12 | 22.04 | 0.98 |
| 8 | 450 | 1303 | 86.76 | 24.79 | 1.09 |
| 9 | 505 | 1414 | 92.22 | 26.72 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.37 | 7.71 | 0.48 |
| 2| 1958 | 26.84 | 9.06 | 0.52 |
| 3| 2055 | 26.94 | 9.77 | 0.53 |
| 5| 2413 | 32.03 | 12.53 | 0.61 |
| 10| 3147 | 40.35 | 18.19 | 0.75 |
| 41| 7612 | 96.64 | 54.46 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 946 | 26.56 | 9.76 | 0.48 |
| 5| 1291 | 29.94 | 12.03 | 0.54 |
| 10| 2015 | 39.60 | 18.07 | 0.69 |
| 40| 6395 | 96.88 | 53.95 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.54 | 8.47 | 0.46 |
| 2| 821 | 29.15 | 9.59 | 0.49 |
| 3| 914 | 32.68 | 11.22 | 0.54 |
| 5| 1284 | 37.85 | 14.02 | 0.61 |
| 10| 1970 | 47.33 | 20.01 | 0.76 |
| 36| 5874 | 96.57 | 51.18 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.83 | 10.15 | 0.53 |
| 2| 760 | 35.14 | 11.16 | 0.55 |
| 3| 942 | 37.84 | 12.60 | 0.59 |
| 5| 1151 | 41.29 | 14.86 | 0.64 |
| 10| 2252 | 56.60 | 22.59 | 0.87 |
| 28| 4729 | 95.99 | 45.47 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5831 | 27.05 | 9.08 | 0.69 |
| 2| 5916 | 34.83 | 11.65 | 0.78 |
| 3| 5947 | 40.44 | 13.51 | 0.84 |
| 4| 6186 | 54.30 | 18.27 | 0.99 |
| 5| 6353 | 64.74 | 21.74 | 1.11 |
| 6| 6671 | 75.38 | 25.44 | 1.24 |
| 7| 6655 | 83.42 | 28.05 | 1.32 |
| 8| 6881 | 88.58 | 29.81 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 284 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

