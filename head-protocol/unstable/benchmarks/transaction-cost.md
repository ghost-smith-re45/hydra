--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-15 06:50:37.477185226 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6042 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 42.62 | 12.26 | 0.62 |
| 4 | 226 | 858 | 53.81 | 15.31 | 0.73 |
| 5 | 282 | 969 | 62.20 | 17.73 | 0.82 |
| 6 | 338 | 1081 | 65.22 | 18.88 | 0.86 |
| 7 | 394 | 1192 | 78.08 | 22.28 | 0.99 |
| 8 | 449 | 1303 | 94.27 | 26.69 | 1.16 |
| 9 | 505 | 1414 | 95.41 | 27.20 | 1.18 |
| 10 | 560 | 1525 | 97.45 | 28.33 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.85 | 8.50 | 0.50 |
| 3| 2082 | 26.98 | 9.78 | 0.53 |
| 5| 2344 | 29.96 | 11.95 | 0.58 |
| 10| 3189 | 40.89 | 18.32 | 0.75 |
| 39| 7257 | 93.87 | 52.33 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.54 | 7.30 | 0.41 |
| 2| 789 | 23.59 | 8.23 | 0.43 |
| 3| 923 | 25.10 | 9.32 | 0.46 |
| 5| 1230 | 30.50 | 12.18 | 0.54 |
| 10| 2025 | 40.51 | 18.33 | 0.70 |
| 38| 6031 | 91.71 | 51.17 | 1.53 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 597 | 28.46 | 8.69 | 0.47 |
| 2| 850 | 31.58 | 10.26 | 0.52 |
| 3| 957 | 33.40 | 11.44 | 0.54 |
| 5| 1322 | 35.75 | 13.46 | 0.59 |
| 10| 2039 | 47.96 | 20.21 | 0.77 |
| 34| 5456 | 91.14 | 48.31 | 1.47 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 872 | 36.52 | 11.59 | 0.57 |
| 3| 939 | 37.91 | 12.62 | 0.59 |
| 5| 1243 | 42.65 | 15.28 | 0.66 |
| 10| 2094 | 55.22 | 22.17 | 0.85 |
| 29| 4760 | 96.65 | 46.30 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.09 | 9.09 | 0.69 |
| 2| 6046 | 37.08 | 12.50 | 0.81 |
| 3| 6202 | 46.91 | 15.86 | 0.92 |
| 4| 6277 | 54.67 | 18.41 | 1.00 |
| 5| 6507 | 65.88 | 22.27 | 1.13 |
| 6| 6621 | 75.54 | 25.50 | 1.24 |
| 7| 6607 | 77.96 | 26.20 | 1.26 |
| 8| 6863 | 94.36 | 31.81 | 1.44 |
| 9| 6965 | 98.60 | 33.17 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 40 | 2280 | 7197 | 99.84 | 38.30 | 1.55 |
| 10 | 37 | 2107 | 7093 | 94.39 | 36.12 | 1.49 |

