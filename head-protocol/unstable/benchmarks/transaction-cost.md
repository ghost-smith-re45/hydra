--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-03 04:44:35.505606569 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6042 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.80 | 9.07 | 0.78 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 43.97 | 12.61 | 0.63 |
| 4 | 227 | 858 | 49.57 | 14.32 | 0.69 |
| 5 | 282 | 974 | 60.98 | 17.44 | 0.81 |
| 6 | 340 | 1081 | 69.75 | 19.93 | 0.91 |
| 7 | 394 | 1192 | 84.47 | 23.85 | 1.06 |
| 8 | 450 | 1303 | 80.65 | 23.43 | 1.03 |
| 9 | 507 | 1418 | 88.28 | 25.60 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.37 | 7.71 | 0.48 |
| 2| 1941 | 25.47 | 8.70 | 0.50 |
| 3| 2086 | 27.32 | 9.86 | 0.53 |
| 5| 2328 | 30.38 | 12.05 | 0.59 |
| 10| 3196 | 41.42 | 18.49 | 0.76 |
| 39| 7555 | 98.91 | 53.78 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.77 | 7.36 | 0.42 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 927 | 25.03 | 9.30 | 0.46 |
| 5| 1203 | 29.93 | 12.04 | 0.53 |
| 10| 1866 | 36.41 | 17.15 | 0.65 |
| 39| 6520 | 98.19 | 53.71 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.42 | 8.68 | 0.47 |
| 2| 828 | 29.26 | 9.62 | 0.49 |
| 3| 902 | 30.26 | 10.55 | 0.51 |
| 5| 1354 | 36.40 | 13.66 | 0.60 |
| 10| 1911 | 46.62 | 19.80 | 0.75 |
| 35| 5538 | 96.95 | 50.50 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.16 | 0.53 |
| 2| 819 | 35.92 | 11.40 | 0.56 |
| 3| 996 | 38.51 | 12.80 | 0.60 |
| 5| 1276 | 42.72 | 15.30 | 0.66 |
| 10| 1945 | 53.50 | 21.63 | 0.82 |
| 30| 4916 | 99.07 | 47.65 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5799 | 27.09 | 9.08 | 0.69 |
| 2| 5975 | 36.92 | 12.44 | 0.80 |
| 3| 6014 | 41.60 | 13.93 | 0.85 |
| 4| 6350 | 57.09 | 19.30 | 1.03 |
| 5| 6415 | 64.09 | 21.57 | 1.11 |
| 6| 6521 | 73.42 | 24.67 | 1.21 |
| 7| 6845 | 85.17 | 28.78 | 1.35 |
| 8| 6637 | 83.59 | 28.04 | 1.32 |
| 9| 6964 | 99.77 | 33.53 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 284 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 571 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1141 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2164 | 7126 | 96.88 | 37.08 | 1.51 |

