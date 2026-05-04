--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-04 07:52:02.112033814 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6236 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 19.08 | 6.04 | 0.64 |
| 10| 7651 | 28.81 | 9.07 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 40.18 | 11.66 | 0.59 |
| 4 | 227 | 858 | 48.22 | 13.99 | 0.68 |
| 5 | 281 | 969 | 64.05 | 18.18 | 0.84 |
| 6 | 337 | 1081 | 73.81 | 20.98 | 0.95 |
| 7 | 394 | 1192 | 86.55 | 24.35 | 1.08 |
| 8 | 449 | 1307 | 80.51 | 23.35 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1974 | 26.92 | 9.09 | 0.52 |
| 3| 2070 | 27.02 | 9.79 | 0.53 |
| 5| 2357 | 31.38 | 12.33 | 0.60 |
| 10| 3335 | 44.33 | 19.28 | 0.79 |
| 41| 7595 | 96.69 | 54.51 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.54 | 7.30 | 0.41 |
| 2| 816 | 25.53 | 8.79 | 0.46 |
| 3| 965 | 26.61 | 9.77 | 0.48 |
| 5| 1170 | 28.12 | 11.50 | 0.51 |
| 10| 1923 | 38.61 | 17.77 | 0.67 |
| 43| 6788 | 98.23 | 56.35 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 1000 | 33.36 | 11.42 | 0.55 |
| 5| 1174 | 36.38 | 13.58 | 0.59 |
| 10| 2043 | 44.97 | 19.39 | 0.74 |
| 34| 5762 | 94.49 | 49.34 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.87 | 10.16 | 0.53 |
| 2| 833 | 35.92 | 11.40 | 0.56 |
| 3| 1056 | 39.14 | 13.00 | 0.61 |
| 5| 1272 | 42.61 | 15.27 | 0.66 |
| 10| 1999 | 53.54 | 21.64 | 0.83 |
| 29| 4910 | 98.50 | 46.85 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5917 | 34.86 | 11.67 | 0.78 |
| 3| 6042 | 43.55 | 14.61 | 0.87 |
| 4| 6330 | 54.92 | 18.51 | 1.01 |
| 5| 6271 | 56.94 | 19.08 | 1.02 |
| 6| 6468 | 67.38 | 22.66 | 1.14 |
| 7| 6731 | 79.98 | 26.99 | 1.29 |
| 8| 6842 | 88.90 | 29.90 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2164 | 7126 | 96.19 | 36.84 | 1.51 |

