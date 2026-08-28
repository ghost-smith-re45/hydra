--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-28 17:17:28.316552094 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6041 | 12.84 | 4.08 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10043 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 39.94 | 11.60 | 0.59 |
| 4 | 228 | 858 | 52.26 | 14.96 | 0.72 |
| 5 | 284 | 974 | 58.76 | 16.91 | 0.79 |
| 6 | 340 | 1081 | 64.33 | 18.64 | 0.85 |
| 7 | 393 | 1192 | 80.53 | 22.91 | 1.02 |
| 8 | 451 | 1303 | 89.48 | 25.50 | 1.11 |
| 9 | 507 | 1418 | 89.91 | 26.01 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 22.92 | 7.32 | 0.47 |
| 2| 1980 | 26.83 | 9.06 | 0.52 |
| 3| 2105 | 27.94 | 10.05 | 0.54 |
| 5| 2492 | 32.87 | 12.77 | 0.62 |
| 10| 3016 | 38.77 | 17.73 | 0.72 |
| 40| 7571 | 96.67 | 53.82 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.54 | 7.30 | 0.41 |
| 2| 746 | 24.04 | 8.38 | 0.44 |
| 3| 945 | 27.07 | 9.88 | 0.48 |
| 5| 1215 | 29.56 | 11.90 | 0.53 |
| 10| 2014 | 39.00 | 17.88 | 0.68 |
| 40| 6437 | 98.97 | 54.51 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.17 | 8.91 | 0.48 |
| 2| 740 | 30.23 | 9.85 | 0.50 |
| 3| 914 | 32.76 | 11.24 | 0.54 |
| 5| 1206 | 36.99 | 13.77 | 0.60 |
| 10| 1907 | 43.51 | 18.94 | 0.72 |
| 36| 6128 | 98.37 | 51.72 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 810 | 35.89 | 11.39 | 0.56 |
| 3| 1032 | 38.55 | 12.81 | 0.60 |
| 5| 1260 | 42.57 | 15.26 | 0.66 |
| 10| 1932 | 52.70 | 21.41 | 0.82 |
| 30| 4912 | 98.51 | 47.48 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5937 | 35.83 | 12.04 | 0.79 |
| 3| 5993 | 40.20 | 13.41 | 0.84 |
| 4| 6190 | 48.09 | 16.09 | 0.93 |
| 5| 6463 | 65.03 | 21.94 | 1.12 |
| 6| 6655 | 76.32 | 25.80 | 1.25 |
| 7| 6537 | 73.90 | 24.72 | 1.21 |
| 8| 7024 | 94.70 | 32.00 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.28 | 10.41 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7159 | 97.61 | 37.43 | 1.52 |

