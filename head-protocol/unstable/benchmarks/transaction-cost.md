--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-13 04:41:10.441819235 UTC |
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
| 2| 6038 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14283 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 635 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 42.72 | 12.29 | 0.62 |
| 4 | 228 | 858 | 53.19 | 15.15 | 0.73 |
| 5 | 284 | 969 | 56.49 | 16.40 | 0.77 |
| 6 | 339 | 1081 | 73.82 | 20.95 | 0.95 |
| 7 | 392 | 1192 | 80.23 | 22.83 | 1.02 |
| 8 | 449 | 1303 | 97.68 | 27.45 | 1.19 |
| 9 | 506 | 1414 | 95.48 | 27.27 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.00 | 7.62 | 0.48 |
| 2| 2002 | 26.92 | 9.09 | 0.52 |
| 3| 2121 | 28.31 | 10.14 | 0.55 |
| 5| 2347 | 29.89 | 11.93 | 0.58 |
| 10| 3200 | 41.47 | 18.50 | 0.76 |
| 39| 7751 | 99.96 | 54.13 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.50 | 7.30 | 0.41 |
| 2| 764 | 23.63 | 8.24 | 0.43 |
| 3| 916 | 26.67 | 9.80 | 0.48 |
| 5| 1242 | 29.08 | 11.77 | 0.52 |
| 10| 2049 | 42.26 | 18.78 | 0.72 |
| 43| 6757 | 97.29 | 56.08 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 29.09 | 8.89 | 0.48 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 902 | 30.15 | 10.52 | 0.51 |
| 5| 1196 | 36.38 | 13.58 | 0.59 |
| 10| 1999 | 45.09 | 19.41 | 0.74 |
| 37| 5944 | 96.60 | 51.84 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.79 | 10.15 | 0.53 |
| 2| 861 | 36.56 | 11.60 | 0.57 |
| 3| 976 | 38.66 | 12.84 | 0.60 |
| 5| 1359 | 44.15 | 15.73 | 0.68 |
| 10| 1995 | 53.42 | 21.61 | 0.83 |
| 29| 4797 | 97.58 | 46.57 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 27.08 | 9.09 | 0.69 |
| 2| 6034 | 36.93 | 12.44 | 0.80 |
| 3| 6173 | 45.84 | 15.47 | 0.90 |
| 4| 6240 | 53.83 | 18.09 | 0.99 |
| 5| 6125 | 51.63 | 17.15 | 0.96 |
| 6| 6552 | 70.79 | 23.82 | 1.18 |
| 7| 6656 | 77.02 | 25.90 | 1.25 |
| 8| 6729 | 88.48 | 29.68 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1141 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1705 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.05 | 37.58 | 1.53 |

