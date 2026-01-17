--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-17 04:47:29.201731268 UTC |
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
| 2| 6035 | 13.08 | 4.16 | 0.55 |
| 3| 6239 | 14.69 | 4.65 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.90 | 9.10 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 39.85 | 11.58 | 0.59 |
| 4 | 225 | 858 | 47.78 | 13.91 | 0.67 |
| 5 | 283 | 969 | 64.40 | 18.29 | 0.85 |
| 6 | 338 | 1081 | 70.96 | 20.18 | 0.92 |
| 7 | 395 | 1196 | 76.35 | 21.91 | 0.98 |
| 8 | 449 | 1303 | 96.59 | 27.20 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.29 | 7.69 | 0.48 |
| 2| 1954 | 25.39 | 8.68 | 0.50 |
| 3| 2108 | 28.31 | 10.14 | 0.54 |
| 5| 2317 | 29.96 | 11.95 | 0.58 |
| 10| 3117 | 40.23 | 18.13 | 0.74 |
| 42| 7764 | 98.21 | 55.59 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 794 | 24.32 | 8.46 | 0.44 |
| 3| 1006 | 28.23 | 10.22 | 0.50 |
| 5| 1282 | 31.10 | 12.36 | 0.55 |
| 10| 1906 | 37.52 | 17.46 | 0.66 |
| 44| 6946 | 99.74 | 57.43 | 1.68 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.47 | 9.38 | 0.48 |
| 3| 941 | 30.90 | 10.74 | 0.52 |
| 5| 1275 | 34.93 | 13.22 | 0.58 |
| 10| 2104 | 46.25 | 19.78 | 0.76 |
| 34| 5545 | 92.06 | 48.58 | 1.49 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 1024 | 38.63 | 12.83 | 0.60 |
| 5| 1360 | 43.36 | 15.49 | 0.67 |
| 10| 2152 | 55.41 | 22.22 | 0.85 |
| 29| 5032 | 99.87 | 47.27 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 27.08 | 9.09 | 0.69 |
| 2| 5895 | 32.56 | 10.90 | 0.75 |
| 3| 6063 | 44.65 | 15.01 | 0.89 |
| 4| 6138 | 50.80 | 17.04 | 0.95 |
| 5| 6367 | 60.57 | 20.35 | 1.07 |
| 6| 6579 | 73.62 | 24.81 | 1.21 |
| 7| 6836 | 85.66 | 28.91 | 1.35 |
| 8| 6775 | 88.93 | 29.94 | 1.38 |
| 9| 7100 | 98.50 | 33.17 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1710 | 6857 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2213 | 7153 | 99.12 | 37.95 | 1.54 |

