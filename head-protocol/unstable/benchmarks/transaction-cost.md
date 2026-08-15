--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-15 05:43:50.099741737 UTC |
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
| 1| 5837 | 10.86 | 3.46 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.88 | 9.10 | 0.79 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 751 | 42.27 | 12.15 | 0.61 |
| 4 | 228 | 858 | 47.60 | 13.82 | 0.67 |
| 5 | 281 | 969 | 59.42 | 17.10 | 0.80 |
| 6 | 340 | 1081 | 65.46 | 18.86 | 0.86 |
| 7 | 396 | 1192 | 74.92 | 21.70 | 0.96 |
| 8 | 450 | 1303 | 85.95 | 24.80 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 23.30 | 7.41 | 0.47 |
| 2| 1925 | 25.76 | 8.76 | 0.51 |
| 3| 2104 | 28.46 | 10.18 | 0.55 |
| 5| 2338 | 30.12 | 11.99 | 0.58 |
| 10| 3225 | 42.71 | 18.85 | 0.77 |
| 38| 7190 | 92.63 | 51.35 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.84 | 7.38 | 0.42 |
| 2| 733 | 24.27 | 8.44 | 0.44 |
| 3| 970 | 26.68 | 9.79 | 0.48 |
| 5| 1218 | 29.79 | 11.99 | 0.53 |
| 10| 2048 | 40.69 | 18.35 | 0.70 |
| 40| 6617 | 99.67 | 54.79 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 824 | 29.22 | 9.61 | 0.49 |
| 3| 961 | 33.39 | 11.43 | 0.54 |
| 5| 1232 | 37.02 | 13.77 | 0.60 |
| 10| 2023 | 47.84 | 20.18 | 0.77 |
| 36| 6014 | 98.42 | 51.75 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 850 | 36.64 | 11.62 | 0.57 |
| 3| 959 | 37.88 | 12.61 | 0.59 |
| 5| 1288 | 43.36 | 15.49 | 0.67 |
| 10| 1969 | 53.34 | 21.59 | 0.82 |
| 29| 4719 | 96.39 | 46.21 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.13 | 9.09 | 0.69 |
| 2| 5962 | 36.97 | 12.46 | 0.80 |
| 3| 6157 | 45.53 | 15.37 | 0.90 |
| 4| 6048 | 45.84 | 15.23 | 0.90 |
| 5| 6357 | 60.60 | 20.35 | 1.07 |
| 6| 6595 | 74.04 | 24.92 | 1.22 |
| 7| 6674 | 80.04 | 26.98 | 1.29 |
| 8| 6889 | 91.20 | 30.74 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1140 | 6515 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7157 | 99.38 | 38.04 | 1.54 |

