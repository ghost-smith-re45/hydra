--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-10 04:43:33.70073933 UTC |
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
| 1| 5840 | 10.76 | 3.42 | 0.52 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6238 | 14.78 | 4.68 | 0.58 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.02 | 9.14 | 0.79 |
| 43| 14283 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 751 | 41.29 | 11.92 | 0.60 |
| 4 | 225 | 862 | 49.33 | 14.28 | 0.69 |
| 5 | 282 | 969 | 56.88 | 16.56 | 0.77 |
| 6 | 339 | 1081 | 68.23 | 19.61 | 0.89 |
| 7 | 394 | 1192 | 74.08 | 21.44 | 0.96 |
| 8 | 449 | 1303 | 92.64 | 26.36 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1783 | 24.37 | 7.71 | 0.48 |
| 2| 1937 | 25.80 | 8.77 | 0.51 |
| 3| 2136 | 28.43 | 10.17 | 0.55 |
| 5| 2396 | 31.87 | 12.47 | 0.60 |
| 10| 3079 | 39.96 | 18.06 | 0.74 |
| 41| 7609 | 97.62 | 54.74 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.57 | 7.30 | 0.41 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 930 | 26.99 | 9.87 | 0.48 |
| 5| 1278 | 32.15 | 12.65 | 0.56 |
| 10| 2050 | 40.09 | 18.21 | 0.70 |
| 41| 6530 | 96.46 | 54.53 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.17 | 8.91 | 0.48 |
| 2| 896 | 29.86 | 9.81 | 0.50 |
| 3| 1016 | 31.54 | 10.94 | 0.53 |
| 5| 1328 | 35.83 | 13.49 | 0.60 |
| 10| 2038 | 47.99 | 20.22 | 0.77 |
| 38| 6184 | 99.50 | 53.31 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 825 | 35.85 | 11.38 | 0.56 |
| 3| 1037 | 39.34 | 13.05 | 0.61 |
| 5| 1305 | 43.31 | 15.48 | 0.67 |
| 10| 2133 | 55.39 | 22.22 | 0.85 |
| 29| 4790 | 96.48 | 46.27 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.09 | 9.10 | 0.69 |
| 2| 5893 | 34.79 | 11.64 | 0.77 |
| 3| 6130 | 45.69 | 15.40 | 0.90 |
| 4| 6303 | 56.09 | 18.95 | 1.02 |
| 5| 6445 | 65.39 | 22.12 | 1.12 |
| 6| 6489 | 69.97 | 23.51 | 1.17 |
| 7| 6854 | 84.60 | 28.63 | 1.34 |
| 8| 6848 | 90.59 | 30.58 | 1.40 |
| 9| 6708 | 89.64 | 29.99 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 37 | 2105 | 7091 | 94.39 | 36.12 | 1.49 |

