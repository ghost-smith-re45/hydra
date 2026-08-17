--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-17 06:02:06.919936097 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.84 | 4.08 | 0.55 |
| 3| 6243 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.90 | 9.10 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 169 | 747 | 40.20 | 11.68 | 0.59 |
| 4 | 226 | 862 | 51.15 | 14.72 | 0.71 |
| 5 | 282 | 969 | 59.73 | 17.18 | 0.80 |
| 6 | 340 | 1081 | 70.21 | 20.08 | 0.91 |
| 7 | 396 | 1192 | 78.43 | 22.53 | 1.00 |
| 8 | 452 | 1303 | 85.38 | 24.56 | 1.07 |
| 9 | 507 | 1414 | 96.54 | 27.70 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.37 | 7.71 | 0.48 |
| 2| 1953 | 25.84 | 8.78 | 0.51 |
| 3| 2056 | 27.03 | 9.79 | 0.53 |
| 5| 2511 | 33.31 | 12.88 | 0.62 |
| 10| 3289 | 43.34 | 19.03 | 0.78 |
| 41| 7848 | 99.57 | 55.31 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.84 | 7.38 | 0.42 |
| 2| 766 | 24.28 | 8.45 | 0.44 |
| 3| 834 | 24.02 | 9.03 | 0.45 |
| 5| 1177 | 28.70 | 11.69 | 0.52 |
| 10| 1813 | 35.45 | 16.88 | 0.64 |
| 42| 6677 | 97.35 | 55.46 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 29.13 | 8.90 | 0.48 |
| 2| 829 | 31.58 | 10.26 | 0.52 |
| 3| 941 | 32.68 | 11.22 | 0.54 |
| 5| 1330 | 35.65 | 13.44 | 0.59 |
| 10| 1967 | 44.27 | 19.17 | 0.73 |
| 36| 6227 | 99.93 | 52.22 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 849 | 36.56 | 11.60 | 0.57 |
| 3| 1001 | 38.66 | 12.84 | 0.60 |
| 5| 1199 | 42.01 | 15.08 | 0.65 |
| 10| 1931 | 52.78 | 21.41 | 0.82 |
| 30| 4926 | 99.82 | 47.83 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 26.92 | 9.04 | 0.69 |
| 2| 6007 | 37.16 | 12.54 | 0.81 |
| 3| 6021 | 41.32 | 13.85 | 0.85 |
| 4| 6256 | 54.16 | 18.19 | 0.99 |
| 5| 6315 | 62.11 | 20.84 | 1.08 |
| 6| 6496 | 70.13 | 23.57 | 1.17 |
| 7| 6800 | 85.04 | 28.74 | 1.34 |
| 8| 7013 | 96.06 | 32.49 | 1.47 |
| 9| 6940 | 99.28 | 33.40 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6005 | 29.98 | 10.65 | 0.73 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2164 | 7126 | 96.63 | 36.99 | 1.51 |

