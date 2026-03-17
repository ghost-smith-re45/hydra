--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-17 06:39:13.37570193 UTC |
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
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 42.65 | 12.27 | 0.62 |
| 4 | 226 | 858 | 52.82 | 15.14 | 0.72 |
| 5 | 282 | 969 | 64.30 | 18.27 | 0.84 |
| 6 | 337 | 1081 | 69.94 | 20.05 | 0.91 |
| 7 | 394 | 1192 | 86.54 | 24.39 | 1.08 |
| 8 | 449 | 1303 | 89.33 | 25.41 | 1.11 |
| 9 | 505 | 1418 | 99.21 | 28.34 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.29 | 7.69 | 0.48 |
| 2| 1966 | 26.87 | 9.07 | 0.52 |
| 3| 2119 | 28.27 | 10.13 | 0.55 |
| 5| 2317 | 30.41 | 12.06 | 0.58 |
| 10| 3128 | 41.00 | 18.35 | 0.75 |
| 40| 7504 | 94.98 | 53.41 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.53 | 7.31 | 0.41 |
| 2| 796 | 23.51 | 8.21 | 0.43 |
| 3| 906 | 25.56 | 9.48 | 0.47 |
| 5| 1197 | 29.03 | 11.76 | 0.52 |
| 10| 1889 | 36.70 | 17.23 | 0.65 |
| 40| 6450 | 95.73 | 53.64 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 27.51 | 8.47 | 0.46 |
| 2| 818 | 29.15 | 9.59 | 0.49 |
| 3| 903 | 30.26 | 10.55 | 0.51 |
| 5| 1219 | 36.95 | 13.76 | 0.60 |
| 10| 2078 | 48.82 | 20.46 | 0.78 |
| 34| 5343 | 94.93 | 49.27 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.83 | 10.16 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1258 | 42.68 | 15.29 | 0.66 |
| 10| 2036 | 54.25 | 21.86 | 0.84 |
| 28| 4986 | 98.86 | 46.37 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.12 | 9.10 | 0.69 |
| 2| 5868 | 34.91 | 11.67 | 0.77 |
| 3| 6082 | 42.41 | 14.24 | 0.86 |
| 4| 6183 | 54.35 | 18.26 | 0.99 |
| 5| 6355 | 63.35 | 21.29 | 1.10 |
| 6| 6410 | 64.97 | 21.78 | 1.11 |
| 7| 6667 | 77.48 | 26.07 | 1.26 |
| 8| 6946 | 94.41 | 31.87 | 1.45 |
| 9| 6826 | 96.74 | 32.52 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

