--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-21 09:46:01.156982439 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.81 | 9.07 | 0.78 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 42.77 | 12.32 | 0.62 |
| 4 | 228 | 858 | 49.41 | 14.28 | 0.69 |
| 5 | 281 | 969 | 58.34 | 16.85 | 0.79 |
| 6 | 337 | 1081 | 69.97 | 20.03 | 0.91 |
| 7 | 392 | 1192 | 76.27 | 21.89 | 0.98 |
| 8 | 450 | 1303 | 92.34 | 26.23 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1924 | 25.76 | 8.76 | 0.51 |
| 3| 2075 | 27.43 | 9.89 | 0.53 |
| 5| 2465 | 33.23 | 12.86 | 0.62 |
| 10| 3088 | 40.34 | 18.17 | 0.74 |
| 41| 7797 | 99.90 | 55.39 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.81 | 7.38 | 0.42 |
| 2| 783 | 24.28 | 8.45 | 0.44 |
| 3| 831 | 24.09 | 9.04 | 0.45 |
| 5| 1255 | 31.22 | 12.38 | 0.55 |
| 10| 1886 | 36.48 | 17.17 | 0.65 |
| 41| 6675 | 98.58 | 55.13 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 827 | 29.22 | 9.61 | 0.49 |
| 3| 1045 | 31.57 | 10.95 | 0.53 |
| 5| 1295 | 37.81 | 14.01 | 0.61 |
| 10| 2030 | 45.20 | 19.46 | 0.75 |
| 36| 6105 | 98.19 | 51.71 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 863 | 36.60 | 11.61 | 0.57 |
| 3| 939 | 37.88 | 12.61 | 0.59 |
| 5| 1158 | 41.29 | 14.86 | 0.64 |
| 10| 2058 | 54.70 | 22.01 | 0.84 |
| 30| 4819 | 97.73 | 47.24 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5835 | 27.05 | 9.08 | 0.69 |
| 2| 5821 | 31.52 | 10.47 | 0.74 |
| 3| 6105 | 46.25 | 15.57 | 0.90 |
| 4| 6207 | 51.61 | 17.34 | 0.97 |
| 5| 6454 | 61.57 | 20.75 | 1.08 |
| 6| 6507 | 71.95 | 24.21 | 1.19 |
| 7| 6821 | 83.98 | 28.36 | 1.33 |
| 8| 6905 | 94.55 | 31.85 | 1.45 |
| 10| 6880 | 97.90 | 32.83 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2224 | 7163 | 98.05 | 37.58 | 1.53 |

