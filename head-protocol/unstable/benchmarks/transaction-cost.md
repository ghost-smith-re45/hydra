--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-07 07:04:56.985922012 UTC |
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
| 1| 5837 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6240 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.91 | 12.57 | 0.63 |
| 4 | 225 | 858 | 49.12 | 14.23 | 0.69 |
| 5 | 282 | 969 | 62.78 | 17.90 | 0.83 |
| 6 | 340 | 1081 | 75.38 | 21.36 | 0.96 |
| 7 | 394 | 1192 | 72.68 | 21.07 | 0.94 |
| 8 | 450 | 1307 | 96.43 | 27.16 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1956 | 25.76 | 8.76 | 0.51 |
| 3| 2121 | 28.43 | 10.17 | 0.55 |
| 5| 2486 | 33.28 | 12.87 | 0.62 |
| 10| 3221 | 42.24 | 18.71 | 0.77 |
| 41| 7751 | 98.24 | 54.94 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.54 | 7.31 | 0.41 |
| 2| 767 | 24.32 | 8.46 | 0.44 |
| 3| 903 | 25.82 | 9.54 | 0.47 |
| 5| 1306 | 32.25 | 12.67 | 0.56 |
| 10| 2011 | 39.66 | 18.08 | 0.69 |
| 39| 6282 | 92.57 | 52.12 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.13 | 8.90 | 0.48 |
| 2| 814 | 29.22 | 9.61 | 0.49 |
| 3| 958 | 30.94 | 10.75 | 0.52 |
| 5| 1250 | 36.95 | 13.76 | 0.60 |
| 10| 2072 | 45.49 | 19.55 | 0.75 |
| 36| 5911 | 96.57 | 51.19 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 761 | 35.17 | 11.17 | 0.55 |
| 3| 971 | 37.95 | 12.63 | 0.59 |
| 5| 1346 | 43.96 | 15.68 | 0.68 |
| 10| 1987 | 53.57 | 21.67 | 0.83 |
| 29| 4868 | 97.53 | 46.55 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.00 | 9.08 | 0.69 |
| 2| 5870 | 34.88 | 11.68 | 0.77 |
| 3| 6136 | 46.02 | 15.51 | 0.90 |
| 4| 6331 | 56.27 | 19.01 | 1.02 |
| 5| 6468 | 65.17 | 22.02 | 1.12 |
| 6| 6563 | 70.80 | 23.87 | 1.18 |
| 7| 6914 | 85.56 | 28.95 | 1.35 |
| 8| 6948 | 94.14 | 31.69 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.05 | 6.02 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 37.74 | 13.85 | 0.83 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1704 | 6850 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2159 | 7121 | 96.00 | 36.77 | 1.50 |

