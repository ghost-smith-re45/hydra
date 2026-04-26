--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-26 07:18:08.290468622 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6242 | 14.76 | 4.67 | 0.58 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7650 | 29.49 | 9.31 | 0.79 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 169 | 751 | 40.32 | 11.73 | 0.59 |
| 4 | 227 | 858 | 49.48 | 14.29 | 0.69 |
| 5 | 282 | 969 | 57.84 | 16.66 | 0.78 |
| 6 | 338 | 1081 | 67.62 | 19.38 | 0.88 |
| 7 | 394 | 1196 | 73.95 | 21.33 | 0.95 |
| 8 | 451 | 1307 | 86.51 | 24.73 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.00 | 7.62 | 0.48 |
| 2| 1977 | 26.96 | 9.09 | 0.52 |
| 3| 2014 | 26.24 | 9.56 | 0.52 |
| 5| 2317 | 30.18 | 12.00 | 0.58 |
| 10| 3153 | 40.74 | 18.29 | 0.75 |
| 40| 7634 | 99.93 | 54.72 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 786 | 23.55 | 8.22 | 0.43 |
| 3| 906 | 25.10 | 9.32 | 0.46 |
| 5| 1201 | 29.97 | 12.03 | 0.53 |
| 10| 1878 | 37.53 | 17.47 | 0.66 |
| 39| 6316 | 92.08 | 52.01 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.50 | 8.46 | 0.46 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 948 | 30.90 | 10.74 | 0.52 |
| 5| 1275 | 34.85 | 13.20 | 0.58 |
| 10| 2135 | 46.22 | 19.77 | 0.76 |
| 37| 5887 | 97.11 | 51.95 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 831 | 35.85 | 11.38 | 0.56 |
| 3| 953 | 37.80 | 12.59 | 0.59 |
| 5| 1314 | 43.25 | 15.47 | 0.67 |
| 10| 1973 | 53.42 | 21.61 | 0.82 |
| 29| 4851 | 98.58 | 46.87 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 26.97 | 9.06 | 0.69 |
| 2| 5893 | 34.87 | 11.67 | 0.78 |
| 3| 6093 | 44.80 | 15.09 | 0.89 |
| 4| 6107 | 46.95 | 15.67 | 0.91 |
| 5| 6389 | 60.20 | 20.20 | 1.06 |
| 6| 6512 | 70.06 | 23.58 | 1.17 |
| 7| 6836 | 84.87 | 28.72 | 1.34 |
| 8| 6635 | 83.52 | 27.90 | 1.32 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.68 | 6.24 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 283 | 6002 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2217 | 7156 | 98.24 | 37.65 | 1.53 |

