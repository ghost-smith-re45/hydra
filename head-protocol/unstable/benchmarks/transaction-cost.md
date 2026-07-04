--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-04 08:05:15.354509913 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6643 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.30 | 9.24 | 0.79 |
| 43| 14285 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.39 | 9.43 | 0.51 |
| 3 | 171 | 747 | 41.40 | 11.95 | 0.60 |
| 4 | 228 | 858 | 52.10 | 14.92 | 0.72 |
| 5 | 284 | 969 | 61.34 | 17.53 | 0.81 |
| 6 | 338 | 1081 | 66.82 | 19.31 | 0.88 |
| 7 | 393 | 1192 | 72.51 | 20.99 | 0.94 |
| 8 | 449 | 1303 | 96.56 | 27.19 | 1.18 |
| 9 | 504 | 1414 | 87.33 | 25.26 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1826 | 24.29 | 7.69 | 0.48 |
| 2| 1941 | 25.84 | 8.78 | 0.51 |
| 3| 2077 | 27.24 | 9.84 | 0.53 |
| 5| 2439 | 32.32 | 12.60 | 0.61 |
| 10| 3068 | 39.82 | 18.03 | 0.74 |
| 41| 7655 | 98.13 | 54.91 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.50 | 7.29 | 0.41 |
| 2| 699 | 22.58 | 7.95 | 0.42 |
| 3| 853 | 24.07 | 9.03 | 0.45 |
| 5| 1265 | 31.27 | 12.39 | 0.55 |
| 10| 1992 | 38.46 | 17.74 | 0.68 |
| 41| 6536 | 96.28 | 54.49 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.51 | 8.47 | 0.46 |
| 2| 800 | 30.98 | 10.08 | 0.51 |
| 3| 953 | 33.43 | 11.44 | 0.54 |
| 5| 1219 | 36.91 | 13.75 | 0.60 |
| 10| 2102 | 48.98 | 20.50 | 0.79 |
| 36| 6071 | 99.16 | 51.93 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.79 | 10.15 | 0.53 |
| 2| 859 | 36.60 | 11.61 | 0.57 |
| 3| 988 | 38.63 | 12.83 | 0.60 |
| 5| 1162 | 41.26 | 14.85 | 0.64 |
| 10| 1878 | 52.11 | 21.21 | 0.81 |
| 31| 4884 | 98.36 | 48.05 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.05 | 9.07 | 0.69 |
| 2| 5920 | 35.95 | 12.11 | 0.79 |
| 3| 6019 | 41.37 | 13.85 | 0.85 |
| 4| 6209 | 54.91 | 18.52 | 1.00 |
| 5| 6352 | 60.02 | 20.18 | 1.06 |
| 6| 6471 | 72.61 | 24.40 | 1.20 |
| 7| 6658 | 78.42 | 26.35 | 1.27 |
| 8| 6780 | 90.64 | 30.43 | 1.40 |
| 9| 6950 | 95.06 | 31.90 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1705 | 6851 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2166 | 7128 | 95.74 | 36.69 | 1.50 |

