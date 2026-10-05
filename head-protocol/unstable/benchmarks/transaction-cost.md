--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-05 11:52:18.951013258 UTC |
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
| 1| 5834 | 10.69 | 3.40 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 29.47 | 9.30 | 0.79 |
| 43| 14285 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 640 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 751 | 43.73 | 12.51 | 0.63 |
| 4 | 226 | 858 | 52.33 | 14.98 | 0.72 |
| 5 | 284 | 969 | 56.20 | 16.33 | 0.76 |
| 6 | 337 | 1081 | 71.13 | 20.26 | 0.92 |
| 7 | 394 | 1192 | 82.97 | 23.58 | 1.04 |
| 8 | 449 | 1303 | 80.97 | 23.56 | 1.03 |
| 9 | 505 | 1414 | 98.96 | 28.23 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1930 | 25.47 | 8.70 | 0.50 |
| 3| 2012 | 26.02 | 9.51 | 0.52 |
| 5| 2495 | 33.61 | 12.95 | 0.62 |
| 10| 3305 | 42.94 | 18.90 | 0.78 |
| 39| 7434 | 94.44 | 52.56 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.57 | 7.30 | 0.41 |
| 2| 857 | 25.33 | 8.75 | 0.46 |
| 3| 915 | 25.02 | 9.30 | 0.46 |
| 5| 1282 | 30.89 | 12.29 | 0.54 |
| 10| 1978 | 38.84 | 17.84 | 0.68 |
| 41| 6565 | 96.21 | 54.46 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 919 | 32.76 | 11.24 | 0.54 |
| 5| 1183 | 36.53 | 13.63 | 0.60 |
| 10| 2013 | 47.37 | 20.02 | 0.77 |
| 36| 5994 | 97.78 | 51.51 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.15 | 0.53 |
| 2| 820 | 35.85 | 11.38 | 0.56 |
| 3| 942 | 37.80 | 12.59 | 0.59 |
| 5| 1283 | 42.53 | 15.25 | 0.66 |
| 10| 2026 | 54.40 | 21.91 | 0.84 |
| 28| 4651 | 95.15 | 45.24 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.96 | 9.06 | 0.69 |
| 2| 5914 | 36.04 | 12.12 | 0.79 |
| 3| 6128 | 45.70 | 15.43 | 0.90 |
| 4| 6276 | 54.76 | 18.48 | 1.00 |
| 5| 6442 | 62.96 | 21.23 | 1.10 |
| 6| 6528 | 70.59 | 23.76 | 1.18 |
| 7| 6632 | 78.57 | 26.46 | 1.27 |
| 8| 6843 | 92.76 | 31.19 | 1.43 |
| 9| 6858 | 90.96 | 30.57 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1138 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 39 | 2219 | 7159 | 98.49 | 37.73 | 1.53 |

