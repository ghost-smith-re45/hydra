--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-27 04:45:02.475388573 UTC |
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
| 1| 5841 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.84 | 12.34 | 0.62 |
| 4 | 225 | 858 | 50.52 | 14.54 | 0.70 |
| 5 | 282 | 969 | 60.84 | 17.38 | 0.81 |
| 6 | 339 | 1081 | 68.26 | 19.62 | 0.89 |
| 7 | 395 | 1192 | 82.24 | 23.28 | 1.03 |
| 8 | 449 | 1303 | 94.45 | 26.79 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 23.92 | 7.60 | 0.48 |
| 2| 1988 | 26.76 | 9.04 | 0.52 |
| 3| 2070 | 26.94 | 9.77 | 0.53 |
| 5| 2417 | 32.41 | 12.62 | 0.61 |
| 10| 3143 | 40.62 | 18.26 | 0.75 |
| 40| 7739 | 99.45 | 54.62 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.80 | 7.37 | 0.42 |
| 2| 733 | 23.58 | 8.23 | 0.43 |
| 3| 914 | 26.94 | 9.85 | 0.48 |
| 5| 1174 | 28.81 | 11.71 | 0.52 |
| 10| 1932 | 38.55 | 17.76 | 0.67 |
| 42| 6718 | 98.27 | 55.72 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.09 | 8.89 | 0.48 |
| 2| 828 | 31.54 | 10.26 | 0.52 |
| 3| 1058 | 32.29 | 11.17 | 0.54 |
| 5| 1185 | 36.38 | 13.58 | 0.59 |
| 10| 1998 | 47.21 | 19.99 | 0.76 |
| 36| 5931 | 96.50 | 51.17 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.16 | 0.53 |
| 2| 799 | 35.85 | 11.38 | 0.56 |
| 3| 895 | 37.20 | 12.40 | 0.58 |
| 5| 1220 | 41.97 | 15.07 | 0.65 |
| 10| 2081 | 54.70 | 22.01 | 0.84 |
| 30| 5088 | 99.86 | 47.89 | 1.53 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.09 | 9.08 | 0.69 |
| 2| 5984 | 36.92 | 12.48 | 0.80 |
| 3| 6140 | 44.99 | 15.13 | 0.89 |
| 4| 6321 | 54.80 | 18.49 | 1.00 |
| 5| 6522 | 64.77 | 21.87 | 1.12 |
| 6| 6367 | 62.55 | 20.92 | 1.09 |
| 7| 6721 | 80.78 | 27.16 | 1.29 |
| 8| 6921 | 92.02 | 31.08 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1705 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |

