--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-18 06:47:14.618697065 UTC |
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
| 1| 5837 | 10.26 | 3.25 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.97 | 4.75 | 0.58 |
| 5| 6641 | 18.90 | 5.97 | 0.64 |
| 10| 7651 | 28.73 | 9.04 | 0.78 |
| 43| 14283 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 41.27 | 11.92 | 0.60 |
| 4 | 227 | 862 | 51.29 | 14.75 | 0.71 |
| 5 | 285 | 969 | 56.25 | 16.34 | 0.77 |
| 6 | 338 | 1081 | 68.51 | 19.71 | 0.89 |
| 7 | 394 | 1192 | 74.62 | 21.54 | 0.96 |
| 8 | 451 | 1307 | 82.85 | 23.86 | 1.05 |
| 10 | 561 | 1525 | 96.60 | 28.00 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 2012 | 26.92 | 9.08 | 0.52 |
| 3| 2069 | 26.99 | 9.78 | 0.53 |
| 5| 2468 | 32.07 | 12.54 | 0.61 |
| 10| 3118 | 40.84 | 18.31 | 0.75 |
| 39| 7412 | 94.32 | 52.51 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.32 | 0.41 |
| 2| 697 | 22.55 | 7.93 | 0.42 |
| 3| 828 | 24.09 | 9.03 | 0.45 |
| 5| 1301 | 32.41 | 12.71 | 0.56 |
| 10| 2051 | 39.83 | 18.12 | 0.69 |
| 41| 6651 | 98.93 | 55.20 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.54 | 8.47 | 0.46 |
| 2| 774 | 30.98 | 10.08 | 0.51 |
| 3| 1075 | 34.15 | 11.66 | 0.56 |
| 5| 1130 | 35.52 | 13.32 | 0.58 |
| 10| 2035 | 47.21 | 19.98 | 0.77 |
| 36| 6139 | 99.20 | 52.02 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 798 | 35.85 | 11.38 | 0.56 |
| 3| 1010 | 38.47 | 12.79 | 0.60 |
| 5| 1262 | 42.57 | 15.26 | 0.66 |
| 10| 1925 | 52.45 | 21.33 | 0.81 |
| 30| 4848 | 98.47 | 47.47 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 27.00 | 9.06 | 0.69 |
| 2| 5965 | 36.97 | 12.45 | 0.80 |
| 3| 6040 | 43.80 | 14.65 | 0.88 |
| 4| 6208 | 54.22 | 18.20 | 0.99 |
| 5| 6432 | 62.70 | 21.16 | 1.09 |
| 6| 6572 | 73.80 | 24.86 | 1.21 |
| 7| 6594 | 78.67 | 26.48 | 1.27 |
| 8| 6987 | 94.38 | 31.83 | 1.45 |
| 9| 6956 | 95.79 | 32.21 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 97.61 | 37.43 | 1.52 |

