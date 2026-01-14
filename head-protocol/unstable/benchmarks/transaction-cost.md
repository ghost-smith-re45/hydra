--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-14 05:02:37.63934727 UTC |
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
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 747 | 43.49 | 12.45 | 0.62 |
| 4 | 226 | 858 | 49.72 | 14.38 | 0.69 |
| 5 | 284 | 969 | 56.02 | 16.25 | 0.76 |
| 6 | 340 | 1081 | 73.03 | 20.75 | 0.94 |
| 7 | 394 | 1196 | 72.67 | 21.16 | 0.94 |
| 8 | 451 | 1303 | 98.71 | 27.71 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1980 | 26.92 | 9.09 | 0.52 |
| 3| 2086 | 27.36 | 9.87 | 0.53 |
| 5| 2320 | 29.97 | 11.95 | 0.58 |
| 10| 3098 | 39.70 | 18.00 | 0.74 |
| 42| 7785 | 97.79 | 55.49 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.84 | 7.40 | 0.42 |
| 2| 766 | 24.32 | 8.46 | 0.44 |
| 3| 872 | 25.85 | 9.54 | 0.47 |
| 5| 1302 | 30.60 | 12.22 | 0.54 |
| 10| 2066 | 42.00 | 18.73 | 0.72 |
| 39| 6572 | 99.20 | 53.95 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 709 | 27.54 | 8.47 | 0.47 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 993 | 33.47 | 11.46 | 0.55 |
| 5| 1226 | 34.37 | 13.04 | 0.58 |
| 10| 1966 | 44.71 | 19.30 | 0.74 |
| 33| 5720 | 94.03 | 48.53 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.88 | 11.39 | 0.56 |
| 3| 934 | 37.88 | 12.61 | 0.59 |
| 5| 1317 | 43.32 | 15.49 | 0.67 |
| 10| 2084 | 54.74 | 22.02 | 0.84 |
| 29| 4807 | 97.24 | 46.44 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.00 | 9.07 | 0.69 |
| 2| 5936 | 35.96 | 12.07 | 0.79 |
| 3| 6189 | 46.86 | 15.84 | 0.92 |
| 4| 6270 | 55.24 | 18.61 | 1.01 |
| 5| 6439 | 61.33 | 20.65 | 1.08 |
| 6| 6577 | 75.67 | 25.54 | 1.24 |
| 7| 6811 | 87.56 | 29.63 | 1.37 |
| 8| 6847 | 89.83 | 30.28 | 1.40 |
| 9| 6992 | 97.00 | 32.70 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1139 | 6513 | 61.24 | 22.96 | 1.10 |
| 10 | 39 | 2220 | 7160 | 99.82 | 38.19 | 1.55 |

