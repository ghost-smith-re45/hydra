--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-06 04:41:27.820566851 UTC |
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
| 1| 5840 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.88 | 4.72 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 42.62 | 12.24 | 0.62 |
| 4 | 227 | 858 | 48.29 | 14.01 | 0.68 |
| 5 | 283 | 974 | 64.43 | 18.27 | 0.85 |
| 6 | 339 | 1081 | 63.72 | 18.45 | 0.85 |
| 7 | 395 | 1192 | 76.06 | 21.88 | 0.97 |
| 8 | 450 | 1303 | 85.51 | 24.55 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.00 | 7.62 | 0.48 |
| 2| 1980 | 26.84 | 9.06 | 0.52 |
| 3| 2122 | 28.06 | 10.09 | 0.54 |
| 5| 2366 | 31.45 | 12.35 | 0.60 |
| 10| 3143 | 40.77 | 18.30 | 0.75 |
| 40| 7675 | 98.44 | 54.35 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 611 | 22.84 | 7.37 | 0.41 |
| 2| 869 | 25.57 | 8.81 | 0.46 |
| 3| 971 | 26.65 | 9.79 | 0.48 |
| 5| 1190 | 29.89 | 12.00 | 0.53 |
| 10| 2087 | 42.02 | 18.73 | 0.72 |
| 41| 6602 | 96.95 | 54.69 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.54 | 8.47 | 0.46 |
| 2| 796 | 30.98 | 10.08 | 0.51 |
| 3| 868 | 32.09 | 11.03 | 0.53 |
| 5| 1270 | 35.12 | 13.27 | 0.59 |
| 10| 2016 | 44.97 | 19.39 | 0.74 |
| 38| 6141 | 99.48 | 53.35 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 989 | 38.62 | 12.83 | 0.60 |
| 5| 1315 | 43.36 | 15.49 | 0.67 |
| 10| 1986 | 53.45 | 21.62 | 0.83 |
| 30| 4926 | 99.50 | 47.74 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.05 | 9.07 | 0.69 |
| 2| 5864 | 32.49 | 10.86 | 0.75 |
| 3| 6058 | 44.49 | 14.95 | 0.88 |
| 4| 6212 | 53.96 | 18.15 | 0.99 |
| 5| 6383 | 63.37 | 21.26 | 1.10 |
| 6| 6718 | 76.20 | 25.71 | 1.25 |
| 7| 6798 | 83.39 | 28.13 | 1.33 |
| 8| 6730 | 84.33 | 28.30 | 1.33 |
| 9| 6716 | 91.47 | 30.60 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 39 | 2219 | 7158 | 97.79 | 37.50 | 1.53 |

