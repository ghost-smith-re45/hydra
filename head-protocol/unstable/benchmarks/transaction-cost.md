--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-19 06:44:56.704385077 UTC |
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
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14286 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10082 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 227 | 858 | 52.57 | 15.04 | 0.72 |
| 5 | 280 | 969 | 60.58 | 17.31 | 0.81 |
| 6 | 339 | 1081 | 70.56 | 20.21 | 0.91 |
| 7 | 395 | 1196 | 85.26 | 24.17 | 1.07 |
| 8 | 453 | 1303 | 84.69 | 24.39 | 1.07 |
| 9 | 507 | 1414 | 95.77 | 27.40 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 24.29 | 7.69 | 0.48 |
| 2| 1984 | 26.92 | 9.09 | 0.52 |
| 3| 2121 | 28.39 | 10.16 | 0.55 |
| 5| 2322 | 30.26 | 12.02 | 0.58 |
| 10| 3186 | 41.69 | 18.56 | 0.76 |
| 40| 7748 | 99.20 | 54.57 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.39 | 0.41 |
| 2| 766 | 24.05 | 8.39 | 0.44 |
| 3| 962 | 26.99 | 9.87 | 0.48 |
| 5| 1218 | 29.67 | 11.96 | 0.53 |
| 10| 2094 | 43.48 | 19.11 | 0.73 |
| 41| 6712 | 99.16 | 55.26 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.17 | 8.91 | 0.48 |
| 2| 800 | 31.28 | 10.17 | 0.51 |
| 3| 964 | 33.36 | 11.42 | 0.54 |
| 5| 1337 | 35.83 | 13.49 | 0.60 |
| 10| 2209 | 47.00 | 20.01 | 0.77 |
| 35| 5697 | 99.21 | 51.17 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.87 | 10.16 | 0.53 |
| 2| 834 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1330 | 43.32 | 15.49 | 0.67 |
| 10| 2128 | 55.67 | 22.29 | 0.85 |
| 29| 5012 | 99.01 | 47.00 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.13 | 9.09 | 0.69 |
| 2| 5774 | 28.49 | 9.38 | 0.70 |
| 3| 6136 | 44.59 | 15.01 | 0.89 |
| 4| 6268 | 55.09 | 18.54 | 1.00 |
| 5| 6471 | 64.51 | 21.79 | 1.11 |
| 6| 6508 | 70.34 | 23.62 | 1.18 |
| 7| 6584 | 81.02 | 27.19 | 1.29 |
| 8| 6889 | 90.50 | 30.49 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2216 | 7156 | 98.05 | 37.58 | 1.53 |

