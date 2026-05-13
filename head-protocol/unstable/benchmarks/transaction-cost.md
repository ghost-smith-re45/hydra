--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-13 07:59:56.13238009 UTC |
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
| 1| 5836 | 10.93 | 3.49 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.48 | 4.58 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 43.75 | 12.51 | 0.63 |
| 4 | 227 | 858 | 49.43 | 14.26 | 0.69 |
| 5 | 282 | 969 | 59.18 | 17.01 | 0.79 |
| 6 | 338 | 1081 | 64.77 | 18.85 | 0.86 |
| 7 | 394 | 1192 | 87.02 | 24.51 | 1.08 |
| 8 | 450 | 1303 | 98.83 | 27.74 | 1.21 |
| 9 | 505 | 1414 | 93.48 | 26.91 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1973 | 26.38 | 8.96 | 0.51 |
| 3| 2055 | 26.98 | 9.78 | 0.53 |
| 5| 2385 | 30.92 | 12.22 | 0.59 |
| 10| 3258 | 41.39 | 18.48 | 0.76 |
| 41| 7685 | 97.67 | 54.77 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 825 | 25.37 | 8.76 | 0.45 |
| 3| 938 | 26.13 | 9.61 | 0.47 |
| 5| 1163 | 28.03 | 11.49 | 0.51 |
| 10| 2017 | 39.45 | 18.02 | 0.69 |
| 42| 6633 | 98.18 | 55.72 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.54 | 8.47 | 0.46 |
| 2| 737 | 30.27 | 9.86 | 0.50 |
| 3| 965 | 33.47 | 11.46 | 0.55 |
| 5| 1172 | 36.20 | 13.53 | 0.59 |
| 10| 2209 | 49.40 | 20.65 | 0.80 |
| 33| 5411 | 95.34 | 48.81 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 958 | 37.87 | 12.61 | 0.59 |
| 5| 1207 | 41.90 | 15.05 | 0.65 |
| 10| 1986 | 53.31 | 21.58 | 0.82 |
| 30| 4929 | 99.58 | 47.78 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.08 | 9.09 | 0.69 |
| 2| 6039 | 36.72 | 12.39 | 0.80 |
| 3| 6015 | 41.21 | 13.79 | 0.85 |
| 4| 6258 | 54.61 | 18.42 | 1.00 |
| 5| 6419 | 63.77 | 21.48 | 1.10 |
| 6| 6513 | 69.15 | 23.22 | 1.16 |
| 7| 6673 | 79.08 | 26.69 | 1.28 |
| 8| 6938 | 93.34 | 31.51 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2218 | 7157 | 99.49 | 38.08 | 1.54 |

