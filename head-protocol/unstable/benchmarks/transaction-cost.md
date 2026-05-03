--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-03 07:37:44.320773145 UTC |
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
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7648 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.46 | 12.20 | 0.61 |
| 4 | 226 | 858 | 48.19 | 14.01 | 0.68 |
| 5 | 280 | 974 | 59.25 | 17.02 | 0.79 |
| 6 | 340 | 1081 | 69.51 | 19.87 | 0.90 |
| 7 | 394 | 1192 | 77.02 | 22.16 | 0.98 |
| 8 | 450 | 1303 | 81.20 | 23.61 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 22.92 | 7.32 | 0.47 |
| 2| 1997 | 27.00 | 9.10 | 0.52 |
| 3| 2055 | 27.47 | 9.90 | 0.53 |
| 5| 2402 | 30.88 | 12.21 | 0.59 |
| 10| 3081 | 39.24 | 17.88 | 0.73 |
| 41| 7640 | 96.98 | 54.58 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 741 | 23.58 | 8.24 | 0.43 |
| 3| 879 | 25.05 | 9.30 | 0.46 |
| 5| 1157 | 28.05 | 11.48 | 0.51 |
| 10| 1972 | 39.03 | 17.93 | 0.68 |
| 40| 6472 | 97.90 | 54.27 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.19 | 9.84 | 0.50 |
| 3| 1000 | 31.69 | 10.98 | 0.53 |
| 5| 1334 | 35.83 | 13.49 | 0.60 |
| 10| 2018 | 47.56 | 20.09 | 0.77 |
| 35| 5827 | 94.70 | 50.03 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 833 | 36.52 | 11.59 | 0.57 |
| 3| 1047 | 38.84 | 12.91 | 0.60 |
| 5| 1246 | 42.60 | 15.27 | 0.66 |
| 10| 2062 | 54.81 | 22.03 | 0.84 |
| 29| 4893 | 99.16 | 47.03 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 27.08 | 9.08 | 0.69 |
| 2| 5933 | 36.00 | 12.10 | 0.79 |
| 3| 6126 | 45.42 | 15.34 | 0.90 |
| 4| 6167 | 52.74 | 17.73 | 0.98 |
| 5| 6300 | 57.09 | 19.13 | 1.03 |
| 6| 6506 | 69.78 | 23.39 | 1.17 |
| 7| 6850 | 85.55 | 28.93 | 1.35 |
| 8| 6851 | 93.18 | 31.45 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6515 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2222 | 7162 | 98.93 | 37.88 | 1.54 |

