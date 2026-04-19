--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-19 07:17:55.250572093 UTC |
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
| 1| 5840 | 10.47 | 3.32 | 0.52 |
| 2| 6035 | 12.75 | 4.04 | 0.55 |
| 3| 6243 | 14.29 | 4.51 | 0.57 |
| 5| 6643 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.79 | 12.52 | 0.63 |
| 4 | 227 | 858 | 53.74 | 15.31 | 0.73 |
| 5 | 285 | 969 | 60.75 | 17.35 | 0.81 |
| 6 | 336 | 1081 | 64.51 | 18.72 | 0.85 |
| 7 | 392 | 1192 | 82.95 | 23.58 | 1.04 |
| 8 | 451 | 1303 | 94.02 | 26.53 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1916 | 25.84 | 8.78 | 0.51 |
| 3| 2101 | 28.47 | 10.18 | 0.55 |
| 5| 2401 | 31.78 | 12.45 | 0.60 |
| 10| 3223 | 42.41 | 18.75 | 0.77 |
| 40| 7779 | 99.88 | 54.76 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.77 | 7.36 | 0.42 |
| 2| 697 | 22.62 | 7.95 | 0.42 |
| 3| 967 | 26.92 | 9.85 | 0.48 |
| 5| 1236 | 28.97 | 11.74 | 0.52 |
| 10| 1861 | 36.99 | 17.32 | 0.66 |
| 41| 6561 | 98.53 | 55.09 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 27.51 | 8.47 | 0.46 |
| 2| 840 | 31.58 | 10.27 | 0.52 |
| 3| 906 | 30.26 | 10.55 | 0.51 |
| 5| 1307 | 35.60 | 13.43 | 0.59 |
| 10| 1954 | 46.46 | 19.76 | 0.75 |
| 37| 6093 | 99.73 | 52.79 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.83 | 10.16 | 0.53 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 1009 | 38.55 | 12.81 | 0.60 |
| 5| 1398 | 43.99 | 15.69 | 0.68 |
| 10| 2168 | 55.67 | 22.29 | 0.86 |
| 30| 5002 | 99.50 | 47.78 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5982 | 37.08 | 12.48 | 0.80 |
| 3| 6109 | 45.47 | 15.34 | 0.90 |
| 4| 6301 | 54.82 | 18.47 | 1.00 |
| 5| 6473 | 64.81 | 21.85 | 1.12 |
| 6| 6530 | 72.00 | 24.21 | 1.19 |
| 7| 6810 | 86.26 | 29.15 | 1.36 |
| 8| 6800 | 88.73 | 29.82 | 1.38 |
| 9| 6916 | 94.59 | 31.81 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.98 | 6.00 | 0.60 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1710 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

