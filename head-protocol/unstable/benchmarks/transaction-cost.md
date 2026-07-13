--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-13 08:14:07.103855098 UTC |
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
| 1| 5836 | 11.04 | 3.52 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 41.18 | 11.91 | 0.60 |
| 4 | 227 | 858 | 52.34 | 14.98 | 0.72 |
| 5 | 284 | 969 | 61.49 | 17.60 | 0.82 |
| 6 | 338 | 1081 | 69.80 | 19.95 | 0.91 |
| 7 | 394 | 1192 | 75.11 | 21.70 | 0.97 |
| 8 | 449 | 1303 | 91.84 | 26.16 | 1.14 |
| 9 | 505 | 1414 | 92.08 | 26.69 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.00 | 7.62 | 0.48 |
| 2| 1979 | 26.55 | 9.00 | 0.52 |
| 3| 2146 | 27.93 | 10.05 | 0.54 |
| 5| 2430 | 32.40 | 12.62 | 0.61 |
| 10| 3139 | 40.89 | 18.32 | 0.75 |
| 40| 7361 | 92.32 | 52.63 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.84 | 7.39 | 0.41 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 930 | 26.90 | 9.86 | 0.48 |
| 5| 1205 | 28.95 | 11.73 | 0.52 |
| 10| 2023 | 41.43 | 18.57 | 0.71 |
| 41| 6752 | 99.49 | 55.38 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 27.50 | 8.46 | 0.46 |
| 2| 840 | 29.19 | 9.60 | 0.49 |
| 3| 864 | 31.97 | 11.00 | 0.53 |
| 5| 1286 | 37.54 | 13.94 | 0.61 |
| 10| 1989 | 47.55 | 20.07 | 0.77 |
| 36| 6003 | 97.96 | 51.59 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 948 | 37.84 | 12.60 | 0.59 |
| 5| 1282 | 42.68 | 15.29 | 0.66 |
| 10| 2011 | 54.05 | 21.81 | 0.83 |
| 29| 4821 | 97.46 | 46.54 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 27.09 | 9.08 | 0.69 |
| 2| 6054 | 36.72 | 12.40 | 0.80 |
| 3| 6093 | 44.96 | 15.12 | 0.89 |
| 4| 6069 | 49.52 | 16.52 | 0.94 |
| 5| 6333 | 60.62 | 20.41 | 1.07 |
| 6| 6607 | 71.46 | 24.10 | 1.19 |
| 7| 6721 | 83.70 | 28.23 | 1.33 |
| 8| 6742 | 88.62 | 29.86 | 1.38 |
| 9| 6941 | 99.74 | 33.69 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.85 | 7.43 | 0.64 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

