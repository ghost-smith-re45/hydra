--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-17 07:31:38.553339565 UTC |
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
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 751 | 42.62 | 12.24 | 0.62 |
| 4 | 226 | 858 | 53.71 | 15.28 | 0.73 |
| 5 | 281 | 969 | 55.90 | 16.19 | 0.76 |
| 6 | 339 | 1081 | 65.95 | 19.02 | 0.87 |
| 7 | 397 | 1192 | 85.18 | 24.07 | 1.06 |
| 8 | 451 | 1303 | 94.47 | 26.79 | 1.16 |
| 9 | 507 | 1414 | 97.64 | 27.79 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1946 | 25.47 | 8.70 | 0.50 |
| 3| 2095 | 28.05 | 10.08 | 0.54 |
| 5| 2388 | 31.07 | 12.26 | 0.59 |
| 10| 3313 | 43.23 | 18.97 | 0.78 |
| 39| 7548 | 97.65 | 53.43 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.54 | 7.31 | 0.41 |
| 2| 743 | 24.04 | 8.40 | 0.44 |
| 3| 897 | 25.83 | 9.54 | 0.47 |
| 5| 1288 | 31.10 | 12.35 | 0.55 |
| 10| 1903 | 37.62 | 17.49 | 0.66 |
| 43| 6807 | 99.26 | 56.61 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 27.54 | 8.47 | 0.46 |
| 2| 852 | 31.58 | 10.27 | 0.52 |
| 3| 869 | 32.05 | 11.02 | 0.53 |
| 5| 1189 | 36.27 | 13.55 | 0.59 |
| 10| 2104 | 45.54 | 19.57 | 0.75 |
| 36| 5954 | 96.43 | 51.17 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 853 | 36.48 | 11.58 | 0.57 |
| 3| 948 | 37.91 | 12.62 | 0.59 |
| 5| 1241 | 42.64 | 15.28 | 0.66 |
| 10| 1946 | 53.53 | 21.64 | 0.82 |
| 30| 4958 | 99.21 | 47.65 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.08 | 9.09 | 0.69 |
| 2| 5973 | 35.88 | 12.05 | 0.79 |
| 3| 6108 | 44.61 | 15.00 | 0.89 |
| 4| 6217 | 53.72 | 18.03 | 0.99 |
| 5| 6311 | 59.22 | 19.83 | 1.05 |
| 6| 6462 | 68.80 | 23.04 | 1.16 |
| 7| 6755 | 83.03 | 28.01 | 1.32 |
| 8| 6804 | 87.29 | 29.39 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1140 | 6514 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.93 | 37.88 | 1.54 |

