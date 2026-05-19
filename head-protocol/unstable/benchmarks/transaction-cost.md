--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-19 08:57:30.227215814 UTC |
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
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.64 | 12.27 | 0.62 |
| 4 | 226 | 858 | 52.12 | 14.95 | 0.72 |
| 5 | 283 | 974 | 63.52 | 18.05 | 0.84 |
| 6 | 338 | 1081 | 69.36 | 19.87 | 0.90 |
| 7 | 396 | 1196 | 75.53 | 21.85 | 0.97 |
| 8 | 449 | 1303 | 83.12 | 23.97 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.37 | 7.71 | 0.48 |
| 2| 1939 | 25.51 | 8.70 | 0.50 |
| 3| 2067 | 27.31 | 9.86 | 0.53 |
| 5| 2364 | 31.34 | 12.32 | 0.60 |
| 10| 3246 | 42.66 | 18.83 | 0.77 |
| 42| 7792 | 99.41 | 55.91 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 599 | 22.57 | 7.30 | 0.41 |
| 2| 719 | 22.60 | 7.95 | 0.42 |
| 3| 828 | 24.06 | 9.02 | 0.45 |
| 5| 1319 | 32.15 | 12.64 | 0.56 |
| 10| 2128 | 43.64 | 19.17 | 0.73 |
| 40| 6651 | 99.70 | 54.78 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 819 | 29.22 | 9.61 | 0.49 |
| 3| 1065 | 32.32 | 11.18 | 0.54 |
| 5| 1214 | 36.98 | 13.77 | 0.60 |
| 10| 1976 | 47.52 | 20.06 | 0.77 |
| 35| 5979 | 97.50 | 50.84 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 819 | 36.22 | 11.49 | 0.56 |
| 3| 1012 | 38.59 | 12.82 | 0.60 |
| 5| 1274 | 42.68 | 15.29 | 0.66 |
| 10| 2068 | 55.21 | 22.15 | 0.85 |
| 30| 4874 | 99.19 | 47.63 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 27.09 | 9.08 | 0.69 |
| 2| 5845 | 31.52 | 10.48 | 0.74 |
| 3| 5997 | 41.37 | 13.85 | 0.85 |
| 4| 6273 | 55.26 | 18.63 | 1.01 |
| 5| 6353 | 60.34 | 20.26 | 1.06 |
| 6| 6523 | 70.08 | 23.53 | 1.17 |
| 7| 6561 | 82.20 | 27.67 | 1.30 |
| 8| 6853 | 89.98 | 30.33 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 571 | 6176 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1136 | 6510 | 58.66 | 22.07 | 1.07 |
| 10 | 39 | 2222 | 7162 | 98.49 | 37.73 | 1.53 |

