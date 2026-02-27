--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-27 06:31:17.308896568 UTC |
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
| 2| 6037 | 12.72 | 4.03 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 29.40 | 9.28 | 0.79 |
| 43| 14286 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 747 | 43.55 | 12.48 | 0.62 |
| 4 | 228 | 858 | 52.57 | 15.04 | 0.72 |
| 5 | 282 | 969 | 63.05 | 17.94 | 0.83 |
| 6 | 340 | 1081 | 63.85 | 18.52 | 0.85 |
| 7 | 396 | 1192 | 86.89 | 24.48 | 1.08 |
| 8 | 449 | 1307 | 98.96 | 27.91 | 1.21 |
| 9 | 506 | 1418 | 96.53 | 27.53 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 2013 | 26.87 | 9.07 | 0.52 |
| 3| 2064 | 27.02 | 9.79 | 0.53 |
| 5| 2402 | 32.57 | 12.66 | 0.61 |
| 10| 3340 | 43.83 | 19.16 | 0.79 |
| 40| 7706 | 97.89 | 54.18 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.77 | 7.37 | 0.42 |
| 2| 846 | 25.53 | 8.80 | 0.46 |
| 3| 854 | 24.11 | 9.04 | 0.45 |
| 5| 1245 | 30.21 | 12.08 | 0.54 |
| 10| 1898 | 36.99 | 17.32 | 0.66 |
| 42| 6610 | 97.20 | 55.39 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 27.47 | 8.46 | 0.46 |
| 2| 787 | 30.98 | 10.08 | 0.51 |
| 3| 963 | 30.94 | 10.75 | 0.52 |
| 5| 1173 | 36.20 | 13.53 | 0.59 |
| 10| 1999 | 44.04 | 19.11 | 0.73 |
| 36| 6003 | 97.37 | 51.43 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.16 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 943 | 37.91 | 12.62 | 0.59 |
| 5| 1410 | 43.99 | 15.69 | 0.68 |
| 10| 2034 | 54.40 | 21.91 | 0.84 |
| 29| 4637 | 95.86 | 46.04 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 26.97 | 9.05 | 0.69 |
| 2| 5880 | 32.54 | 10.86 | 0.75 |
| 3| 6135 | 45.83 | 15.44 | 0.90 |
| 4| 6236 | 52.71 | 17.74 | 0.98 |
| 5| 6271 | 59.36 | 19.88 | 1.05 |
| 6| 6604 | 73.83 | 24.91 | 1.22 |
| 7| 6758 | 84.48 | 28.54 | 1.34 |
| 8| 6634 | 90.81 | 30.46 | 1.40 |
| 10| 6875 | 99.71 | 33.45 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 284 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 20 | 1139 | 6514 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1709 | 6856 | 79.34 | 30.22 | 1.31 |
| 10 | 39 | 2218 | 7157 | 99.38 | 38.04 | 1.54 |

