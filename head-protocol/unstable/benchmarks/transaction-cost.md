--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-11 10:00:00.331291378 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.48 | 4.58 | 0.57 |
| 5| 6646 | 18.98 | 6.00 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 41.01 | 11.85 | 0.60 |
| 4 | 226 | 858 | 47.79 | 13.87 | 0.67 |
| 5 | 283 | 969 | 64.11 | 18.19 | 0.84 |
| 6 | 340 | 1081 | 67.62 | 19.38 | 0.88 |
| 7 | 393 | 1192 | 74.33 | 21.47 | 0.96 |
| 8 | 449 | 1307 | 84.89 | 24.35 | 1.07 |
| 9 | 504 | 1418 | 91.80 | 26.51 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1924 | 25.51 | 8.70 | 0.50 |
| 3| 2017 | 26.31 | 9.58 | 0.52 |
| 5| 2406 | 31.19 | 12.29 | 0.60 |
| 10| 3320 | 44.27 | 19.26 | 0.79 |
| 40| 7690 | 98.83 | 54.41 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.84 | 7.37 | 0.41 |
| 2| 744 | 24.31 | 8.47 | 0.44 |
| 3| 897 | 25.72 | 9.52 | 0.47 |
| 5| 1290 | 30.68 | 12.24 | 0.54 |
| 10| 1880 | 36.66 | 17.22 | 0.65 |
| 41| 6425 | 95.62 | 54.32 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 29.17 | 8.91 | 0.48 |
| 2| 856 | 31.69 | 10.29 | 0.52 |
| 3| 917 | 32.80 | 11.25 | 0.54 |
| 5| 1210 | 34.37 | 13.04 | 0.58 |
| 10| 2043 | 48.34 | 20.31 | 0.78 |
| 37| 6087 | 99.46 | 52.68 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.83 | 10.15 | 0.53 |
| 2| 825 | 35.89 | 11.39 | 0.56 |
| 3| 953 | 37.88 | 12.61 | 0.59 |
| 5| 1315 | 43.43 | 15.51 | 0.67 |
| 10| 2026 | 53.75 | 21.73 | 0.83 |
| 29| 4994 | 99.10 | 47.04 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.09 | 9.09 | 0.69 |
| 2| 5969 | 37.05 | 12.49 | 0.80 |
| 3| 6100 | 44.64 | 15.02 | 0.89 |
| 4| 6228 | 52.34 | 17.61 | 0.97 |
| 5| 6335 | 63.16 | 21.22 | 1.09 |
| 6| 6490 | 72.01 | 24.16 | 1.19 |
| 7| 6642 | 79.32 | 26.61 | 1.28 |
| 8| 6797 | 88.84 | 29.86 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 283 | 6002 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2275 | 7191 | 99.22 | 38.09 | 1.54 |

