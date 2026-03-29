--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-29 07:08:54.013586143 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7650 | 29.19 | 9.21 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2164 | 12.13 | 7.25 | 0.40 |
| 54| 10078 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 747 | 42.33 | 12.19 | 0.61 |
| 4 | 227 | 858 | 54.19 | 15.47 | 0.74 |
| 5 | 280 | 969 | 58.23 | 16.82 | 0.78 |
| 6 | 339 | 1081 | 64.78 | 18.82 | 0.86 |
| 7 | 394 | 1192 | 79.12 | 22.70 | 1.01 |
| 8 | 450 | 1307 | 94.60 | 26.78 | 1.17 |
| 9 | 508 | 1414 | 92.04 | 26.62 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.00 | 7.62 | 0.48 |
| 2| 1926 | 25.47 | 8.70 | 0.50 |
| 3| 2070 | 26.87 | 9.75 | 0.53 |
| 5| 2341 | 30.00 | 11.96 | 0.58 |
| 10| 3135 | 40.68 | 18.27 | 0.75 |
| 40| 7499 | 96.40 | 53.72 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.54 | 7.31 | 0.41 |
| 2| 786 | 24.01 | 8.39 | 0.44 |
| 3| 870 | 25.16 | 9.33 | 0.46 |
| 5| 1206 | 29.10 | 11.77 | 0.52 |
| 10| 1907 | 37.54 | 17.47 | 0.66 |
| 42| 6593 | 96.73 | 55.25 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 709 | 27.50 | 8.46 | 0.46 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 940 | 30.87 | 10.74 | 0.52 |
| 5| 1131 | 35.68 | 13.36 | 0.58 |
| 10| 2087 | 45.80 | 19.63 | 0.75 |
| 37| 6213 | 99.93 | 52.82 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 939 | 37.87 | 12.61 | 0.59 |
| 5| 1348 | 43.91 | 15.67 | 0.68 |
| 10| 1955 | 53.24 | 21.56 | 0.82 |
| 29| 4838 | 98.90 | 46.95 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.96 | 9.06 | 0.69 |
| 2| 5868 | 34.99 | 11.71 | 0.78 |
| 3| 6086 | 44.65 | 15.03 | 0.89 |
| 4| 6251 | 54.97 | 18.57 | 1.00 |
| 5| 6575 | 66.56 | 22.47 | 1.14 |
| 6| 6667 | 74.65 | 25.18 | 1.23 |
| 7| 6902 | 84.71 | 28.78 | 1.35 |
| 8| 6757 | 88.27 | 29.67 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6173 | 41.02 | 14.97 | 0.86 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1705 | 6851 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2166 | 7128 | 97.51 | 37.29 | 1.52 |

