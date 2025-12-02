--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-02 04:46:38.502226527 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 13.01 | 4.14 | 0.55 |
| 3| 6243 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 43.75 | 12.55 | 0.63 |
| 4 | 225 | 858 | 52.55 | 15.06 | 0.72 |
| 5 | 284 | 969 | 59.44 | 17.10 | 0.80 |
| 6 | 338 | 1081 | 69.89 | 19.97 | 0.91 |
| 7 | 396 | 1192 | 87.10 | 24.57 | 1.08 |
| 8 | 449 | 1303 | 86.87 | 24.87 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2122 | 28.02 | 10.07 | 0.54 |
| 5| 2384 | 31.49 | 12.36 | 0.60 |
| 10| 3188 | 41.67 | 18.55 | 0.76 |
| 40| 7583 | 97.47 | 54.06 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.81 | 7.38 | 0.42 |
| 2| 763 | 24.27 | 8.44 | 0.44 |
| 3| 943 | 26.61 | 9.77 | 0.48 |
| 5| 1212 | 29.18 | 11.81 | 0.52 |
| 10| 1967 | 38.68 | 17.79 | 0.68 |
| 44| 6747 | 98.33 | 57.01 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.87 | 10.05 | 0.51 |
| 3| 970 | 33.40 | 11.44 | 0.55 |
| 5| 1348 | 35.64 | 13.44 | 0.59 |
| 10| 2042 | 48.60 | 20.39 | 0.78 |
| 36| 6100 | 99.59 | 52.06 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.87 | 10.16 | 0.53 |
| 2| 761 | 35.14 | 11.16 | 0.55 |
| 3| 974 | 37.95 | 12.63 | 0.59 |
| 5| 1200 | 41.97 | 15.07 | 0.65 |
| 10| 2093 | 55.10 | 22.13 | 0.85 |
| 29| 4902 | 97.91 | 46.69 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 26.97 | 9.05 | 0.69 |
| 2| 5820 | 31.60 | 10.50 | 0.74 |
| 3| 6142 | 46.08 | 15.55 | 0.90 |
| 4| 6298 | 52.49 | 17.69 | 0.98 |
| 5| 6448 | 64.97 | 21.96 | 1.12 |
| 6| 6623 | 72.04 | 24.23 | 1.20 |
| 7| 6816 | 84.62 | 28.60 | 1.34 |
| 8| 6776 | 89.31 | 30.03 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1709 | 6855 | 80.41 | 30.59 | 1.32 |
| 10 | 39 | 2218 | 7157 | 97.61 | 37.43 | 1.52 |

