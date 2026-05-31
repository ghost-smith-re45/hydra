--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-31 08:56:06.036030236 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6645 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 169 | 747 | 41.28 | 11.92 | 0.60 |
| 4 | 225 | 862 | 53.59 | 15.25 | 0.73 |
| 5 | 283 | 969 | 61.50 | 17.57 | 0.82 |
| 6 | 339 | 1081 | 73.23 | 20.80 | 0.94 |
| 7 | 393 | 1192 | 86.74 | 24.44 | 1.08 |
| 8 | 449 | 1303 | 80.94 | 23.45 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 23.92 | 7.60 | 0.48 |
| 2| 1938 | 25.88 | 8.79 | 0.51 |
| 3| 2117 | 28.17 | 10.11 | 0.54 |
| 5| 2456 | 31.87 | 12.49 | 0.61 |
| 10| 3256 | 42.98 | 18.91 | 0.78 |
| 39| 7201 | 90.22 | 51.38 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.57 | 7.33 | 0.41 |
| 2| 836 | 25.17 | 8.71 | 0.45 |
| 3| 947 | 26.40 | 9.70 | 0.48 |
| 5| 1197 | 30.12 | 12.07 | 0.53 |
| 10| 1968 | 38.27 | 17.68 | 0.67 |
| 41| 6710 | 98.84 | 55.23 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.17 | 8.91 | 0.48 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 969 | 30.87 | 10.74 | 0.52 |
| 5| 1300 | 34.85 | 13.20 | 0.58 |
| 10| 2034 | 47.89 | 20.17 | 0.77 |
| 35| 5777 | 94.04 | 49.81 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 871 | 36.60 | 11.61 | 0.57 |
| 3| 941 | 37.80 | 12.59 | 0.59 |
| 5| 1161 | 41.11 | 14.82 | 0.64 |
| 10| 1949 | 53.45 | 21.62 | 0.82 |
| 30| 4945 | 99.60 | 47.79 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5809 | 27.00 | 9.08 | 0.69 |
| 2| 5929 | 35.96 | 12.08 | 0.79 |
| 3| 6200 | 46.99 | 15.85 | 0.92 |
| 4| 6236 | 53.62 | 18.01 | 0.99 |
| 5| 6380 | 64.07 | 21.55 | 1.10 |
| 6| 6505 | 70.80 | 23.85 | 1.18 |
| 7| 6754 | 80.94 | 27.31 | 1.30 |
| 8| 6834 | 88.77 | 29.87 | 1.38 |
| 9| 6833 | 94.85 | 31.90 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.08 | 6.83 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1708 | 6854 | 81.81 | 31.06 | 1.34 |
| 10 | 39 | 2218 | 7157 | 97.61 | 37.43 | 1.52 |

