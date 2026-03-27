--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-27 07:00:18.026570557 UTC |
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
| 1| 5834 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.58 | 5.86 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 40.09 | 11.64 | 0.59 |
| 4 | 226 | 858 | 51.10 | 14.68 | 0.71 |
| 5 | 284 | 969 | 59.36 | 17.05 | 0.80 |
| 6 | 337 | 1085 | 68.16 | 19.59 | 0.89 |
| 7 | 394 | 1192 | 78.34 | 22.43 | 1.00 |
| 8 | 451 | 1303 | 82.65 | 23.81 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1887 | 24.43 | 8.40 | 0.49 |
| 3| 2080 | 27.43 | 9.89 | 0.53 |
| 5| 2395 | 31.15 | 12.28 | 0.60 |
| 10| 3124 | 40.47 | 18.22 | 0.75 |
| 41| 7530 | 94.77 | 53.98 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.54 | 7.31 | 0.41 |
| 2| 823 | 25.39 | 8.78 | 0.45 |
| 3| 941 | 26.71 | 9.80 | 0.48 |
| 5| 1288 | 31.21 | 12.37 | 0.55 |
| 10| 2011 | 39.01 | 17.88 | 0.68 |
| 40| 6537 | 97.26 | 54.06 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 29.17 | 8.91 | 0.48 |
| 2| 817 | 29.18 | 9.60 | 0.49 |
| 3| 928 | 32.76 | 11.24 | 0.54 |
| 5| 1211 | 34.37 | 13.04 | 0.58 |
| 10| 2073 | 48.11 | 20.24 | 0.78 |
| 36| 6125 | 99.23 | 52.01 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 939 | 37.84 | 12.60 | 0.59 |
| 5| 1310 | 43.20 | 15.46 | 0.67 |
| 10| 1934 | 52.59 | 21.36 | 0.81 |
| 30| 4971 | 99.31 | 47.73 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5796 | 26.97 | 9.05 | 0.69 |
| 2| 5998 | 36.85 | 12.42 | 0.80 |
| 3| 6172 | 47.04 | 15.88 | 0.92 |
| 4| 6342 | 54.98 | 18.51 | 1.01 |
| 5| 6291 | 56.77 | 19.03 | 1.02 |
| 6| 6373 | 62.51 | 20.93 | 1.09 |
| 7| 6603 | 78.47 | 26.38 | 1.26 |
| 8| 6949 | 90.60 | 30.57 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1707 | 6853 | 80.67 | 30.67 | 1.32 |
| 10 | 40 | 2274 | 7191 | 99.84 | 38.30 | 1.55 |
| 10 | 39 | 2219 | 7158 | 99.38 | 38.04 | 1.54 |

