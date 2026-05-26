--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-26 08:55:24.543541714 UTC |
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
| 1| 5837 | 10.85 | 3.45 | 0.52 |
| 2| 6039 | 12.54 | 3.97 | 0.55 |
| 3| 6236 | 15.07 | 4.78 | 0.58 |
| 5| 6640 | 18.52 | 5.84 | 0.63 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 751 | 43.73 | 12.51 | 0.63 |
| 4 | 226 | 858 | 49.37 | 14.24 | 0.69 |
| 5 | 284 | 969 | 57.82 | 16.71 | 0.78 |
| 6 | 339 | 1081 | 69.57 | 19.89 | 0.90 |
| 7 | 394 | 1192 | 87.06 | 24.56 | 1.08 |
| 8 | 451 | 1303 | 81.01 | 23.47 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1880 | 24.40 | 8.39 | 0.49 |
| 3| 2078 | 27.39 | 9.88 | 0.53 |
| 5| 2449 | 33.65 | 12.96 | 0.62 |
| 10| 3310 | 43.24 | 19.00 | 0.78 |
| 40| 7542 | 96.17 | 53.70 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.37 | 0.41 |
| 2| 831 | 25.44 | 8.77 | 0.46 |
| 3| 920 | 26.98 | 9.87 | 0.48 |
| 5| 1271 | 31.27 | 12.39 | 0.55 |
| 10| 2082 | 40.79 | 18.38 | 0.70 |
| 41| 6575 | 99.18 | 55.23 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 29.17 | 8.91 | 0.48 |
| 2| 858 | 29.97 | 9.84 | 0.50 |
| 3| 942 | 30.90 | 10.74 | 0.52 |
| 5| 1219 | 36.99 | 13.77 | 0.60 |
| 10| 2083 | 45.34 | 19.51 | 0.75 |
| 36| 5880 | 95.85 | 51.01 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 810 | 35.92 | 11.40 | 0.56 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1253 | 42.57 | 15.26 | 0.66 |
| 10| 1987 | 53.20 | 21.55 | 0.82 |
| 30| 4889 | 98.79 | 47.53 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 5879 | 32.53 | 10.87 | 0.75 |
| 3| 6132 | 45.46 | 15.36 | 0.90 |
| 4| 6281 | 54.79 | 18.43 | 1.00 |
| 5| 6240 | 56.07 | 18.75 | 1.01 |
| 6| 6408 | 69.76 | 23.42 | 1.16 |
| 7| 6792 | 85.17 | 28.74 | 1.34 |
| 8| 7004 | 91.88 | 31.07 | 1.42 |
| 9| 6878 | 95.49 | 32.06 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1136 | 6510 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2277 | 7194 | 99.66 | 38.24 | 1.55 |

