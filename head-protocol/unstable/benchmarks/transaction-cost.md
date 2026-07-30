--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-30 07:45:17.283715184 UTC |
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
| 1| 5837 | 10.78 | 3.43 | 0.52 |
| 2| 6038 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 15.05 | 4.78 | 0.58 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7644 | 28.81 | 9.07 | 0.78 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 169 | 747 | 42.62 | 12.25 | 0.62 |
| 4 | 227 | 858 | 49.58 | 14.32 | 0.69 |
| 5 | 282 | 969 | 60.90 | 17.42 | 0.81 |
| 6 | 340 | 1081 | 73.25 | 20.81 | 0.94 |
| 7 | 395 | 1192 | 80.52 | 22.91 | 1.02 |
| 8 | 451 | 1303 | 80.66 | 23.33 | 1.03 |
| 9 | 505 | 1414 | 89.97 | 26.08 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1936 | 25.76 | 8.76 | 0.51 |
| 3| 2104 | 28.31 | 10.14 | 0.54 |
| 5| 2374 | 30.97 | 12.23 | 0.59 |
| 10| 3301 | 43.06 | 18.95 | 0.78 |
| 41| 7811 | 99.57 | 55.32 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.54 | 7.30 | 0.41 |
| 2| 803 | 25.52 | 8.78 | 0.46 |
| 3| 876 | 25.85 | 9.56 | 0.47 |
| 5| 1232 | 29.66 | 11.96 | 0.53 |
| 10| 2022 | 41.69 | 18.66 | 0.71 |
| 42| 6713 | 98.98 | 55.88 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 27.54 | 8.47 | 0.46 |
| 2| 802 | 30.98 | 10.08 | 0.51 |
| 3| 902 | 30.26 | 10.55 | 0.51 |
| 5| 1371 | 36.51 | 13.69 | 0.60 |
| 10| 1959 | 44.04 | 19.11 | 0.73 |
| 36| 5992 | 97.33 | 51.46 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.87 | 10.16 | 0.53 |
| 2| 812 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1320 | 43.43 | 15.51 | 0.67 |
| 10| 1903 | 52.45 | 21.33 | 0.81 |
| 30| 4944 | 99.00 | 47.62 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 27.09 | 9.10 | 0.69 |
| 2| 5955 | 35.88 | 12.04 | 0.79 |
| 3| 6053 | 44.96 | 15.10 | 0.89 |
| 4| 6339 | 57.20 | 19.33 | 1.03 |
| 5| 6502 | 65.07 | 21.94 | 1.12 |
| 6| 6713 | 75.36 | 25.48 | 1.24 |
| 7| 6738 | 83.75 | 28.19 | 1.33 |
| 8| 6859 | 90.03 | 30.32 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2217 | 7157 | 98.49 | 37.73 | 1.53 |

