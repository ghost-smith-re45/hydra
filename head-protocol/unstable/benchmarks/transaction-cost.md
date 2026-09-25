--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-25 10:45:20.257203154 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14281 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 40.40 | 11.75 | 0.59 |
| 4 | 226 | 858 | 48.97 | 14.17 | 0.69 |
| 5 | 281 | 974 | 57.61 | 16.63 | 0.78 |
| 6 | 339 | 1081 | 69.55 | 19.92 | 0.90 |
| 7 | 395 | 1192 | 78.43 | 22.49 | 1.00 |
| 8 | 452 | 1303 | 91.58 | 26.00 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.37 | 7.71 | 0.48 |
| 2| 1993 | 26.58 | 9.01 | 0.52 |
| 3| 2059 | 27.31 | 9.86 | 0.53 |
| 5| 2318 | 30.00 | 11.96 | 0.58 |
| 10| 3191 | 40.84 | 18.31 | 0.75 |
| 38| 7468 | 97.53 | 52.71 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 22.77 | 7.37 | 0.42 |
| 2| 752 | 23.62 | 8.24 | 0.43 |
| 3| 874 | 25.85 | 9.55 | 0.47 |
| 5| 1231 | 30.02 | 12.03 | 0.53 |
| 10| 2033 | 41.03 | 18.45 | 0.70 |
| 40| 6568 | 97.56 | 54.18 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 29.13 | 8.90 | 0.48 |
| 2| 783 | 30.91 | 10.06 | 0.51 |
| 3| 1034 | 31.65 | 10.97 | 0.53 |
| 5| 1219 | 34.33 | 13.03 | 0.58 |
| 10| 1902 | 46.23 | 19.68 | 0.75 |
| 34| 5678 | 93.23 | 48.97 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.79 | 10.15 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 947 | 37.91 | 12.62 | 0.59 |
| 5| 1296 | 42.61 | 15.27 | 0.66 |
| 10| 2035 | 53.83 | 21.75 | 0.83 |
| 30| 4996 | 99.68 | 47.85 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5782 | 27.09 | 9.10 | 0.69 |
| 2| 5954 | 35.84 | 12.05 | 0.79 |
| 3| 6042 | 43.93 | 14.73 | 0.88 |
| 4| 6265 | 54.97 | 18.49 | 1.00 |
| 5| 6260 | 59.55 | 19.93 | 1.05 |
| 6| 6630 | 73.48 | 24.74 | 1.21 |
| 7| 6830 | 84.73 | 28.65 | 1.34 |
| 8| 6710 | 84.72 | 28.41 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1140 | 6514 | 61.05 | 22.90 | 1.10 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |

