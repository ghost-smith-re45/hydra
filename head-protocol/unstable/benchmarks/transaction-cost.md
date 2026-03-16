--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-16 07:13:45.479563662 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6645 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 28.88 | 9.10 | 0.79 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 751 | 42.60 | 12.26 | 0.62 |
| 4 | 226 | 862 | 47.89 | 13.88 | 0.68 |
| 5 | 283 | 969 | 58.33 | 16.84 | 0.79 |
| 6 | 338 | 1081 | 76.17 | 21.59 | 0.97 |
| 7 | 394 | 1196 | 80.92 | 23.09 | 1.02 |
| 8 | 451 | 1303 | 96.02 | 27.06 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1992 | 26.96 | 9.09 | 0.52 |
| 3| 2075 | 27.31 | 9.86 | 0.53 |
| 5| 2319 | 30.08 | 11.98 | 0.58 |
| 10| 3259 | 43.08 | 18.93 | 0.78 |
| 40| 7495 | 95.19 | 53.42 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.57 | 7.32 | 0.41 |
| 2| 827 | 25.16 | 8.70 | 0.45 |
| 3| 895 | 25.06 | 9.31 | 0.46 |
| 5| 1206 | 29.22 | 11.81 | 0.52 |
| 10| 1927 | 37.62 | 17.49 | 0.67 |
| 41| 6642 | 97.69 | 54.85 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 27.50 | 8.46 | 0.46 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 868 | 32.04 | 11.02 | 0.53 |
| 5| 1238 | 36.95 | 13.76 | 0.60 |
| 10| 2072 | 48.48 | 20.36 | 0.78 |
| 37| 6082 | 98.87 | 52.52 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 760 | 35.17 | 11.17 | 0.55 |
| 3| 983 | 38.55 | 12.81 | 0.60 |
| 5| 1308 | 42.49 | 15.24 | 0.66 |
| 10| 2175 | 55.89 | 22.36 | 0.86 |
| 29| 4822 | 97.91 | 46.67 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.08 | 0.69 |
| 2| 6013 | 36.85 | 12.42 | 0.80 |
| 3| 5970 | 40.39 | 13.48 | 0.84 |
| 4| 6209 | 54.85 | 18.47 | 1.00 |
| 5| 6492 | 64.96 | 21.97 | 1.12 |
| 6| 6636 | 76.18 | 25.72 | 1.24 |
| 7| 6767 | 85.07 | 28.71 | 1.34 |
| 8| 6887 | 91.31 | 30.79 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 20 | 1139 | 6513 | 59.28 | 22.29 | 1.08 |
| 10 | 38 | 2164 | 7126 | 96.00 | 36.77 | 1.50 |

