--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-19 07:45:35.006406511 UTC |
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
| 1| 5837 | 10.74 | 3.42 | 0.52 |
| 2| 6039 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 19.02 | 6.02 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.34 | 9.42 | 0.51 |
| 3 | 170 | 747 | 40.40 | 11.75 | 0.59 |
| 4 | 227 | 858 | 49.22 | 14.21 | 0.69 |
| 5 | 285 | 969 | 61.17 | 17.49 | 0.81 |
| 6 | 341 | 1081 | 67.70 | 19.44 | 0.88 |
| 7 | 395 | 1196 | 71.72 | 20.75 | 0.93 |
| 8 | 448 | 1303 | 90.26 | 25.73 | 1.12 |
| 10 | 560 | 1525 | 99.01 | 28.57 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 24.00 | 7.62 | 0.48 |
| 2| 1883 | 24.40 | 8.39 | 0.49 |
| 3| 2013 | 25.95 | 9.49 | 0.52 |
| 5| 2422 | 32.11 | 12.55 | 0.61 |
| 10| 3151 | 40.84 | 18.31 | 0.75 |
| 39| 7765 | 99.92 | 54.10 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.84 | 7.39 | 0.42 |
| 2| 812 | 25.39 | 8.77 | 0.45 |
| 3| 918 | 25.07 | 9.31 | 0.46 |
| 5| 1197 | 28.99 | 11.74 | 0.52 |
| 10| 2136 | 43.47 | 19.12 | 0.73 |
| 40| 6480 | 99.15 | 54.60 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 844 | 29.19 | 9.60 | 0.49 |
| 3| 945 | 30.94 | 10.75 | 0.52 |
| 5| 1199 | 36.35 | 13.57 | 0.59 |
| 10| 2001 | 44.07 | 19.12 | 0.73 |
| 34| 6022 | 97.03 | 50.12 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 816 | 35.81 | 11.37 | 0.56 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1256 | 42.57 | 15.26 | 0.66 |
| 10| 2175 | 55.89 | 22.38 | 0.86 |
| 29| 4818 | 97.24 | 46.44 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.12 | 9.10 | 0.69 |
| 2| 5930 | 35.98 | 12.10 | 0.79 |
| 3| 6186 | 47.16 | 15.93 | 0.92 |
| 4| 6093 | 49.13 | 16.40 | 0.93 |
| 5| 6463 | 64.51 | 21.82 | 1.11 |
| 6| 6362 | 71.24 | 23.83 | 1.18 |
| 7| 6634 | 81.34 | 27.24 | 1.30 |
| 8| 6840 | 92.92 | 31.30 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.21 | 10.04 | 0.71 |
| 10 | 20 | 1138 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

