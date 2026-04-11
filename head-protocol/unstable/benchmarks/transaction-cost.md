--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-11 06:43:20.197652844 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.73 | 4.04 | 0.55 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2165 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.32 | 9.64 | 0.52 |
| 3 | 169 | 747 | 42.50 | 12.22 | 0.61 |
| 4 | 226 | 862 | 52.64 | 15.10 | 0.72 |
| 5 | 283 | 974 | 57.61 | 16.63 | 0.78 |
| 6 | 339 | 1081 | 66.32 | 19.15 | 0.87 |
| 7 | 393 | 1192 | 80.44 | 22.89 | 1.02 |
| 8 | 449 | 1303 | 98.68 | 27.70 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.00 | 7.62 | 0.48 |
| 2| 1933 | 25.76 | 8.76 | 0.51 |
| 3| 2059 | 26.98 | 9.78 | 0.53 |
| 5| 2434 | 32.37 | 12.61 | 0.61 |
| 10| 3238 | 42.59 | 18.82 | 0.77 |
| 41| 7797 | 98.21 | 54.95 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.53 | 7.30 | 0.41 |
| 2| 840 | 25.57 | 8.80 | 0.46 |
| 3| 911 | 24.99 | 9.29 | 0.46 |
| 5| 1307 | 31.37 | 12.43 | 0.55 |
| 10| 1916 | 38.35 | 17.71 | 0.67 |
| 40| 6573 | 98.95 | 54.58 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 27.51 | 8.47 | 0.46 |
| 2| 822 | 29.22 | 9.61 | 0.49 |
| 3| 1066 | 32.29 | 11.17 | 0.54 |
| 5| 1275 | 37.70 | 13.98 | 0.61 |
| 10| 2075 | 45.56 | 19.57 | 0.75 |
| 35| 6139 | 99.36 | 51.38 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.79 | 10.15 | 0.53 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 986 | 38.62 | 12.83 | 0.60 |
| 5| 1367 | 43.96 | 15.68 | 0.68 |
| 10| 2008 | 54.06 | 21.81 | 0.83 |
| 29| 4986 | 99.87 | 47.27 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.05 | 9.07 | 0.69 |
| 2| 5949 | 35.99 | 12.08 | 0.79 |
| 3| 6124 | 45.82 | 15.45 | 0.90 |
| 4| 6046 | 46.14 | 15.37 | 0.90 |
| 5| 6539 | 66.55 | 22.45 | 1.14 |
| 6| 6436 | 69.72 | 23.42 | 1.17 |
| 7| 6844 | 85.20 | 28.79 | 1.35 |
| 8| 6727 | 88.07 | 29.60 | 1.37 |
| 9| 6831 | 95.85 | 32.11 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6172 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2217 | 7156 | 99.56 | 38.10 | 1.54 |

