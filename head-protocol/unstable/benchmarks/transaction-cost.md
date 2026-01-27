--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-27 05:02:21.095093328 UTC |
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
| 1| 5837 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 19.34 | 6.13 | 0.64 |
| 10| 7650 | 29.18 | 9.20 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 169 | 747 | 43.76 | 12.52 | 0.63 |
| 4 | 226 | 858 | 48.93 | 14.13 | 0.69 |
| 5 | 282 | 969 | 62.57 | 17.82 | 0.83 |
| 6 | 339 | 1081 | 75.66 | 21.39 | 0.96 |
| 7 | 393 | 1192 | 78.84 | 22.68 | 1.00 |
| 8 | 449 | 1303 | 98.92 | 27.76 | 1.21 |
| 9 | 506 | 1418 | 93.67 | 26.89 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.29 | 7.69 | 0.48 |
| 2| 1992 | 26.79 | 9.05 | 0.52 |
| 3| 2130 | 28.10 | 10.09 | 0.54 |
| 5| 2370 | 31.48 | 12.36 | 0.60 |
| 10| 3205 | 42.46 | 18.76 | 0.77 |
| 39| 7423 | 96.48 | 53.12 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.37 | 0.41 |
| 2| 820 | 25.57 | 8.80 | 0.46 |
| 3| 898 | 25.76 | 9.53 | 0.47 |
| 5| 1137 | 28.69 | 11.69 | 0.52 |
| 10| 1952 | 37.78 | 17.53 | 0.67 |
| 42| 6688 | 98.77 | 55.86 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.54 | 8.47 | 0.46 |
| 2| 840 | 29.26 | 9.62 | 0.49 |
| 3| 977 | 33.51 | 11.47 | 0.55 |
| 5| 1278 | 35.05 | 13.25 | 0.59 |
| 10| 2105 | 45.72 | 19.61 | 0.75 |
| 36| 5862 | 95.63 | 50.90 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 827 | 35.85 | 11.38 | 0.56 |
| 3| 948 | 37.91 | 12.62 | 0.59 |
| 5| 1328 | 43.32 | 15.48 | 0.67 |
| 10| 1955 | 53.46 | 21.62 | 0.82 |
| 29| 4863 | 98.22 | 46.78 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 27.08 | 9.09 | 0.69 |
| 2| 5891 | 34.98 | 11.71 | 0.78 |
| 3| 6176 | 47.03 | 15.87 | 0.92 |
| 4| 6298 | 54.82 | 18.44 | 1.00 |
| 5| 6460 | 64.99 | 21.92 | 1.12 |
| 6| 6630 | 74.73 | 25.17 | 1.23 |
| 7| 6585 | 80.93 | 27.23 | 1.29 |
| 8| 7045 | 96.79 | 32.77 | 1.48 |
| 9| 6756 | 93.23 | 31.32 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1136 | 6510 | 59.54 | 22.38 | 1.08 |
| 10 | 38 | 2164 | 7126 | 95.56 | 36.62 | 1.50 |

