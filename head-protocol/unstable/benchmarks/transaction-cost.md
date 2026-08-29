--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-29 12:03:35.68325063 UTC |
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
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14285 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10035 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 226 | 858 | 51.01 | 14.66 | 0.71 |
| 5 | 282 | 969 | 56.40 | 16.35 | 0.77 |
| 6 | 340 | 1081 | 71.33 | 20.31 | 0.92 |
| 7 | 394 | 1192 | 78.09 | 22.28 | 0.99 |
| 8 | 451 | 1307 | 98.18 | 27.48 | 1.20 |
| 9 | 505 | 1418 | 96.15 | 27.44 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 1969 | 26.54 | 9.00 | 0.52 |
| 3| 2061 | 26.99 | 9.78 | 0.53 |
| 5| 2348 | 29.92 | 11.94 | 0.58 |
| 10| 3209 | 41.46 | 18.50 | 0.76 |
| 40| 7728 | 98.66 | 54.42 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.32 | 0.41 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 828 | 24.06 | 9.02 | 0.45 |
| 5| 1244 | 29.56 | 11.90 | 0.53 |
| 10| 2012 | 38.70 | 17.79 | 0.68 |
| 41| 6692 | 98.39 | 55.08 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.50 | 8.46 | 0.46 |
| 2| 782 | 30.91 | 10.06 | 0.51 |
| 3| 971 | 30.94 | 10.75 | 0.52 |
| 5| 1234 | 34.18 | 13.00 | 0.57 |
| 10| 2063 | 45.69 | 19.60 | 0.75 |
| 35| 5924 | 97.10 | 50.70 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 884 | 36.60 | 11.61 | 0.57 |
| 3| 1011 | 38.55 | 12.81 | 0.60 |
| 5| 1291 | 43.13 | 15.44 | 0.67 |
| 10| 1948 | 53.31 | 21.58 | 0.82 |
| 30| 4931 | 99.45 | 47.75 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 26.97 | 9.05 | 0.69 |
| 2| 5979 | 35.85 | 12.04 | 0.79 |
| 3| 5996 | 41.60 | 13.90 | 0.85 |
| 4| 6316 | 52.16 | 17.59 | 0.98 |
| 5| 6394 | 63.59 | 21.45 | 1.10 |
| 6| 6568 | 74.18 | 25.01 | 1.22 |
| 7| 6769 | 82.98 | 27.93 | 1.32 |
| 8| 7016 | 94.71 | 32.02 | 1.45 |
| 9| 6930 | 97.45 | 32.76 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 40.13 | 14.67 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 38 | 2161 | 7124 | 97.33 | 37.23 | 1.52 |

