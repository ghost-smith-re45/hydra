--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-20 06:33:57.25646101 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 19.17 | 6.07 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 41.11 | 11.90 | 0.60 |
| 4 | 226 | 858 | 53.89 | 15.35 | 0.73 |
| 5 | 284 | 969 | 57.44 | 16.56 | 0.78 |
| 6 | 340 | 1081 | 64.60 | 18.85 | 0.86 |
| 7 | 395 | 1192 | 79.10 | 22.70 | 1.01 |
| 8 | 449 | 1303 | 84.85 | 24.43 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.85 | 8.78 | 0.51 |
| 3| 2125 | 28.39 | 10.16 | 0.55 |
| 5| 2522 | 33.11 | 12.83 | 0.62 |
| 10| 3253 | 42.88 | 18.88 | 0.78 |
| 40| 7718 | 99.25 | 54.56 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.80 | 7.37 | 0.41 |
| 2| 788 | 25.31 | 8.74 | 0.45 |
| 3| 913 | 25.10 | 9.32 | 0.46 |
| 5| 1157 | 28.16 | 11.51 | 0.51 |
| 10| 1985 | 39.06 | 17.89 | 0.68 |
| 42| 6710 | 98.52 | 55.77 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 29.13 | 8.90 | 0.48 |
| 2| 842 | 31.69 | 10.29 | 0.52 |
| 3| 952 | 33.36 | 11.43 | 0.54 |
| 5| 1288 | 37.66 | 13.97 | 0.61 |
| 10| 2111 | 45.68 | 19.60 | 0.75 |
| 36| 5970 | 97.75 | 51.53 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.83 | 10.16 | 0.53 |
| 2| 814 | 35.85 | 11.38 | 0.56 |
| 3| 976 | 38.55 | 12.81 | 0.60 |
| 5| 1230 | 41.97 | 15.07 | 0.65 |
| 10| 2103 | 55.06 | 22.11 | 0.85 |
| 29| 4683 | 95.89 | 46.03 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5894 | 34.91 | 11.70 | 0.78 |
| 3| 6092 | 42.28 | 14.21 | 0.86 |
| 4| 6139 | 50.32 | 16.88 | 0.95 |
| 5| 6439 | 64.07 | 21.52 | 1.11 |
| 6| 6595 | 71.09 | 24.02 | 1.19 |
| 7| 6626 | 83.41 | 28.07 | 1.32 |
| 8| 6882 | 90.58 | 30.54 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1705 | 6851 | 81.37 | 30.91 | 1.33 |
| 10 | 38 | 2166 | 7128 | 96.44 | 36.92 | 1.51 |

