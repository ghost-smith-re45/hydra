--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-06 09:38:53.142394245 UTC |
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
| 1| 5841 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6643 | 18.71 | 5.91 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 42.88 | 12.36 | 0.62 |
| 4 | 228 | 858 | 52.35 | 14.96 | 0.72 |
| 5 | 282 | 969 | 64.12 | 18.19 | 0.84 |
| 6 | 339 | 1081 | 63.88 | 18.49 | 0.85 |
| 7 | 393 | 1192 | 82.57 | 23.44 | 1.04 |
| 8 | 450 | 1303 | 96.48 | 27.17 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.93 | 7.32 | 0.47 |
| 2| 1925 | 25.47 | 8.70 | 0.50 |
| 3| 2055 | 27.06 | 9.80 | 0.53 |
| 5| 2387 | 31.33 | 12.32 | 0.60 |
| 10| 3174 | 41.54 | 18.52 | 0.76 |
| 42| 7784 | 99.81 | 56.03 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.81 | 7.37 | 0.42 |
| 2| 839 | 25.52 | 8.81 | 0.46 |
| 3| 924 | 26.79 | 9.82 | 0.48 |
| 5| 1236 | 29.89 | 12.01 | 0.53 |
| 10| 1813 | 35.67 | 16.94 | 0.64 |
| 44| 6936 | 99.87 | 57.50 | 1.68 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.17 | 8.91 | 0.48 |
| 2| 775 | 28.47 | 9.38 | 0.48 |
| 3| 945 | 30.87 | 10.74 | 0.52 |
| 5| 1194 | 36.35 | 13.57 | 0.59 |
| 10| 1977 | 44.26 | 19.17 | 0.73 |
| 35| 6003 | 97.47 | 50.86 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 711 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 1005 | 38.59 | 12.82 | 0.60 |
| 5| 1256 | 42.45 | 15.23 | 0.66 |
| 10| 1963 | 52.78 | 21.43 | 0.82 |
| 29| 4824 | 97.53 | 46.57 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 27.08 | 9.09 | 0.69 |
| 2| 5970 | 37.01 | 12.50 | 0.80 |
| 3| 5993 | 40.61 | 13.56 | 0.84 |
| 4| 6139 | 50.38 | 16.86 | 0.95 |
| 5| 6453 | 64.71 | 21.85 | 1.11 |
| 6| 6538 | 73.02 | 24.51 | 1.20 |
| 7| 6784 | 84.15 | 28.44 | 1.33 |
| 8| 6815 | 90.11 | 30.35 | 1.40 |
| 9| 6786 | 89.69 | 30.15 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 37 | 2108 | 7094 | 94.58 | 36.18 | 1.49 |

