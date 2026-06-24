--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-24 08:57:29.219812808 UTC |
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
| 1| 5836 | 10.66 | 3.39 | 0.52 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 15.05 | 4.78 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7651 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 751 | 42.66 | 12.27 | 0.62 |
| 4 | 227 | 858 | 49.10 | 14.20 | 0.69 |
| 5 | 282 | 969 | 57.81 | 16.65 | 0.78 |
| 6 | 338 | 1081 | 68.51 | 19.79 | 0.89 |
| 7 | 394 | 1192 | 78.17 | 22.34 | 1.00 |
| 8 | 450 | 1303 | 87.46 | 25.02 | 1.09 |
| 10 | 561 | 1529 | 96.77 | 27.98 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.44 | 8.41 | 0.49 |
| 3| 2102 | 28.02 | 10.08 | 0.54 |
| 5| 2376 | 31.49 | 12.36 | 0.60 |
| 10| 3158 | 40.81 | 18.30 | 0.75 |
| 40| 7620 | 98.90 | 54.46 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.77 | 7.36 | 0.42 |
| 2| 766 | 23.65 | 8.24 | 0.43 |
| 3| 925 | 25.10 | 9.32 | 0.46 |
| 5| 1177 | 28.04 | 11.48 | 0.51 |
| 10| 1957 | 39.83 | 18.11 | 0.69 |
| 41| 6732 | 99.47 | 55.40 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 26.79 | 8.25 | 0.45 |
| 2| 770 | 30.98 | 10.08 | 0.51 |
| 3| 940 | 30.90 | 10.74 | 0.52 |
| 5| 1247 | 37.35 | 13.87 | 0.61 |
| 10| 1899 | 45.86 | 19.57 | 0.75 |
| 37| 6076 | 98.39 | 52.34 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.16 | 0.53 |
| 2| 760 | 35.17 | 11.17 | 0.55 |
| 3| 1077 | 39.26 | 13.03 | 0.61 |
| 5| 1257 | 42.56 | 15.26 | 0.66 |
| 10| 1957 | 53.42 | 21.61 | 0.82 |
| 29| 4870 | 98.36 | 46.82 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5969 | 37.09 | 12.47 | 0.80 |
| 3| 6116 | 44.72 | 15.05 | 0.89 |
| 4| 6304 | 55.78 | 18.88 | 1.01 |
| 5| 6416 | 61.55 | 20.68 | 1.08 |
| 6| 6365 | 68.59 | 22.97 | 1.15 |
| 7| 6885 | 85.95 | 28.97 | 1.36 |
| 8| 6854 | 92.73 | 31.23 | 1.43 |
| 9| 7085 | 99.95 | 33.69 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2217 | 7157 | 98.05 | 37.58 | 1.53 |

