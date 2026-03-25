--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-25 06:44:40.788444257 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.82 | 4.07 | 0.55 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7650 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 40.38 | 11.75 | 0.59 |
| 4 | 227 | 858 | 48.27 | 14.03 | 0.68 |
| 5 | 283 | 969 | 59.34 | 17.05 | 0.80 |
| 6 | 337 | 1085 | 69.94 | 20.02 | 0.91 |
| 7 | 393 | 1192 | 86.26 | 24.32 | 1.07 |
| 8 | 449 | 1303 | 92.80 | 26.39 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.37 | 7.71 | 0.48 |
| 2| 2002 | 26.55 | 9.00 | 0.52 |
| 3| 2013 | 25.91 | 9.48 | 0.52 |
| 5| 2323 | 29.81 | 11.91 | 0.58 |
| 10| 3250 | 43.15 | 18.95 | 0.78 |
| 40| 7637 | 97.61 | 54.11 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 22.81 | 7.38 | 0.42 |
| 2| 781 | 23.59 | 8.23 | 0.43 |
| 3| 892 | 25.12 | 9.34 | 0.46 |
| 5| 1164 | 28.04 | 11.48 | 0.51 |
| 10| 2074 | 41.57 | 18.60 | 0.71 |
| 40| 6601 | 99.55 | 54.70 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.50 | 8.46 | 0.46 |
| 2| 785 | 30.94 | 10.07 | 0.51 |
| 3| 960 | 33.43 | 11.44 | 0.55 |
| 5| 1226 | 37.06 | 13.78 | 0.60 |
| 10| 2073 | 48.41 | 20.34 | 0.78 |
| 34| 5608 | 91.83 | 48.54 | 1.49 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 831 | 35.89 | 11.39 | 0.56 |
| 3| 944 | 37.95 | 12.63 | 0.59 |
| 5| 1331 | 43.65 | 15.59 | 0.67 |
| 10| 1974 | 53.50 | 21.63 | 0.83 |
| 30| 4944 | 99.15 | 47.66 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.13 | 9.09 | 0.69 |
| 2| 5917 | 34.83 | 11.65 | 0.78 |
| 3| 6223 | 47.07 | 15.91 | 0.92 |
| 4| 6274 | 52.53 | 17.72 | 0.98 |
| 5| 6476 | 65.19 | 21.98 | 1.12 |
| 6| 6498 | 69.49 | 23.37 | 1.17 |
| 7| 6687 | 80.15 | 26.95 | 1.29 |
| 8| 6684 | 82.42 | 27.71 | 1.31 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1137 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 81.30 | 30.89 | 1.33 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |

