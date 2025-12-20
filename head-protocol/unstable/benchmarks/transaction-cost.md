--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-20 04:40:20.677438625 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 747 | 41.36 | 11.94 | 0.60 |
| 4 | 226 | 862 | 53.78 | 15.30 | 0.73 |
| 5 | 284 | 969 | 61.04 | 17.49 | 0.81 |
| 6 | 339 | 1081 | 63.62 | 18.43 | 0.84 |
| 7 | 394 | 1192 | 84.47 | 23.85 | 1.06 |
| 8 | 449 | 1303 | 97.85 | 27.40 | 1.20 |
| 10 | 560 | 1525 | 99.35 | 28.60 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.40 | 8.40 | 0.49 |
| 3| 2115 | 28.35 | 10.15 | 0.55 |
| 5| 2337 | 30.04 | 11.97 | 0.58 |
| 10| 3387 | 44.96 | 19.47 | 0.80 |
| 41| 7741 | 99.65 | 55.31 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.81 | 7.37 | 0.42 |
| 2| 761 | 23.61 | 8.23 | 0.43 |
| 3| 917 | 26.16 | 9.61 | 0.47 |
| 5| 1282 | 31.08 | 12.35 | 0.55 |
| 10| 2156 | 43.25 | 19.07 | 0.73 |
| 43| 6786 | 98.48 | 56.43 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.54 | 8.47 | 0.46 |
| 2| 879 | 29.94 | 9.83 | 0.50 |
| 3| 918 | 32.76 | 11.24 | 0.54 |
| 5| 1172 | 36.28 | 13.55 | 0.59 |
| 10| 2016 | 47.93 | 20.20 | 0.77 |
| 36| 6024 | 98.78 | 51.88 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 891 | 37.24 | 12.41 | 0.58 |
| 5| 1247 | 42.45 | 15.23 | 0.66 |
| 10| 2001 | 53.91 | 21.77 | 0.83 |
| 29| 4903 | 97.79 | 46.67 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5800 | 27.13 | 9.09 | 0.69 |
| 2| 6013 | 37.17 | 12.52 | 0.81 |
| 3| 6089 | 44.97 | 15.10 | 0.89 |
| 4| 6193 | 51.40 | 17.26 | 0.96 |
| 5| 6446 | 65.26 | 22.02 | 1.12 |
| 6| 6556 | 69.76 | 23.49 | 1.17 |
| 7| 6647 | 79.27 | 26.70 | 1.28 |
| 8| 6829 | 88.84 | 29.82 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 38 | 2160 | 7122 | 96.44 | 36.92 | 1.51 |

