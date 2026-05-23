--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-23 07:35:45.861073759 UTC |
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
| 1| 5841 | 10.40 | 3.30 | 0.52 |
| 2| 6038 | 12.82 | 4.07 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 751 | 43.88 | 12.56 | 0.63 |
| 4 | 226 | 858 | 49.64 | 14.33 | 0.69 |
| 5 | 282 | 969 | 62.94 | 17.91 | 0.83 |
| 6 | 337 | 1081 | 71.80 | 20.47 | 0.93 |
| 7 | 394 | 1192 | 80.66 | 22.98 | 1.02 |
| 8 | 449 | 1303 | 98.93 | 27.76 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.40 | 8.40 | 0.49 |
| 3| 2132 | 28.38 | 10.16 | 0.55 |
| 5| 2448 | 32.60 | 12.67 | 0.61 |
| 10| 3169 | 40.73 | 18.29 | 0.75 |
| 42| 7707 | 99.15 | 55.83 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 22.54 | 7.31 | 0.41 |
| 2| 698 | 22.55 | 7.93 | 0.42 |
| 3| 948 | 26.63 | 9.79 | 0.48 |
| 5| 1247 | 30.75 | 12.26 | 0.54 |
| 10| 2005 | 38.48 | 17.73 | 0.68 |
| 40| 6137 | 90.82 | 52.29 | 1.53 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 778 | 30.91 | 10.06 | 0.51 |
| 3| 911 | 32.76 | 11.24 | 0.54 |
| 5| 1244 | 37.06 | 13.79 | 0.60 |
| 10| 2064 | 48.20 | 20.27 | 0.78 |
| 35| 5947 | 96.11 | 50.46 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 820 | 35.81 | 11.37 | 0.56 |
| 3| 892 | 37.24 | 12.41 | 0.58 |
| 5| 1245 | 42.65 | 15.28 | 0.66 |
| 10| 2243 | 57.24 | 22.79 | 0.88 |
| 28| 4670 | 95.50 | 45.33 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.04 | 9.08 | 0.69 |
| 2| 5940 | 35.97 | 12.09 | 0.79 |
| 3| 6129 | 45.81 | 15.45 | 0.90 |
| 4| 6305 | 56.30 | 18.96 | 1.02 |
| 5| 6527 | 66.67 | 22.48 | 1.14 |
| 6| 6712 | 76.58 | 25.90 | 1.25 |
| 7| 6719 | 78.31 | 26.41 | 1.27 |
| 8| 6755 | 85.57 | 28.74 | 1.35 |
| 9| 6991 | 99.20 | 33.42 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 10 | 568 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2222 | 7162 | 98.86 | 37.86 | 1.54 |

