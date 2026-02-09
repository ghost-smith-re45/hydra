--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-09 05:42:48.74848804 UTC |
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
| 1| 5836 | 10.26 | 3.25 | 0.51 |
| 2| 6035 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14279 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.72 | 12.29 | 0.62 |
| 4 | 226 | 858 | 52.31 | 14.97 | 0.72 |
| 5 | 285 | 969 | 62.73 | 17.86 | 0.83 |
| 6 | 338 | 1081 | 71.35 | 20.31 | 0.92 |
| 7 | 395 | 1192 | 81.34 | 23.24 | 1.03 |
| 8 | 449 | 1303 | 97.84 | 27.44 | 1.20 |
| 9 | 505 | 1414 | 95.54 | 27.29 | 1.18 |
| 10 | 561 | 1525 | 97.25 | 28.22 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1747 | 22.92 | 7.32 | 0.47 |
| 2| 2002 | 26.42 | 8.96 | 0.52 |
| 3| 2014 | 25.87 | 9.47 | 0.52 |
| 5| 2494 | 33.43 | 12.91 | 0.62 |
| 10| 3176 | 40.99 | 18.36 | 0.75 |
| 38| 7389 | 96.99 | 52.58 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.38 | 0.41 |
| 2| 771 | 24.28 | 8.45 | 0.44 |
| 3| 878 | 25.09 | 9.33 | 0.46 |
| 5| 1230 | 29.67 | 11.96 | 0.53 |
| 10| 1900 | 36.47 | 17.17 | 0.65 |
| 41| 6578 | 99.08 | 55.24 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 812 | 29.18 | 9.60 | 0.49 |
| 3| 989 | 31.57 | 10.95 | 0.53 |
| 5| 1172 | 36.35 | 13.57 | 0.59 |
| 10| 2130 | 48.69 | 20.43 | 0.78 |
| 36| 5958 | 97.06 | 51.37 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.16 | 12.39 | 0.58 |
| 5| 1276 | 42.57 | 15.26 | 0.66 |
| 10| 2007 | 53.99 | 21.79 | 0.83 |
| 29| 4998 | 98.91 | 46.99 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5832 | 27.05 | 9.08 | 0.69 |
| 2| 6000 | 37.01 | 12.48 | 0.80 |
| 3| 6061 | 41.35 | 13.85 | 0.85 |
| 4| 6239 | 53.85 | 18.08 | 0.99 |
| 5| 6388 | 64.10 | 21.56 | 1.10 |
| 6| 6649 | 75.75 | 25.54 | 1.24 |
| 7| 6448 | 71.44 | 23.87 | 1.18 |
| 8| 6853 | 89.86 | 30.25 | 1.40 |
| 9| 7040 | 98.91 | 33.28 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 38 | 2162 | 7124 | 97.95 | 37.44 | 1.53 |

