--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-31 04:39:31.701976894 UTC |
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
| 1| 5838 | 10.55 | 3.35 | 0.52 |
| 2| 6041 | 12.23 | 3.86 | 0.54 |
| 3| 6242 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 19.02 | 6.02 | 0.64 |
| 10| 7650 | 29.19 | 9.21 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 171 | 747 | 41.11 | 11.90 | 0.60 |
| 4 | 227 | 862 | 52.62 | 15.07 | 0.72 |
| 5 | 282 | 969 | 59.22 | 16.99 | 0.79 |
| 6 | 341 | 1085 | 66.81 | 19.31 | 0.88 |
| 7 | 392 | 1196 | 80.69 | 22.95 | 1.02 |
| 8 | 450 | 1303 | 94.72 | 26.80 | 1.17 |
| 10 | 561 | 1525 | 97.56 | 28.24 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1925 | 25.85 | 8.78 | 0.51 |
| 3| 2062 | 27.32 | 9.86 | 0.53 |
| 5| 2456 | 32.33 | 12.60 | 0.61 |
| 10| 3111 | 39.65 | 17.98 | 0.74 |
| 41| 7752 | 98.51 | 55.01 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.77 | 7.36 | 0.42 |
| 2| 774 | 23.62 | 8.25 | 0.43 |
| 3| 962 | 26.08 | 9.61 | 0.47 |
| 5| 1351 | 32.70 | 12.80 | 0.57 |
| 10| 1996 | 39.41 | 17.99 | 0.69 |
| 40| 6416 | 93.65 | 53.08 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 29.13 | 8.90 | 0.48 |
| 2| 858 | 29.86 | 9.81 | 0.50 |
| 3| 948 | 30.98 | 10.76 | 0.52 |
| 5| 1280 | 35.01 | 13.24 | 0.58 |
| 10| 1956 | 43.99 | 19.10 | 0.73 |
| 36| 5879 | 96.14 | 51.06 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 710 | 33.83 | 10.16 | 0.53 |
| 2| 884 | 36.56 | 11.60 | 0.57 |
| 3| 966 | 37.88 | 12.61 | 0.59 |
| 5| 1212 | 41.82 | 15.03 | 0.65 |
| 10| 2175 | 55.85 | 22.37 | 0.86 |
| 28| 4725 | 96.42 | 45.59 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 27.05 | 9.07 | 0.69 |
| 2| 5867 | 32.45 | 10.84 | 0.75 |
| 3| 6135 | 45.61 | 15.39 | 0.90 |
| 4| 6270 | 56.11 | 19.00 | 1.02 |
| 5| 6367 | 60.26 | 20.24 | 1.06 |
| 6| 6595 | 74.97 | 25.24 | 1.23 |
| 7| 6860 | 85.12 | 28.76 | 1.35 |
| 8| 6997 | 93.71 | 31.70 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.73 | 22.44 | 1.08 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

