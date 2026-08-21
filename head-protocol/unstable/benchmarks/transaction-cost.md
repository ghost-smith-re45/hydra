--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-21 05:57:29.242611051 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 13.10 | 4.17 | 0.55 |
| 3| 6239 | 15.24 | 4.85 | 0.58 |
| 5| 6640 | 18.98 | 6.00 | 0.64 |
| 10| 7644 | 29.49 | 9.31 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 41.19 | 11.92 | 0.60 |
| 4 | 228 | 858 | 48.11 | 13.94 | 0.68 |
| 5 | 283 | 969 | 59.46 | 17.08 | 0.80 |
| 6 | 339 | 1081 | 71.46 | 20.34 | 0.92 |
| 7 | 393 | 1192 | 72.46 | 20.98 | 0.94 |
| 8 | 450 | 1303 | 96.70 | 27.28 | 1.19 |
| 9 | 505 | 1418 | 91.04 | 26.27 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.29 | 7.69 | 0.48 |
| 2| 1972 | 26.46 | 8.97 | 0.52 |
| 3| 2063 | 26.90 | 9.76 | 0.53 |
| 5| 2391 | 30.96 | 12.23 | 0.59 |
| 10| 3176 | 41.16 | 18.39 | 0.76 |
| 38| 7570 | 97.41 | 52.77 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.54 | 7.30 | 0.41 |
| 2| 796 | 23.59 | 8.23 | 0.44 |
| 3| 941 | 26.02 | 9.58 | 0.47 |
| 5| 1246 | 29.04 | 11.76 | 0.52 |
| 10| 1987 | 38.47 | 17.73 | 0.68 |
| 40| 6550 | 98.82 | 54.52 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.19 | 9.84 | 0.50 |
| 3| 940 | 30.94 | 10.75 | 0.52 |
| 5| 1307 | 35.80 | 13.48 | 0.59 |
| 10| 2077 | 48.14 | 20.25 | 0.78 |
| 38| 6081 | 99.50 | 53.32 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 812 | 35.85 | 11.38 | 0.56 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1309 | 43.32 | 15.49 | 0.67 |
| 10| 1978 | 53.31 | 21.58 | 0.82 |
| 29| 4742 | 96.28 | 46.16 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5935 | 35.96 | 12.07 | 0.79 |
| 3| 6158 | 45.77 | 15.44 | 0.90 |
| 4| 6162 | 50.18 | 16.80 | 0.95 |
| 5| 6294 | 57.17 | 19.14 | 1.03 |
| 6| 6569 | 73.93 | 24.95 | 1.22 |
| 7| 6393 | 66.94 | 22.29 | 1.13 |
| 8| 6961 | 94.10 | 31.78 | 1.45 |
| 9| 6962 | 98.78 | 33.16 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2163 | 7125 | 96.00 | 36.77 | 1.50 |

