--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-16 04:51:53.591053576 UTC |
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
| 3| 6236 | 14.67 | 4.64 | 0.58 |
| 5| 6640 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 747 | 43.57 | 12.47 | 0.63 |
| 4 | 227 | 858 | 50.97 | 14.65 | 0.71 |
| 5 | 283 | 969 | 64.05 | 18.21 | 0.84 |
| 6 | 340 | 1081 | 71.25 | 20.33 | 0.92 |
| 7 | 394 | 1192 | 85.92 | 24.19 | 1.07 |
| 8 | 451 | 1303 | 97.22 | 27.45 | 1.19 |
| 9 | 505 | 1418 | 93.99 | 27.03 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.00 | 7.62 | 0.48 |
| 2| 2016 | 26.92 | 9.08 | 0.52 |
| 3| 2013 | 25.87 | 9.47 | 0.52 |
| 5| 2438 | 31.99 | 12.52 | 0.61 |
| 10| 3103 | 39.40 | 17.92 | 0.73 |
| 39| 7355 | 93.68 | 52.32 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 617 | 22.80 | 7.36 | 0.41 |
| 2| 695 | 22.58 | 7.95 | 0.42 |
| 3| 895 | 25.14 | 9.33 | 0.46 |
| 5| 1275 | 29.94 | 12.02 | 0.53 |
| 10| 1934 | 38.59 | 17.77 | 0.68 |
| 41| 6522 | 98.48 | 55.08 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.47 | 8.46 | 0.46 |
| 2| 811 | 29.19 | 9.60 | 0.49 |
| 3| 945 | 30.82 | 10.73 | 0.52 |
| 5| 1317 | 35.68 | 13.45 | 0.59 |
| 10| 2043 | 48.34 | 20.31 | 0.78 |
| 36| 5981 | 98.70 | 51.82 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.79 | 10.15 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 959 | 37.91 | 12.62 | 0.59 |
| 5| 1324 | 43.58 | 15.57 | 0.67 |
| 10| 2035 | 54.02 | 21.80 | 0.83 |
| 29| 4843 | 97.14 | 46.45 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5934 | 35.88 | 12.07 | 0.79 |
| 3| 6143 | 45.49 | 15.35 | 0.90 |
| 4| 6324 | 54.70 | 18.45 | 1.00 |
| 5| 6280 | 57.11 | 19.17 | 1.03 |
| 6| 6491 | 67.50 | 22.66 | 1.14 |
| 7| 6644 | 77.03 | 25.90 | 1.25 |
| 8| 6694 | 88.71 | 29.86 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6175 | 40.83 | 14.90 | 0.86 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1705 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |

