--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-07 07:46:37.370105079 UTC |
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
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 19.17 | 6.07 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 42.57 | 12.27 | 0.62 |
| 4 | 226 | 858 | 50.99 | 14.68 | 0.71 |
| 5 | 282 | 974 | 61.46 | 17.65 | 0.82 |
| 6 | 339 | 1081 | 67.65 | 19.47 | 0.88 |
| 7 | 396 | 1192 | 83.08 | 23.65 | 1.04 |
| 8 | 451 | 1303 | 92.18 | 26.14 | 1.14 |
| 9 | 506 | 1414 | 90.19 | 26.05 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1996 | 26.87 | 9.07 | 0.52 |
| 3| 2127 | 28.42 | 10.17 | 0.55 |
| 5| 2391 | 31.45 | 12.35 | 0.60 |
| 10| 3129 | 40.50 | 18.21 | 0.75 |
| 38| 7107 | 90.92 | 50.89 | 1.56 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.84 | 7.39 | 0.41 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 942 | 26.12 | 9.60 | 0.47 |
| 5| 1135 | 28.07 | 11.50 | 0.51 |
| 10| 2024 | 40.04 | 18.17 | 0.69 |
| 40| 6370 | 92.79 | 52.85 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.50 | 8.46 | 0.46 |
| 2| 857 | 29.97 | 9.84 | 0.50 |
| 3| 994 | 31.54 | 10.94 | 0.53 |
| 5| 1237 | 37.43 | 13.90 | 0.61 |
| 10| 1995 | 47.21 | 19.98 | 0.76 |
| 37| 6152 | 99.54 | 52.71 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 804 | 35.92 | 11.40 | 0.56 |
| 3| 985 | 38.63 | 12.83 | 0.60 |
| 5| 1331 | 43.17 | 15.45 | 0.67 |
| 10| 2044 | 54.92 | 22.06 | 0.84 |
| 29| 4774 | 96.74 | 46.32 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5946 | 35.93 | 12.07 | 0.79 |
| 3| 6104 | 45.08 | 15.15 | 0.89 |
| 4| 6214 | 51.31 | 17.26 | 0.96 |
| 5| 6339 | 63.53 | 21.38 | 1.10 |
| 6| 6549 | 73.44 | 24.72 | 1.21 |
| 7| 6532 | 78.51 | 26.34 | 1.26 |
| 8| 6753 | 87.15 | 29.21 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 99.38 | 38.04 | 1.54 |

