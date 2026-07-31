--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-31 08:06:15.923399303 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 41.51 | 12.00 | 0.61 |
| 4 | 226 | 862 | 49.72 | 14.38 | 0.69 |
| 5 | 283 | 974 | 60.31 | 17.31 | 0.81 |
| 6 | 338 | 1081 | 73.37 | 20.87 | 0.94 |
| 7 | 394 | 1192 | 82.68 | 23.47 | 1.04 |
| 8 | 448 | 1303 | 93.55 | 26.37 | 1.15 |
| 9 | 504 | 1414 | 94.59 | 27.23 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1825 | 23.92 | 7.60 | 0.48 |
| 2| 1999 | 26.62 | 9.02 | 0.52 |
| 3| 2075 | 27.35 | 9.87 | 0.53 |
| 5| 2426 | 32.03 | 12.53 | 0.61 |
| 10| 3127 | 40.31 | 18.15 | 0.74 |
| 40| 7662 | 97.61 | 54.11 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.77 | 7.36 | 0.42 |
| 2| 772 | 23.58 | 8.23 | 0.43 |
| 3| 989 | 28.27 | 10.24 | 0.50 |
| 5| 1301 | 32.54 | 12.73 | 0.56 |
| 10| 2008 | 41.13 | 18.46 | 0.70 |
| 41| 6529 | 96.15 | 54.45 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 29.09 | 8.89 | 0.48 |
| 2| 816 | 29.22 | 9.61 | 0.49 |
| 3| 1019 | 34.07 | 11.64 | 0.55 |
| 5| 1131 | 35.67 | 13.36 | 0.58 |
| 10| 2148 | 46.31 | 19.80 | 0.76 |
| 37| 6040 | 99.37 | 52.68 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.79 | 10.15 | 0.53 |
| 2| 755 | 35.21 | 11.18 | 0.55 |
| 3| 937 | 37.87 | 12.61 | 0.59 |
| 5| 1242 | 42.64 | 15.28 | 0.66 |
| 10| 2024 | 54.10 | 21.82 | 0.83 |
| 29| 4810 | 96.50 | 46.26 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5803 | 26.97 | 9.06 | 0.69 |
| 2| 5987 | 36.73 | 12.39 | 0.80 |
| 3| 6018 | 43.95 | 14.72 | 0.88 |
| 4| 6274 | 55.08 | 18.56 | 1.01 |
| 5| 6473 | 65.14 | 22.00 | 1.12 |
| 6| 6506 | 71.16 | 23.96 | 1.18 |
| 7| 6617 | 79.04 | 26.53 | 1.27 |
| 8| 6793 | 91.23 | 30.73 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1140 | 6514 | 59.73 | 22.44 | 1.08 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

