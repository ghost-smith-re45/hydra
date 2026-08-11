--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-11 06:28:13.306560925 UTC |
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
| 1| 5837 | 10.26 | 3.25 | 0.51 |
| 2| 6038 | 12.72 | 4.03 | 0.55 |
| 3| 6239 | 14.47 | 4.57 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.31 | 9.25 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 40.16 | 11.66 | 0.59 |
| 4 | 226 | 858 | 49.69 | 14.35 | 0.69 |
| 5 | 284 | 969 | 64.27 | 18.23 | 0.84 |
| 6 | 339 | 1081 | 70.07 | 20.05 | 0.91 |
| 7 | 394 | 1192 | 74.92 | 21.61 | 0.96 |
| 8 | 453 | 1303 | 98.37 | 27.58 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.29 | 7.69 | 0.48 |
| 2| 1880 | 24.43 | 8.40 | 0.49 |
| 3| 2110 | 28.30 | 10.14 | 0.54 |
| 5| 2468 | 31.88 | 12.49 | 0.61 |
| 10| 3088 | 39.90 | 18.04 | 0.74 |
| 42| 7813 | 99.97 | 56.07 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.84 | 7.39 | 0.42 |
| 2| 736 | 23.66 | 8.26 | 0.43 |
| 3| 939 | 26.98 | 9.88 | 0.48 |
| 5| 1276 | 30.15 | 12.07 | 0.54 |
| 10| 1962 | 38.82 | 17.83 | 0.68 |
| 39| 6379 | 97.42 | 53.46 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 27.50 | 8.46 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 868 | 31.97 | 11.00 | 0.53 |
| 5| 1196 | 36.42 | 13.59 | 0.60 |
| 10| 1977 | 44.08 | 19.12 | 0.73 |
| 37| 5913 | 97.94 | 52.21 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 1064 | 39.22 | 13.02 | 0.61 |
| 5| 1283 | 42.65 | 15.28 | 0.66 |
| 10| 2052 | 53.99 | 21.79 | 0.83 |
| 29| 4876 | 97.45 | 46.53 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 27.08 | 9.09 | 0.69 |
| 2| 5925 | 36.00 | 12.08 | 0.79 |
| 3| 6060 | 44.81 | 15.05 | 0.89 |
| 4| 6282 | 55.09 | 18.54 | 1.01 |
| 5| 6560 | 66.20 | 22.37 | 1.14 |
| 6| 6533 | 72.88 | 24.58 | 1.20 |
| 7| 6744 | 84.77 | 28.59 | 1.34 |
| 8| 6848 | 86.53 | 29.07 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1711 | 6857 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |

