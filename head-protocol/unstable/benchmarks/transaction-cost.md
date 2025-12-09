--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-09 04:44:37.383057998 UTC |
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
| 1| 5834 | 10.64 | 3.38 | 0.52 |
| 2| 6035 | 13.10 | 4.17 | 0.55 |
| 3| 6236 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7644 | 29.09 | 9.17 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 41.47 | 11.99 | 0.60 |
| 4 | 226 | 858 | 48.29 | 14.01 | 0.68 |
| 5 | 282 | 969 | 58.13 | 16.82 | 0.78 |
| 6 | 338 | 1081 | 64.52 | 18.68 | 0.85 |
| 7 | 395 | 1196 | 82.70 | 23.47 | 1.04 |
| 8 | 451 | 1307 | 98.31 | 27.56 | 1.20 |
| 9 | 505 | 1418 | 91.49 | 26.44 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.37 | 7.71 | 0.48 |
| 2| 1968 | 26.84 | 9.06 | 0.52 |
| 3| 2133 | 28.09 | 10.09 | 0.54 |
| 5| 2425 | 31.72 | 12.43 | 0.60 |
| 10| 2982 | 37.77 | 17.45 | 0.71 |
| 39| 7451 | 95.45 | 52.83 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.81 | 7.37 | 0.42 |
| 2| 838 | 25.44 | 8.77 | 0.46 |
| 3| 916 | 26.12 | 9.62 | 0.47 |
| 5| 1210 | 29.73 | 11.97 | 0.53 |
| 10| 2006 | 39.69 | 18.07 | 0.69 |
| 39| 6437 | 95.35 | 52.92 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 800 | 29.22 | 9.61 | 0.49 |
| 3| 910 | 32.72 | 11.23 | 0.54 |
| 5| 1392 | 36.47 | 13.68 | 0.60 |
| 10| 2002 | 47.63 | 20.09 | 0.77 |
| 35| 5705 | 94.80 | 50.00 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 959 | 37.91 | 12.62 | 0.59 |
| 5| 1260 | 42.65 | 15.28 | 0.66 |
| 10| 2002 | 53.95 | 21.78 | 0.83 |
| 30| 4917 | 99.82 | 47.83 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 27.08 | 9.09 | 0.69 |
| 2| 5937 | 35.77 | 12.03 | 0.79 |
| 3| 6039 | 43.75 | 14.66 | 0.88 |
| 4| 6119 | 49.32 | 16.49 | 0.94 |
| 5| 6469 | 66.50 | 22.49 | 1.13 |
| 6| 6626 | 72.51 | 24.50 | 1.20 |
| 7| 6644 | 78.67 | 26.47 | 1.27 |
| 8| 6835 | 89.21 | 30.08 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 567 | 6171 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1702 | 6849 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.49 | 37.73 | 1.53 |

