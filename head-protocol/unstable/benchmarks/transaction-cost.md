--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-05 05:12:46.812121644 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 41.49 | 11.99 | 0.60 |
| 4 | 225 | 858 | 50.54 | 14.52 | 0.70 |
| 5 | 283 | 969 | 57.80 | 16.68 | 0.78 |
| 6 | 338 | 1081 | 73.69 | 20.91 | 0.94 |
| 7 | 394 | 1192 | 84.30 | 23.77 | 1.06 |
| 8 | 451 | 1303 | 93.46 | 26.35 | 1.15 |
| 9 | 505 | 1414 | 91.30 | 26.33 | 1.14 |
| 10 | 560 | 1525 | 97.71 | 28.27 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1929 | 25.76 | 8.76 | 0.51 |
| 3| 2134 | 28.42 | 10.17 | 0.55 |
| 5| 2351 | 30.65 | 12.13 | 0.59 |
| 10| 3316 | 43.32 | 19.03 | 0.78 |
| 41| 7734 | 99.60 | 55.30 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.84 | 7.39 | 0.41 |
| 2| 808 | 25.37 | 8.75 | 0.45 |
| 3| 955 | 26.20 | 9.64 | 0.47 |
| 5| 1316 | 32.06 | 12.61 | 0.56 |
| 10| 1877 | 37.63 | 17.53 | 0.66 |
| 40| 6473 | 97.04 | 54.03 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 27.50 | 8.46 | 0.46 |
| 2| 807 | 30.98 | 10.08 | 0.51 |
| 3| 902 | 30.19 | 10.53 | 0.51 |
| 5| 1269 | 37.06 | 13.79 | 0.60 |
| 10| 2059 | 48.03 | 20.23 | 0.77 |
| 38| 6142 | 99.29 | 53.30 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 1027 | 38.63 | 12.83 | 0.60 |
| 5| 1376 | 44.02 | 15.70 | 0.68 |
| 10| 2018 | 53.94 | 21.78 | 0.83 |
| 30| 4905 | 99.26 | 47.70 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.09 | 9.09 | 0.69 |
| 2| 5977 | 37.05 | 12.49 | 0.80 |
| 3| 5996 | 43.71 | 14.70 | 0.87 |
| 4| 6242 | 54.38 | 18.35 | 1.00 |
| 5| 6329 | 62.93 | 21.12 | 1.09 |
| 6| 6453 | 69.78 | 23.47 | 1.17 |
| 7| 6788 | 84.90 | 28.70 | 1.34 |
| 8| 6614 | 81.62 | 27.24 | 1.30 |
| 9| 6932 | 96.77 | 32.53 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1709 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2279 | 7195 | 99.66 | 38.24 | 1.55 |

