--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-24 08:09:41.621975494 UTC |
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
| 1| 5836 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 13.08 | 4.16 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14286 | 99.08 | 30.97 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 747 | 42.35 | 12.18 | 0.61 |
| 4 | 227 | 858 | 50.30 | 14.46 | 0.70 |
| 5 | 280 | 969 | 61.05 | 17.49 | 0.81 |
| 6 | 340 | 1081 | 69.33 | 19.79 | 0.90 |
| 7 | 395 | 1192 | 85.98 | 24.25 | 1.07 |
| 8 | 451 | 1303 | 97.89 | 27.46 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1994 | 27.00 | 9.10 | 0.52 |
| 3| 2183 | 29.54 | 10.48 | 0.56 |
| 5| 2407 | 31.95 | 12.51 | 0.60 |
| 10| 3237 | 43.32 | 19.03 | 0.78 |
| 39| 7426 | 96.45 | 53.11 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.50 | 7.29 | 0.41 |
| 2| 763 | 24.32 | 8.46 | 0.44 |
| 3| 829 | 24.09 | 9.03 | 0.45 |
| 5| 1199 | 29.15 | 11.79 | 0.52 |
| 10| 1915 | 38.63 | 17.78 | 0.67 |
| 43| 6870 | 99.42 | 56.67 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 29.09 | 8.89 | 0.48 |
| 2| 910 | 29.82 | 9.80 | 0.50 |
| 3| 943 | 30.94 | 10.75 | 0.52 |
| 5| 1231 | 34.26 | 13.02 | 0.58 |
| 10| 1972 | 44.41 | 19.21 | 0.73 |
| 34| 5654 | 98.75 | 50.39 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.83 | 10.16 | 0.53 |
| 2| 835 | 35.92 | 11.40 | 0.56 |
| 3| 989 | 38.59 | 12.82 | 0.60 |
| 5| 1288 | 43.35 | 15.49 | 0.67 |
| 10| 1985 | 53.12 | 21.53 | 0.82 |
| 29| 4981 | 98.87 | 46.98 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.09 | 9.09 | 0.69 |
| 2| 5927 | 36.00 | 12.08 | 0.79 |
| 3| 6149 | 45.90 | 15.46 | 0.90 |
| 4| 6144 | 47.74 | 15.97 | 0.92 |
| 5| 6379 | 63.78 | 21.53 | 1.10 |
| 6| 6585 | 71.47 | 24.07 | 1.19 |
| 7| 6804 | 84.44 | 28.55 | 1.34 |
| 8| 6928 | 89.89 | 30.27 | 1.40 |
| 10| 6971 | 99.75 | 33.51 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6003 | 30.23 | 10.73 | 0.74 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 39 | 2217 | 7156 | 99.82 | 38.19 | 1.55 |

