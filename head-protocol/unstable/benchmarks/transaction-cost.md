--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-27 08:44:44.771745978 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6243 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 227 | 858 | 51.95 | 14.86 | 0.71 |
| 5 | 282 | 969 | 62.69 | 17.85 | 0.83 |
| 6 | 338 | 1081 | 64.13 | 18.59 | 0.85 |
| 7 | 395 | 1192 | 76.20 | 21.87 | 0.98 |
| 8 | 450 | 1307 | 86.74 | 24.79 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.40 | 8.40 | 0.49 |
| 3| 2137 | 27.93 | 10.05 | 0.54 |
| 5| 2423 | 31.91 | 12.50 | 0.60 |
| 10| 3157 | 40.81 | 18.31 | 0.75 |
| 41| 7782 | 98.04 | 54.92 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 621 | 22.57 | 7.32 | 0.41 |
| 2| 789 | 24.01 | 8.39 | 0.44 |
| 3| 970 | 26.92 | 9.85 | 0.48 |
| 5| 1135 | 28.18 | 11.53 | 0.51 |
| 10| 2112 | 41.68 | 18.65 | 0.71 |
| 42| 6736 | 99.60 | 56.09 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 708 | 27.50 | 8.46 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 951 | 30.90 | 10.74 | 0.52 |
| 5| 1305 | 37.85 | 14.02 | 0.61 |
| 10| 2078 | 47.80 | 20.17 | 0.77 |
| 36| 6204 | 99.71 | 52.18 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.87 | 10.16 | 0.53 |
| 2| 824 | 35.85 | 11.38 | 0.56 |
| 3| 1005 | 38.55 | 12.81 | 0.60 |
| 5| 1216 | 41.93 | 15.06 | 0.65 |
| 10| 2168 | 55.63 | 22.28 | 0.86 |
| 30| 4958 | 99.61 | 47.81 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5835 | 26.92 | 9.05 | 0.69 |
| 2| 5870 | 34.84 | 11.67 | 0.77 |
| 3| 6014 | 43.59 | 14.61 | 0.87 |
| 4| 6305 | 56.12 | 18.90 | 1.02 |
| 5| 6342 | 60.76 | 20.40 | 1.07 |
| 6| 6462 | 72.10 | 24.20 | 1.19 |
| 7| 6807 | 84.41 | 28.46 | 1.34 |
| 8| 6573 | 80.42 | 26.94 | 1.28 |
| 9| 7065 | 98.56 | 33.19 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.65 | 10.19 | 0.72 |
| 10 | 39 | 2218 | 7157 | 98.49 | 37.73 | 1.53 |

