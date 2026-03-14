--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-14 06:33:13.387530164 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.71 | 5.91 | 0.64 |
| 10| 7647 | 29.21 | 9.21 | 0.79 |
| 43| 14282 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 228 | 858 | 53.82 | 15.31 | 0.73 |
| 5 | 281 | 974 | 57.72 | 16.66 | 0.78 |
| 6 | 338 | 1081 | 68.07 | 19.54 | 0.89 |
| 7 | 394 | 1190 | 84.61 | 23.89 | 1.06 |
| 8 | 450 | 1303 | 96.35 | 27.14 | 1.18 |
| 9 | 504 | 1414 | 89.78 | 26.14 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2055 | 26.98 | 9.78 | 0.53 |
| 5| 2388 | 30.93 | 12.22 | 0.59 |
| 10| 3149 | 40.86 | 18.32 | 0.75 |
| 41| 7748 | 99.48 | 55.27 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 630 | 22.84 | 7.38 | 0.42 |
| 2| 723 | 22.56 | 7.94 | 0.42 |
| 3| 873 | 25.05 | 9.32 | 0.46 |
| 5| 1147 | 28.07 | 11.48 | 0.51 |
| 10| 2115 | 42.22 | 18.80 | 0.72 |
| 41| 6658 | 98.87 | 55.18 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 29.17 | 8.91 | 0.48 |
| 2| 795 | 30.95 | 10.07 | 0.51 |
| 3| 973 | 33.36 | 11.42 | 0.54 |
| 5| 1236 | 37.03 | 13.78 | 0.60 |
| 10| 2122 | 46.14 | 19.75 | 0.76 |
| 36| 5828 | 95.16 | 50.76 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.87 | 10.16 | 0.53 |
| 2| 818 | 35.85 | 11.38 | 0.56 |
| 3| 891 | 37.13 | 12.38 | 0.58 |
| 5| 1374 | 43.99 | 15.69 | 0.68 |
| 10| 2013 | 54.36 | 21.90 | 0.84 |
| 30| 4842 | 97.36 | 47.13 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.00 | 9.07 | 0.69 |
| 2| 5992 | 35.87 | 12.06 | 0.79 |
| 3| 6160 | 46.03 | 15.50 | 0.90 |
| 4| 6251 | 51.23 | 17.21 | 0.96 |
| 5| 6510 | 64.82 | 21.88 | 1.12 |
| 6| 6570 | 72.48 | 24.43 | 1.20 |
| 7| 6790 | 82.30 | 27.71 | 1.31 |
| 8| 6755 | 91.71 | 30.89 | 1.41 |
| 9| 7100 | 99.84 | 33.71 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 22.29 | 7.58 | 0.64 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1137 | 6511 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2222 | 7161 | 98.68 | 37.80 | 1.54 |

