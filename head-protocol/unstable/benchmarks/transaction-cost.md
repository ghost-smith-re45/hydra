--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-05 07:41:00.044835628 UTC |
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
| 2| 6042 | 12.63 | 4.00 | 0.55 |
| 3| 6243 | 14.67 | 4.64 | 0.58 |
| 5| 6643 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 169 | 747 | 41.36 | 11.94 | 0.60 |
| 4 | 225 | 858 | 50.36 | 14.48 | 0.70 |
| 5 | 280 | 969 | 63.14 | 17.99 | 0.83 |
| 6 | 338 | 1081 | 64.42 | 18.66 | 0.85 |
| 7 | 394 | 1192 | 81.32 | 23.23 | 1.03 |
| 8 | 449 | 1303 | 87.98 | 25.24 | 1.10 |
| 9 | 507 | 1414 | 91.22 | 26.26 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1924 | 25.81 | 8.77 | 0.51 |
| 3| 2105 | 28.30 | 10.14 | 0.54 |
| 5| 2348 | 30.39 | 12.05 | 0.59 |
| 10| 3169 | 41.12 | 18.40 | 0.75 |
| 38| 7343 | 96.34 | 52.40 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.81 | 7.37 | 0.42 |
| 2| 753 | 23.61 | 8.23 | 0.43 |
| 3| 960 | 26.80 | 9.82 | 0.48 |
| 5| 1205 | 29.04 | 11.76 | 0.52 |
| 10| 1932 | 38.38 | 17.72 | 0.67 |
| 40| 6492 | 97.25 | 54.07 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 836 | 31.69 | 10.29 | 0.52 |
| 3| 966 | 30.86 | 10.73 | 0.52 |
| 5| 1244 | 37.06 | 13.78 | 0.60 |
| 10| 1970 | 46.92 | 19.89 | 0.76 |
| 38| 6109 | 98.64 | 53.06 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 820 | 35.81 | 11.37 | 0.56 |
| 3| 956 | 37.87 | 12.61 | 0.59 |
| 5| 1246 | 42.68 | 15.29 | 0.66 |
| 10| 2000 | 53.24 | 21.56 | 0.82 |
| 29| 4816 | 99.26 | 47.04 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.05 | 9.07 | 0.69 |
| 2| 5986 | 37.05 | 12.47 | 0.80 |
| 3| 5989 | 41.41 | 13.85 | 0.85 |
| 4| 6323 | 55.35 | 18.72 | 1.01 |
| 5| 6330 | 59.63 | 19.98 | 1.05 |
| 6| 6525 | 70.24 | 23.67 | 1.18 |
| 7| 6964 | 87.00 | 29.52 | 1.37 |
| 8| 6728 | 86.01 | 28.96 | 1.35 |
| 9| 6833 | 90.77 | 30.41 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 284 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1141 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2222 | 7161 | 98.93 | 37.88 | 1.54 |

