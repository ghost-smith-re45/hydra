--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-04 09:41:50.774104964 UTC |
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
| 1| 5841 | 10.93 | 3.49 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 41.46 | 11.98 | 0.60 |
| 4 | 227 | 858 | 53.98 | 15.37 | 0.73 |
| 5 | 283 | 974 | 59.43 | 17.07 | 0.80 |
| 6 | 338 | 1081 | 68.13 | 19.55 | 0.89 |
| 7 | 394 | 1192 | 76.86 | 22.12 | 0.98 |
| 8 | 449 | 1303 | 83.20 | 23.99 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.37 | 7.71 | 0.48 |
| 2| 1936 | 25.76 | 8.76 | 0.51 |
| 3| 2095 | 28.31 | 10.14 | 0.54 |
| 5| 2275 | 29.22 | 11.73 | 0.57 |
| 10| 3326 | 43.72 | 19.13 | 0.79 |
| 41| 7666 | 97.81 | 54.80 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 603 | 22.80 | 7.36 | 0.41 |
| 2| 807 | 25.47 | 8.79 | 0.45 |
| 3| 830 | 24.09 | 9.04 | 0.45 |
| 5| 1157 | 28.08 | 11.49 | 0.51 |
| 10| 2094 | 40.87 | 18.41 | 0.71 |
| 42| 6547 | 96.91 | 55.29 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.51 | 8.47 | 0.46 |
| 2| 902 | 29.86 | 9.81 | 0.50 |
| 3| 973 | 30.94 | 10.75 | 0.52 |
| 5| 1215 | 37.03 | 13.78 | 0.60 |
| 10| 2072 | 45.49 | 19.55 | 0.75 |
| 36| 5752 | 94.57 | 50.56 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.16 | 0.53 |
| 2| 887 | 36.56 | 11.60 | 0.57 |
| 3| 980 | 38.51 | 12.80 | 0.60 |
| 5| 1311 | 43.25 | 15.47 | 0.67 |
| 10| 1970 | 53.49 | 21.65 | 0.83 |
| 29| 4734 | 96.53 | 46.28 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 5920 | 36.04 | 12.09 | 0.79 |
| 3| 6117 | 44.84 | 15.08 | 0.89 |
| 4| 6283 | 52.64 | 17.72 | 0.98 |
| 5| 6329 | 57.98 | 19.47 | 1.04 |
| 6| 6634 | 74.46 | 25.07 | 1.22 |
| 7| 6961 | 88.26 | 29.89 | 1.39 |
| 8| 6743 | 87.29 | 29.39 | 1.36 |
| 9| 6938 | 98.00 | 32.97 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2217 | 7157 | 98.49 | 37.73 | 1.53 |

