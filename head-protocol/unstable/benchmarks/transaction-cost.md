--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-27 16:21:03.324421252 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6238 | 14.84 | 4.71 | 0.58 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2166 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 40.22 | 11.69 | 0.59 |
| 4 | 228 | 858 | 48.12 | 13.97 | 0.68 |
| 5 | 284 | 969 | 64.50 | 18.32 | 0.85 |
| 6 | 340 | 1081 | 64.27 | 18.62 | 0.85 |
| 7 | 394 | 1192 | 83.14 | 23.67 | 1.05 |
| 8 | 449 | 1303 | 93.69 | 26.46 | 1.16 |
| 9 | 504 | 1414 | 93.91 | 26.96 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1990 | 26.76 | 9.04 | 0.52 |
| 3| 2056 | 27.40 | 9.88 | 0.53 |
| 5| 2363 | 31.12 | 12.27 | 0.59 |
| 10| 3039 | 39.01 | 17.79 | 0.73 |
| 40| 7486 | 97.25 | 53.99 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.84 | 7.38 | 0.42 |
| 2| 768 | 24.01 | 8.38 | 0.44 |
| 3| 892 | 25.16 | 9.34 | 0.46 |
| 5| 1272 | 31.13 | 12.35 | 0.55 |
| 10| 2047 | 40.72 | 18.35 | 0.70 |
| 42| 6833 | 99.07 | 55.96 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 833 | 31.62 | 10.27 | 0.52 |
| 3| 931 | 33.05 | 11.33 | 0.54 |
| 5| 1206 | 34.22 | 13.01 | 0.57 |
| 10| 1993 | 44.41 | 19.21 | 0.74 |
| 34| 5610 | 98.61 | 50.36 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.89 | 11.39 | 0.56 |
| 3| 984 | 38.62 | 12.83 | 0.60 |
| 5| 1280 | 42.53 | 15.25 | 0.66 |
| 10| 2089 | 54.65 | 21.99 | 0.84 |
| 29| 4852 | 98.62 | 46.88 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.00 | 9.06 | 0.69 |
| 2| 5894 | 34.83 | 11.66 | 0.78 |
| 3| 6084 | 45.00 | 15.10 | 0.89 |
| 4| 6112 | 50.45 | 16.89 | 0.95 |
| 5| 6480 | 65.20 | 22.03 | 1.12 |
| 6| 6460 | 71.83 | 24.16 | 1.19 |
| 7| 6481 | 72.52 | 24.30 | 1.20 |
| 8| 6950 | 93.16 | 31.42 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1705 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

