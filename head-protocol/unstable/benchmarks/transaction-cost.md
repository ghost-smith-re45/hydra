--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-02 04:36:50.533827394 UTC |
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
| 1| 5837 | 10.76 | 3.42 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 15.07 | 4.78 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 735 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 169 | 751 | 42.62 | 12.26 | 0.62 |
| 4 | 227 | 858 | 51.12 | 14.69 | 0.71 |
| 5 | 282 | 974 | 62.10 | 17.67 | 0.82 |
| 6 | 339 | 1081 | 67.47 | 19.38 | 0.88 |
| 7 | 394 | 1196 | 78.15 | 22.34 | 1.00 |
| 8 | 449 | 1303 | 87.13 | 24.93 | 1.09 |
| 10 | 560 | 1525 | 98.32 | 28.49 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1923 | 25.92 | 8.80 | 0.51 |
| 3| 2142 | 28.39 | 10.16 | 0.55 |
| 5| 2445 | 32.33 | 12.60 | 0.61 |
| 10| 3233 | 42.67 | 18.84 | 0.77 |
| 39| 7491 | 97.26 | 53.33 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 786 | 25.52 | 8.79 | 0.45 |
| 3| 896 | 25.14 | 9.33 | 0.46 |
| 5| 1243 | 30.98 | 12.31 | 0.54 |
| 10| 1929 | 39.80 | 18.10 | 0.69 |
| 42| 6687 | 97.62 | 55.54 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 796 | 30.95 | 10.07 | 0.51 |
| 3| 943 | 30.98 | 10.76 | 0.52 |
| 5| 1270 | 34.93 | 13.22 | 0.58 |
| 10| 2017 | 47.13 | 19.96 | 0.76 |
| 35| 5688 | 93.48 | 49.61 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.83 | 10.15 | 0.53 |
| 2| 816 | 35.92 | 11.40 | 0.56 |
| 3| 895 | 37.20 | 12.40 | 0.58 |
| 5| 1286 | 42.65 | 15.28 | 0.66 |
| 10| 2093 | 55.11 | 22.13 | 0.85 |
| 29| 4941 | 98.44 | 46.86 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.13 | 9.09 | 0.69 |
| 2| 5991 | 37.00 | 12.47 | 0.80 |
| 3| 6108 | 44.92 | 15.09 | 0.89 |
| 4| 6265 | 54.62 | 18.45 | 1.00 |
| 5| 6445 | 60.79 | 20.51 | 1.07 |
| 6| 6390 | 64.90 | 21.70 | 1.11 |
| 7| 6564 | 78.55 | 26.41 | 1.26 |
| 8| 6652 | 84.64 | 28.40 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

