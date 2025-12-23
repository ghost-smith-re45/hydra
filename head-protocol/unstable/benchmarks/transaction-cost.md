--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-23 04:53:21.386570126 UTC |
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
| 1| 5834 | 11.12 | 3.55 | 0.52 |
| 2| 6037 | 13.10 | 4.17 | 0.55 |
| 3| 6238 | 14.88 | 4.72 | 0.58 |
| 5| 6646 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10080 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 640 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 751 | 41.29 | 11.92 | 0.60 |
| 4 | 227 | 858 | 49.44 | 14.26 | 0.69 |
| 5 | 282 | 969 | 56.08 | 16.32 | 0.76 |
| 6 | 338 | 1081 | 70.31 | 20.15 | 0.91 |
| 7 | 394 | 1192 | 78.22 | 22.35 | 1.00 |
| 8 | 451 | 1303 | 97.83 | 27.44 | 1.20 |
| 9 | 505 | 1414 | 97.31 | 27.78 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1829 | 24.29 | 7.69 | 0.48 |
| 2| 1934 | 25.92 | 8.80 | 0.51 |
| 3| 2055 | 26.98 | 9.78 | 0.53 |
| 5| 2378 | 30.97 | 12.23 | 0.59 |
| 10| 3341 | 44.08 | 19.22 | 0.79 |
| 40| 7429 | 93.90 | 53.06 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.84 | 7.38 | 0.41 |
| 2| 843 | 25.40 | 8.77 | 0.46 |
| 3| 949 | 26.68 | 9.79 | 0.48 |
| 5| 1267 | 31.15 | 12.37 | 0.55 |
| 10| 1870 | 36.50 | 17.18 | 0.65 |
| 38| 6134 | 93.59 | 51.69 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.17 | 8.91 | 0.48 |
| 2| 884 | 29.94 | 9.83 | 0.50 |
| 3| 944 | 30.82 | 10.73 | 0.52 |
| 5| 1252 | 37.02 | 13.77 | 0.60 |
| 10| 2099 | 45.38 | 19.53 | 0.75 |
| 35| 5753 | 99.30 | 51.23 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 884 | 36.60 | 11.61 | 0.57 |
| 3| 938 | 37.80 | 12.59 | 0.59 |
| 5| 1214 | 41.97 | 15.07 | 0.65 |
| 10| 2038 | 53.95 | 21.78 | 0.83 |
| 30| 5007 | 99.46 | 47.75 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.09 | 0.69 |
| 2| 5893 | 34.94 | 11.69 | 0.78 |
| 3| 6164 | 45.66 | 15.40 | 0.90 |
| 4| 6257 | 54.90 | 18.47 | 1.00 |
| 5| 6357 | 61.03 | 20.52 | 1.07 |
| 6| 6460 | 71.37 | 23.95 | 1.18 |
| 7| 6798 | 84.52 | 28.50 | 1.34 |
| 8| 7099 | 95.17 | 32.20 | 1.46 |
| 9| 6971 | 99.56 | 33.50 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1140 | 6515 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

