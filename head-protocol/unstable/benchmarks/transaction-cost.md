--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-01 06:39:24.174396311 UTC |
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
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.90 | 4.72 | 0.58 |
| 5| 6641 | 19.19 | 6.08 | 0.64 |
| 10| 7650 | 29.38 | 9.27 | 0.79 |
| 43| 14281 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 747 | 41.49 | 11.99 | 0.60 |
| 4 | 227 | 858 | 50.87 | 14.63 | 0.70 |
| 5 | 282 | 969 | 59.25 | 17.03 | 0.79 |
| 6 | 340 | 1081 | 71.74 | 20.41 | 0.92 |
| 7 | 394 | 1192 | 76.36 | 21.91 | 0.98 |
| 8 | 448 | 1303 | 81.59 | 23.71 | 1.04 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1924 | 25.47 | 8.69 | 0.50 |
| 3| 2172 | 29.62 | 10.50 | 0.56 |
| 5| 2344 | 30.37 | 12.05 | 0.59 |
| 10| 3058 | 38.64 | 17.70 | 0.72 |
| 40| 7580 | 97.16 | 53.96 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.84 | 7.40 | 0.42 |
| 2| 805 | 25.39 | 8.77 | 0.45 |
| 3| 854 | 24.11 | 9.04 | 0.45 |
| 5| 1184 | 29.18 | 11.81 | 0.52 |
| 10| 1864 | 36.37 | 17.14 | 0.65 |
| 40| 6607 | 99.48 | 54.70 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 855 | 29.90 | 9.82 | 0.50 |
| 3| 1056 | 31.91 | 11.05 | 0.53 |
| 5| 1377 | 36.32 | 13.64 | 0.60 |
| 10| 1865 | 42.62 | 18.68 | 0.71 |
| 36| 5921 | 97.62 | 51.48 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 822 | 35.85 | 11.38 | 0.56 |
| 3| 948 | 37.88 | 12.61 | 0.59 |
| 5| 1219 | 41.97 | 15.07 | 0.65 |
| 10| 1967 | 53.39 | 21.60 | 0.82 |
| 28| 4837 | 97.76 | 46.01 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 26.97 | 9.06 | 0.69 |
| 2| 5961 | 35.91 | 12.05 | 0.79 |
| 3| 6166 | 46.85 | 15.83 | 0.91 |
| 4| 6307 | 56.19 | 18.93 | 1.02 |
| 5| 6346 | 62.94 | 21.15 | 1.09 |
| 6| 6695 | 75.69 | 25.65 | 1.24 |
| 7| 6630 | 79.75 | 26.83 | 1.28 |
| 8| 7039 | 95.62 | 32.47 | 1.47 |
| 9| 6898 | 97.49 | 32.77 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

