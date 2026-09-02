--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-02 09:46:22.791231596 UTC |
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
| 1| 5836 | 10.35 | 3.28 | 0.51 |
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.76 | 4.67 | 0.58 |
| 5| 6640 | 18.60 | 5.87 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 751 | 43.76 | 12.53 | 0.63 |
| 4 | 226 | 858 | 52.42 | 15.00 | 0.72 |
| 5 | 281 | 969 | 64.25 | 18.26 | 0.84 |
| 6 | 338 | 1081 | 64.80 | 18.79 | 0.86 |
| 7 | 395 | 1192 | 86.52 | 24.34 | 1.08 |
| 8 | 450 | 1303 | 89.76 | 25.56 | 1.12 |
| 10 | 560 | 1525 | 97.80 | 28.36 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 22.92 | 7.32 | 0.47 |
| 2| 1914 | 25.47 | 8.70 | 0.50 |
| 3| 2086 | 27.32 | 9.86 | 0.53 |
| 5| 2380 | 30.99 | 12.24 | 0.59 |
| 10| 3165 | 42.30 | 18.71 | 0.77 |
| 41| 7593 | 97.50 | 54.73 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.77 | 7.36 | 0.41 |
| 2| 825 | 25.57 | 8.80 | 0.46 |
| 3| 966 | 26.10 | 9.60 | 0.47 |
| 5| 1230 | 29.55 | 11.94 | 0.53 |
| 10| 1961 | 38.58 | 17.76 | 0.68 |
| 40| 6641 | 97.67 | 54.20 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 29.13 | 8.90 | 0.48 |
| 2| 797 | 30.98 | 10.08 | 0.51 |
| 3| 1032 | 32.33 | 11.18 | 0.54 |
| 5| 1340 | 35.75 | 13.46 | 0.60 |
| 10| 2035 | 47.85 | 20.18 | 0.77 |
| 38| 6148 | 99.27 | 53.27 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.83 | 10.16 | 0.53 |
| 2| 871 | 36.56 | 11.60 | 0.57 |
| 3| 1013 | 38.51 | 12.80 | 0.60 |
| 5| 1312 | 43.32 | 15.48 | 0.67 |
| 10| 2071 | 55.25 | 22.16 | 0.85 |
| 29| 4911 | 98.18 | 46.77 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.05 | 9.08 | 0.69 |
| 2| 5820 | 31.45 | 10.45 | 0.74 |
| 3| 6164 | 45.92 | 15.47 | 0.90 |
| 4| 6253 | 55.02 | 18.54 | 1.00 |
| 5| 6460 | 65.10 | 21.97 | 1.12 |
| 6| 6660 | 75.14 | 25.40 | 1.23 |
| 7| 6705 | 78.13 | 26.28 | 1.27 |
| 8| 6824 | 88.71 | 29.88 | 1.38 |
| 9| 6908 | 94.46 | 31.84 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2217 | 7157 | 98.05 | 37.58 | 1.53 |

