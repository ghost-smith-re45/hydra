--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-09 07:25:53.52293035 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.32 | 3.89 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7650 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 33.17 | 9.59 | 0.52 |
| 3 | 168 | 746 | 41.51 | 12.00 | 0.60 |
| 4 | 228 | 858 | 49.58 | 14.32 | 0.69 |
| 5 | 283 | 969 | 58.17 | 16.86 | 0.78 |
| 6 | 339 | 1081 | 71.74 | 20.45 | 0.92 |
| 7 | 394 | 1192 | 72.06 | 20.92 | 0.94 |
| 8 | 450 | 1303 | 94.49 | 26.75 | 1.16 |
| 9 | 506 | 1414 | 98.66 | 28.15 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.37 | 7.71 | 0.48 |
| 2| 1945 | 25.47 | 8.70 | 0.50 |
| 3| 2012 | 26.28 | 9.57 | 0.52 |
| 5| 2446 | 31.95 | 12.51 | 0.61 |
| 10| 3084 | 40.39 | 18.18 | 0.74 |
| 40| 7534 | 97.31 | 53.99 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.80 | 7.38 | 0.41 |
| 2| 783 | 24.25 | 8.44 | 0.44 |
| 3| 946 | 26.84 | 9.83 | 0.48 |
| 5| 1284 | 31.10 | 12.35 | 0.55 |
| 10| 1930 | 37.93 | 17.58 | 0.67 |
| 40| 6241 | 92.13 | 52.67 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.13 | 8.90 | 0.48 |
| 2| 776 | 30.91 | 10.06 | 0.51 |
| 3| 944 | 30.90 | 10.74 | 0.52 |
| 5| 1374 | 36.24 | 13.62 | 0.60 |
| 10| 1862 | 45.45 | 19.43 | 0.74 |
| 37| 6098 | 97.95 | 52.23 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 811 | 35.92 | 11.40 | 0.56 |
| 3| 1069 | 39.34 | 13.05 | 0.61 |
| 5| 1200 | 41.93 | 15.06 | 0.65 |
| 10| 2101 | 55.41 | 22.22 | 0.85 |
| 29| 4972 | 99.45 | 47.13 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.13 | 9.10 | 0.69 |
| 2| 5893 | 34.79 | 11.65 | 0.77 |
| 3| 6140 | 44.47 | 14.98 | 0.89 |
| 4| 6285 | 54.93 | 18.50 | 1.00 |
| 5| 6314 | 62.19 | 20.91 | 1.08 |
| 6| 6661 | 75.77 | 25.56 | 1.24 |
| 7| 6646 | 83.06 | 27.91 | 1.31 |
| 8| 7099 | 95.91 | 32.49 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 571 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1710 | 6857 | 79.78 | 30.37 | 1.32 |
| 10 | 38 | 2165 | 7128 | 98.40 | 37.59 | 1.53 |

