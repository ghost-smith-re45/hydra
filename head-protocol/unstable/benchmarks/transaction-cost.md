--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-10 07:44:40.954240208 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 40.29 | 11.71 | 0.59 |
| 4 | 228 | 858 | 49.63 | 14.38 | 0.69 |
| 5 | 283 | 974 | 64.39 | 18.23 | 0.84 |
| 6 | 337 | 1081 | 69.79 | 19.98 | 0.91 |
| 7 | 396 | 1192 | 80.49 | 22.90 | 1.02 |
| 8 | 449 | 1303 | 84.19 | 24.17 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.00 | 7.62 | 0.48 |
| 2| 1925 | 25.47 | 8.69 | 0.50 |
| 3| 2055 | 26.91 | 9.76 | 0.53 |
| 5| 2365 | 30.91 | 12.22 | 0.59 |
| 10| 3111 | 39.79 | 18.02 | 0.74 |
| 41| 7796 | 98.26 | 54.97 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 622 | 22.84 | 7.38 | 0.42 |
| 2| 801 | 25.10 | 8.68 | 0.45 |
| 3| 905 | 25.03 | 9.30 | 0.46 |
| 5| 1274 | 30.13 | 12.08 | 0.54 |
| 10| 2044 | 39.68 | 18.07 | 0.69 |
| 41| 6666 | 97.83 | 54.91 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.54 | 8.47 | 0.46 |
| 2| 778 | 30.91 | 10.06 | 0.51 |
| 3| 868 | 31.97 | 11.01 | 0.53 |
| 5| 1359 | 35.98 | 13.54 | 0.60 |
| 10| 1938 | 46.91 | 19.89 | 0.76 |
| 38| 6117 | 98.71 | 53.12 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 1011 | 38.63 | 12.83 | 0.60 |
| 5| 1402 | 43.99 | 15.69 | 0.68 |
| 10| 1967 | 53.39 | 21.60 | 0.82 |
| 30| 4950 | 99.58 | 47.76 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5782 | 27.00 | 9.08 | 0.69 |
| 2| 5938 | 35.76 | 12.02 | 0.79 |
| 3| 6109 | 44.86 | 15.07 | 0.89 |
| 4| 6285 | 54.75 | 18.52 | 1.00 |
| 5| 6269 | 61.65 | 20.68 | 1.07 |
| 6| 6546 | 72.65 | 24.51 | 1.20 |
| 7| 6776 | 81.24 | 27.33 | 1.30 |
| 8| 6846 | 88.47 | 29.76 | 1.38 |
| 9| 6941 | 98.99 | 33.31 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.00 | 6.69 | 0.62 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6511 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1706 | 6852 | 80.67 | 30.67 | 1.32 |
| 10 | 38 | 2158 | 7120 | 96.88 | 37.08 | 1.51 |

