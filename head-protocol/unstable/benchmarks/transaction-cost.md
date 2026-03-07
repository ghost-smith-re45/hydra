--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-07 06:20:54.820349889 UTC |
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
| 2| 6039 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.10 | 6.05 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14285 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.99 | 12.61 | 0.63 |
| 4 | 228 | 858 | 52.43 | 14.98 | 0.72 |
| 5 | 282 | 969 | 64.46 | 18.28 | 0.85 |
| 6 | 338 | 1081 | 70.96 | 20.22 | 0.92 |
| 7 | 396 | 1192 | 76.42 | 21.88 | 0.98 |
| 8 | 450 | 1303 | 84.80 | 24.37 | 1.07 |
| 9 | 504 | 1414 | 92.23 | 26.49 | 1.15 |
| 10 | 562 | 1525 | 97.95 | 28.39 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.00 | 7.62 | 0.48 |
| 2| 1955 | 25.39 | 8.68 | 0.50 |
| 3| 2018 | 26.02 | 9.51 | 0.52 |
| 5| 2447 | 32.44 | 12.63 | 0.61 |
| 10| 3252 | 43.37 | 19.01 | 0.78 |
| 39| 7406 | 96.54 | 53.13 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 22.77 | 7.37 | 0.42 |
| 2| 792 | 24.32 | 8.46 | 0.44 |
| 3| 965 | 26.68 | 9.79 | 0.48 |
| 5| 1265 | 29.94 | 12.03 | 0.53 |
| 10| 1989 | 39.89 | 18.13 | 0.69 |
| 39| 6426 | 97.20 | 53.39 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 27.47 | 8.46 | 0.46 |
| 2| 782 | 30.98 | 10.08 | 0.51 |
| 3| 869 | 32.01 | 11.01 | 0.53 |
| 5| 1325 | 38.29 | 14.17 | 0.62 |
| 10| 2021 | 45.09 | 19.41 | 0.74 |
| 36| 6031 | 97.62 | 51.55 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.16 | 0.53 |
| 2| 872 | 36.60 | 11.61 | 0.57 |
| 3| 891 | 37.20 | 12.40 | 0.58 |
| 5| 1245 | 42.53 | 15.25 | 0.66 |
| 10| 2062 | 54.72 | 22.01 | 0.84 |
| 28| 4959 | 99.87 | 46.65 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5780 | 27.16 | 9.10 | 0.69 |
| 2| 5894 | 34.91 | 11.70 | 0.78 |
| 3| 6080 | 44.79 | 15.08 | 0.89 |
| 4| 6291 | 54.73 | 18.44 | 1.00 |
| 5| 6498 | 66.25 | 22.36 | 1.13 |
| 6| 6510 | 72.66 | 24.49 | 1.20 |
| 7| 6730 | 81.43 | 27.39 | 1.30 |
| 8| 6869 | 91.26 | 30.75 | 1.41 |
| 9| 6988 | 98.01 | 32.90 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.42 | 5.80 | 0.59 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 568 | 6172 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1710 | 6857 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2279 | 7195 | 99.84 | 38.30 | 1.55 |

