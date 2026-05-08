--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-08 07:07:45.447579446 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6035 | 12.41 | 3.92 | 0.54 |
| 3| 6239 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 19.26 | 6.10 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 41.23 | 11.94 | 0.60 |
| 4 | 227 | 858 | 48.11 | 13.94 | 0.68 |
| 5 | 282 | 969 | 61.05 | 17.43 | 0.81 |
| 6 | 337 | 1081 | 75.06 | 21.24 | 0.96 |
| 7 | 394 | 1192 | 72.12 | 20.90 | 0.94 |
| 8 | 451 | 1303 | 89.99 | 25.62 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2123 | 27.94 | 10.05 | 0.54 |
| 5| 2406 | 30.97 | 12.23 | 0.59 |
| 10| 3152 | 41.43 | 18.47 | 0.76 |
| 41| 7723 | 98.15 | 54.90 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.84 | 7.38 | 0.42 |
| 2| 769 | 24.35 | 8.46 | 0.44 |
| 3| 874 | 25.13 | 9.32 | 0.46 |
| 5| 1138 | 28.18 | 11.53 | 0.51 |
| 10| 2085 | 40.51 | 18.32 | 0.70 |
| 40| 6560 | 98.37 | 54.39 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 965 | 30.94 | 10.75 | 0.52 |
| 5| 1214 | 34.18 | 13.00 | 0.57 |
| 10| 1890 | 42.91 | 18.76 | 0.72 |
| 36| 5682 | 94.20 | 50.45 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.83 | 10.15 | 0.53 |
| 2| 833 | 35.85 | 11.38 | 0.56 |
| 3| 1075 | 39.34 | 13.05 | 0.61 |
| 5| 1286 | 42.53 | 15.25 | 0.66 |
| 10| 2053 | 54.47 | 21.93 | 0.84 |
| 29| 4863 | 96.86 | 46.38 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 27.09 | 9.10 | 0.69 |
| 2| 6036 | 37.08 | 12.49 | 0.81 |
| 3| 6091 | 44.76 | 15.07 | 0.89 |
| 4| 6289 | 54.85 | 18.46 | 1.00 |
| 5| 6369 | 61.36 | 20.66 | 1.08 |
| 6| 6548 | 73.52 | 24.73 | 1.21 |
| 7| 6623 | 76.10 | 25.56 | 1.24 |
| 8| 6775 | 88.41 | 29.69 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.83 | 10.26 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1140 | 6514 | 61.05 | 22.90 | 1.10 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 36 | 2049 | 7057 | 92.34 | 35.31 | 1.46 |

