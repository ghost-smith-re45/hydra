--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-18 04:57:50.907042093 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.48 | 4.58 | 0.57 |
| 5| 6646 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1284 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 225 | 858 | 50.45 | 14.52 | 0.70 |
| 5 | 282 | 969 | 64.35 | 18.31 | 0.84 |
| 6 | 339 | 1081 | 71.45 | 20.42 | 0.92 |
| 7 | 396 | 1192 | 72.37 | 20.95 | 0.94 |
| 8 | 449 | 1303 | 96.72 | 27.23 | 1.19 |
| 9 | 505 | 1418 | 89.33 | 25.91 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.00 | 7.62 | 0.48 |
| 2| 1966 | 26.76 | 9.04 | 0.52 |
| 3| 2111 | 28.02 | 10.07 | 0.54 |
| 5| 2383 | 31.46 | 12.35 | 0.60 |
| 10| 3224 | 42.58 | 18.82 | 0.77 |
| 39| 7490 | 97.30 | 53.35 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 837 | 25.14 | 8.70 | 0.45 |
| 3| 932 | 27.06 | 9.88 | 0.48 |
| 5| 1197 | 29.90 | 12.01 | 0.53 |
| 10| 2015 | 40.49 | 18.32 | 0.70 |
| 40| 6495 | 99.20 | 54.59 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 27.50 | 8.46 | 0.46 |
| 2| 798 | 30.94 | 10.07 | 0.51 |
| 3| 1054 | 34.22 | 11.68 | 0.56 |
| 5| 1252 | 35.04 | 13.25 | 0.58 |
| 10| 2024 | 47.48 | 20.05 | 0.77 |
| 35| 5884 | 95.75 | 50.35 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 813 | 35.89 | 11.39 | 0.56 |
| 3| 958 | 37.95 | 12.63 | 0.59 |
| 5| 1372 | 44.04 | 15.70 | 0.68 |
| 10| 1958 | 53.38 | 21.60 | 0.82 |
| 29| 4989 | 99.26 | 47.10 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.05 | 9.07 | 0.69 |
| 2| 5939 | 35.97 | 12.08 | 0.79 |
| 3| 6188 | 46.89 | 15.85 | 0.92 |
| 4| 6258 | 55.07 | 18.53 | 1.00 |
| 5| 6430 | 64.77 | 21.82 | 1.11 |
| 6| 6552 | 71.00 | 23.92 | 1.18 |
| 7| 6735 | 80.94 | 27.25 | 1.30 |
| 8| 6926 | 93.61 | 31.59 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 20 | 1137 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1710 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7161 | 99.82 | 38.19 | 1.55 |

