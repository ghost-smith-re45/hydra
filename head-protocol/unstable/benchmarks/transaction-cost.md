--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-28 04:59:15.442620865 UTC |
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
| 1| 5841 | 10.67 | 3.39 | 0.52 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 43.49 | 12.45 | 0.62 |
| 4 | 227 | 858 | 53.87 | 15.37 | 0.73 |
| 5 | 282 | 969 | 59.42 | 17.07 | 0.80 |
| 6 | 337 | 1081 | 67.05 | 19.40 | 0.88 |
| 7 | 395 | 1192 | 84.65 | 23.90 | 1.06 |
| 8 | 448 | 1307 | 94.03 | 26.58 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2098 | 27.98 | 10.06 | 0.54 |
| 5| 2406 | 32.03 | 12.51 | 0.61 |
| 10| 3198 | 41.47 | 18.50 | 0.76 |
| 39| 7422 | 96.24 | 53.06 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 783 | 24.05 | 8.39 | 0.44 |
| 3| 853 | 24.07 | 9.03 | 0.45 |
| 5| 1168 | 27.97 | 11.46 | 0.51 |
| 10| 2060 | 39.64 | 18.06 | 0.69 |
| 42| 6520 | 98.18 | 55.61 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 849 | 29.93 | 9.83 | 0.50 |
| 3| 902 | 30.26 | 10.55 | 0.51 |
| 5| 1131 | 35.56 | 13.34 | 0.58 |
| 10| 1979 | 44.37 | 19.20 | 0.73 |
| 35| 5762 | 99.65 | 51.33 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 708 | 33.87 | 10.16 | 0.53 |
| 2| 841 | 36.56 | 11.60 | 0.57 |
| 3| 947 | 37.95 | 12.63 | 0.59 |
| 5| 1199 | 42.01 | 15.08 | 0.65 |
| 10| 1972 | 53.39 | 21.60 | 0.82 |
| 29| 5045 | 99.15 | 47.07 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.05 | 9.08 | 0.69 |
| 2| 5975 | 35.88 | 12.05 | 0.79 |
| 3| 6186 | 46.02 | 15.51 | 0.91 |
| 4| 6195 | 54.20 | 18.22 | 0.99 |
| 5| 6503 | 66.01 | 22.31 | 1.13 |
| 6| 6533 | 70.96 | 23.93 | 1.18 |
| 7| 6744 | 79.53 | 26.75 | 1.28 |
| 8| 6729 | 88.93 | 29.97 | 1.38 |
| 9| 7109 | 99.61 | 33.66 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2221 | 7161 | 97.61 | 37.43 | 1.52 |

