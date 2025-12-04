--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-04 04:47:31.891340157 UTC |
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
| 1| 5840 | 10.36 | 3.28 | 0.51 |
| 2| 6039 | 12.32 | 3.89 | 0.54 |
| 3| 6239 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.90 | 5.97 | 0.64 |
| 10| 7646 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10092 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 43.71 | 12.51 | 0.63 |
| 4 | 226 | 858 | 52.34 | 14.96 | 0.72 |
| 5 | 282 | 969 | 59.44 | 17.10 | 0.80 |
| 6 | 336 | 1081 | 67.84 | 19.47 | 0.89 |
| 7 | 394 | 1196 | 83.21 | 23.64 | 1.05 |
| 8 | 449 | 1303 | 87.51 | 25.07 | 1.10 |
| 9 | 506 | 1414 | 93.66 | 26.89 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 2006 | 26.42 | 8.96 | 0.52 |
| 3| 2055 | 26.86 | 9.75 | 0.53 |
| 5| 2334 | 29.97 | 11.95 | 0.58 |
| 10| 3239 | 42.98 | 18.91 | 0.78 |
| 40| 7583 | 98.49 | 54.31 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.57 | 7.31 | 0.41 |
| 2| 703 | 22.58 | 7.96 | 0.42 |
| 3| 892 | 25.13 | 9.33 | 0.46 |
| 5| 1158 | 28.49 | 11.60 | 0.52 |
| 10| 2221 | 44.20 | 19.33 | 0.74 |
| 40| 6477 | 96.79 | 53.94 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.13 | 8.90 | 0.48 |
| 2| 820 | 29.22 | 9.61 | 0.49 |
| 3| 971 | 30.82 | 10.73 | 0.52 |
| 5| 1370 | 35.76 | 13.47 | 0.60 |
| 10| 2093 | 49.01 | 20.51 | 0.79 |
| 37| 6232 | 98.94 | 52.57 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.87 | 10.16 | 0.53 |
| 2| 857 | 36.56 | 11.60 | 0.57 |
| 3| 1034 | 38.51 | 12.80 | 0.60 |
| 5| 1275 | 42.68 | 15.29 | 0.66 |
| 10| 2108 | 54.94 | 22.08 | 0.85 |
| 28| 4787 | 97.48 | 45.92 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5798 | 27.13 | 9.09 | 0.69 |
| 2| 5845 | 31.52 | 10.48 | 0.74 |
| 3| 6065 | 41.40 | 13.84 | 0.85 |
| 4| 6044 | 43.41 | 14.41 | 0.87 |
| 5| 6327 | 59.72 | 20.01 | 1.06 |
| 6| 6584 | 71.06 | 23.86 | 1.19 |
| 7| 6510 | 74.13 | 24.85 | 1.21 |
| 8| 6790 | 85.51 | 28.77 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 22.29 | 7.58 | 0.64 |
| 10 | 5 | 285 | 6004 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 568 | 6172 | 40.39 | 14.75 | 0.85 |
| 10 | 30 | 1710 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

