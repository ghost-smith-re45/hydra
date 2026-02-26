--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-26 06:41:23.152963256 UTC |
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
| 1| 5836 | 10.95 | 3.49 | 0.52 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6240 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7648 | 28.81 | 9.07 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 747 | 40.10 | 11.64 | 0.59 |
| 4 | 225 | 858 | 48.22 | 13.99 | 0.68 |
| 5 | 284 | 974 | 64.29 | 18.23 | 0.84 |
| 6 | 339 | 1081 | 76.43 | 21.69 | 0.97 |
| 7 | 393 | 1192 | 84.79 | 23.93 | 1.06 |
| 8 | 452 | 1303 | 98.96 | 27.82 | 1.21 |
| 9 | 504 | 1418 | 94.21 | 27.08 | 1.17 |
| 10 | 560 | 1525 | 99.74 | 28.75 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1963 | 26.46 | 8.97 | 0.52 |
| 3| 2139 | 28.39 | 10.16 | 0.55 |
| 5| 2373 | 31.37 | 12.33 | 0.60 |
| 10| 3194 | 42.15 | 18.67 | 0.77 |
| 40| 7601 | 99.54 | 54.60 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.50 | 7.29 | 0.41 |
| 2| 828 | 25.16 | 8.71 | 0.45 |
| 3| 899 | 25.03 | 9.30 | 0.46 |
| 5| 1272 | 30.50 | 12.19 | 0.54 |
| 10| 2172 | 43.57 | 19.13 | 0.74 |
| 40| 6581 | 98.91 | 54.54 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.09 | 8.89 | 0.48 |
| 2| 901 | 29.86 | 9.81 | 0.50 |
| 3| 949 | 30.82 | 10.73 | 0.52 |
| 5| 1214 | 34.37 | 13.04 | 0.58 |
| 10| 2235 | 49.67 | 20.73 | 0.80 |
| 36| 6095 | 99.11 | 51.98 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 863 | 36.64 | 11.62 | 0.57 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1288 | 42.53 | 15.25 | 0.66 |
| 10| 2087 | 54.76 | 22.02 | 0.84 |
| 29| 5099 | 99.60 | 47.22 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.09 | 9.09 | 0.69 |
| 2| 5909 | 32.45 | 10.85 | 0.75 |
| 3| 6012 | 41.48 | 13.87 | 0.85 |
| 4| 6143 | 52.35 | 17.61 | 0.97 |
| 5| 6267 | 59.41 | 19.94 | 1.05 |
| 6| 6500 | 70.32 | 23.73 | 1.18 |
| 7| 6659 | 78.05 | 26.25 | 1.26 |
| 8| 7012 | 94.30 | 31.93 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2214 | 7154 | 98.93 | 37.88 | 1.54 |

