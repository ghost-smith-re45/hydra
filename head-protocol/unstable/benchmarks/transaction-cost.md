--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-08 06:26:41.27992012 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6042 | 12.34 | 3.90 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6646 | 18.52 | 5.84 | 0.63 |
| 10| 7644 | 28.88 | 9.10 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 751 | 41.12 | 11.90 | 0.60 |
| 4 | 226 | 858 | 53.57 | 15.27 | 0.73 |
| 5 | 282 | 969 | 57.74 | 16.66 | 0.78 |
| 6 | 337 | 1081 | 71.47 | 20.35 | 0.92 |
| 7 | 394 | 1192 | 76.44 | 21.97 | 0.98 |
| 8 | 450 | 1303 | 82.88 | 23.87 | 1.05 |
| 10 | 560 | 1525 | 97.58 | 28.36 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 24.00 | 7.62 | 0.48 |
| 2| 1926 | 25.85 | 8.78 | 0.51 |
| 3| 2011 | 26.31 | 9.58 | 0.52 |
| 5| 2370 | 31.29 | 12.31 | 0.60 |
| 10| 3040 | 38.70 | 17.71 | 0.72 |
| 39| 7527 | 98.58 | 53.68 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.54 | 7.30 | 0.41 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 954 | 26.97 | 9.86 | 0.48 |
| 5| 1191 | 29.14 | 11.79 | 0.52 |
| 10| 2005 | 39.97 | 18.15 | 0.69 |
| 42| 6760 | 97.45 | 55.50 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 802 | 30.90 | 10.06 | 0.51 |
| 3| 988 | 31.69 | 10.98 | 0.53 |
| 5| 1176 | 36.38 | 13.58 | 0.59 |
| 10| 1997 | 47.43 | 20.06 | 0.77 |
| 36| 6080 | 98.89 | 51.88 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 841 | 35.92 | 11.40 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1245 | 42.53 | 15.25 | 0.66 |
| 10| 1928 | 52.79 | 21.41 | 0.82 |
| 29| 4737 | 96.18 | 46.17 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 26.92 | 9.04 | 0.69 |
| 2| 6008 | 37.13 | 12.51 | 0.80 |
| 3| 6017 | 43.79 | 14.67 | 0.87 |
| 4| 6259 | 54.05 | 18.15 | 0.99 |
| 5| 6377 | 63.23 | 21.21 | 1.09 |
| 6| 6543 | 71.72 | 24.15 | 1.19 |
| 7| 6665 | 82.50 | 27.79 | 1.31 |
| 8| 6822 | 92.53 | 31.09 | 1.42 |
| 9| 6856 | 97.52 | 32.79 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 56 | 5868 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.84 | 38.30 | 1.55 |
| 10 | 37 | 2104 | 7090 | 94.13 | 36.03 | 1.48 |

