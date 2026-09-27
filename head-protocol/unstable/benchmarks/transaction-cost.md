--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-27 11:05:24.287288995 UTC |
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
| 1| 5837 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 42.22 | 12.14 | 0.61 |
| 4 | 226 | 858 | 47.99 | 13.94 | 0.68 |
| 5 | 282 | 969 | 59.70 | 17.17 | 0.80 |
| 6 | 337 | 1081 | 75.01 | 21.26 | 0.96 |
| 7 | 394 | 1192 | 84.72 | 23.96 | 1.06 |
| 8 | 448 | 1307 | 87.10 | 24.92 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 24.00 | 7.62 | 0.48 |
| 2| 1937 | 25.89 | 8.82 | 0.51 |
| 3| 2211 | 29.21 | 10.40 | 0.56 |
| 5| 2508 | 33.16 | 12.84 | 0.62 |
| 10| 3117 | 39.64 | 17.98 | 0.74 |
| 39| 7607 | 97.87 | 53.50 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 22.81 | 7.38 | 0.42 |
| 2| 810 | 25.43 | 8.78 | 0.45 |
| 3| 953 | 26.84 | 9.83 | 0.48 |
| 5| 1179 | 30.12 | 12.07 | 0.53 |
| 10| 1969 | 38.84 | 17.84 | 0.68 |
| 38| 6187 | 93.43 | 51.69 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 29.17 | 8.91 | 0.48 |
| 2| 800 | 29.18 | 9.60 | 0.49 |
| 3| 987 | 31.61 | 10.96 | 0.53 |
| 5| 1304 | 35.80 | 13.48 | 0.59 |
| 10| 1992 | 43.92 | 19.08 | 0.73 |
| 36| 6090 | 98.13 | 51.68 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.88 | 11.39 | 0.56 |
| 3| 1000 | 38.58 | 12.82 | 0.60 |
| 5| 1427 | 44.66 | 15.90 | 0.69 |
| 10| 2101 | 54.70 | 22.01 | 0.84 |
| 29| 4826 | 96.89 | 46.38 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5835 | 26.96 | 9.06 | 0.69 |
| 2| 5926 | 35.96 | 12.11 | 0.79 |
| 3| 5990 | 41.49 | 13.87 | 0.85 |
| 4| 6328 | 56.17 | 18.96 | 1.02 |
| 5| 6383 | 61.56 | 20.72 | 1.08 |
| 6| 6659 | 75.34 | 25.48 | 1.24 |
| 7| 6637 | 78.25 | 26.34 | 1.26 |
| 8| 6829 | 90.80 | 30.48 | 1.40 |
| 9| 6973 | 97.09 | 32.65 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1139 | 6513 | 60.61 | 22.74 | 1.09 |
| 10 | 38 | 2167 | 7129 | 96.44 | 36.92 | 1.51 |

