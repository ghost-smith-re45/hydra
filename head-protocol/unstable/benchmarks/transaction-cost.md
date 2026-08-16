--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-16 05:55:56.065393709 UTC |
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
| 1| 5834 | 10.28 | 3.25 | 0.51 |
| 2| 6035 | 12.84 | 4.08 | 0.55 |
| 3| 6236 | 14.71 | 4.65 | 0.58 |
| 5| 6645 | 18.60 | 5.87 | 0.64 |
| 10| 7646 | 29.26 | 9.23 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 40.32 | 11.73 | 0.59 |
| 4 | 228 | 858 | 53.34 | 15.19 | 0.73 |
| 5 | 281 | 969 | 56.33 | 16.36 | 0.77 |
| 6 | 339 | 1081 | 75.33 | 21.34 | 0.96 |
| 7 | 394 | 1196 | 85.32 | 24.19 | 1.07 |
| 8 | 452 | 1303 | 95.39 | 26.85 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1942 | 25.43 | 8.68 | 0.50 |
| 3| 2079 | 27.35 | 9.87 | 0.53 |
| 5| 2332 | 29.97 | 11.95 | 0.58 |
| 10| 3184 | 40.89 | 18.32 | 0.75 |
| 39| 7601 | 99.71 | 54.01 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.81 | 7.37 | 0.42 |
| 2| 759 | 23.55 | 8.22 | 0.43 |
| 3| 828 | 24.02 | 9.01 | 0.45 |
| 5| 1387 | 33.37 | 12.97 | 0.57 |
| 10| 1992 | 38.65 | 17.78 | 0.68 |
| 40| 6513 | 95.34 | 53.58 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 29.17 | 8.91 | 0.48 |
| 2| 733 | 30.23 | 9.85 | 0.50 |
| 3| 1043 | 32.37 | 11.19 | 0.54 |
| 5| 1135 | 35.52 | 13.32 | 0.58 |
| 10| 2067 | 45.49 | 19.55 | 0.75 |
| 38| 6099 | 97.65 | 52.79 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.83 | 10.15 | 0.53 |
| 2| 859 | 36.60 | 11.61 | 0.57 |
| 3| 1006 | 38.63 | 12.83 | 0.60 |
| 5| 1162 | 41.26 | 14.85 | 0.64 |
| 10| 2097 | 55.44 | 22.23 | 0.85 |
| 28| 4862 | 97.04 | 45.82 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5932 | 36.04 | 12.11 | 0.79 |
| 3| 5971 | 40.47 | 13.52 | 0.84 |
| 4| 6236 | 51.01 | 17.15 | 0.96 |
| 5| 6574 | 66.19 | 22.44 | 1.14 |
| 6| 6698 | 77.15 | 26.07 | 1.26 |
| 7| 6572 | 78.33 | 26.33 | 1.26 |
| 8| 6841 | 89.56 | 30.17 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1137 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2222 | 7162 | 98.68 | 37.80 | 1.54 |

