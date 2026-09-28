--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-28 11:53:40.233673645 UTC |
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
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 751 | 41.49 | 12.01 | 0.61 |
| 4 | 226 | 858 | 53.78 | 15.30 | 0.73 |
| 5 | 282 | 969 | 57.71 | 16.66 | 0.78 |
| 6 | 337 | 1081 | 68.45 | 19.70 | 0.89 |
| 7 | 396 | 1192 | 78.61 | 22.45 | 1.00 |
| 8 | 449 | 1303 | 94.51 | 26.89 | 1.16 |
| 9 | 506 | 1414 | 92.30 | 26.80 | 1.15 |
| 10 | 560 | 1525 | 97.96 | 28.34 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1920 | 25.76 | 8.76 | 0.51 |
| 3| 2100 | 27.94 | 10.05 | 0.54 |
| 5| 2327 | 30.04 | 11.97 | 0.58 |
| 10| 3262 | 43.08 | 18.93 | 0.78 |
| 42| 7635 | 94.37 | 54.53 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.77 | 7.36 | 0.41 |
| 2| 746 | 23.62 | 8.25 | 0.43 |
| 3| 853 | 24.03 | 9.02 | 0.45 |
| 5| 1200 | 29.08 | 11.77 | 0.52 |
| 10| 2048 | 40.75 | 18.37 | 0.70 |
| 41| 6541 | 97.35 | 54.79 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.47 | 8.46 | 0.46 |
| 2| 732 | 30.23 | 9.85 | 0.50 |
| 3| 956 | 30.98 | 10.76 | 0.52 |
| 5| 1265 | 34.89 | 13.21 | 0.58 |
| 10| 2097 | 49.43 | 20.65 | 0.79 |
| 35| 5838 | 96.11 | 50.42 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.83 | 10.16 | 0.53 |
| 2| 812 | 35.85 | 11.38 | 0.56 |
| 3| 1013 | 38.55 | 12.81 | 0.60 |
| 5| 1331 | 43.96 | 15.68 | 0.68 |
| 10| 2002 | 53.45 | 21.62 | 0.83 |
| 29| 4787 | 97.93 | 46.67 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 26.97 | 9.05 | 0.69 |
| 2| 6017 | 36.96 | 12.45 | 0.80 |
| 3| 6060 | 44.87 | 15.09 | 0.89 |
| 4| 6319 | 54.79 | 18.44 | 1.00 |
| 5| 6359 | 60.13 | 20.22 | 1.06 |
| 6| 6648 | 75.81 | 25.62 | 1.24 |
| 7| 6692 | 78.95 | 26.62 | 1.27 |
| 8| 6715 | 85.51 | 28.79 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

