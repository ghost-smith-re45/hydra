--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-19 05:37:59.299595444 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6041 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6638 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 43.88 | 12.56 | 0.63 |
| 4 | 226 | 858 | 53.89 | 15.35 | 0.73 |
| 5 | 281 | 969 | 59.28 | 17.10 | 0.80 |
| 6 | 339 | 1081 | 69.23 | 19.81 | 0.90 |
| 7 | 394 | 1192 | 82.81 | 23.46 | 1.04 |
| 8 | 448 | 1303 | 98.18 | 27.48 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.40 | 8.39 | 0.49 |
| 3| 2058 | 26.99 | 9.78 | 0.53 |
| 5| 2317 | 30.01 | 11.96 | 0.58 |
| 10| 3136 | 40.65 | 18.26 | 0.75 |
| 40| 7555 | 98.75 | 54.40 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.54 | 7.30 | 0.41 |
| 2| 760 | 24.35 | 8.47 | 0.44 |
| 3| 985 | 28.23 | 10.23 | 0.50 |
| 5| 1250 | 31.10 | 12.34 | 0.55 |
| 10| 2156 | 42.76 | 18.96 | 0.73 |
| 39| 6548 | 99.97 | 54.15 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 875 | 31.61 | 10.27 | 0.52 |
| 3| 970 | 33.51 | 11.46 | 0.55 |
| 5| 1230 | 36.95 | 13.76 | 0.60 |
| 10| 1972 | 44.04 | 19.11 | 0.73 |
| 37| 6022 | 99.56 | 52.69 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.83 | 10.15 | 0.53 |
| 2| 810 | 35.85 | 11.38 | 0.56 |
| 3| 1016 | 38.55 | 12.81 | 0.60 |
| 5| 1378 | 44.15 | 15.73 | 0.68 |
| 10| 2183 | 55.63 | 22.28 | 0.86 |
| 30| 4939 | 99.80 | 47.84 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 26.97 | 9.05 | 0.69 |
| 2| 5960 | 35.80 | 12.03 | 0.79 |
| 3| 6089 | 44.96 | 15.12 | 0.89 |
| 4| 6251 | 55.01 | 18.54 | 1.00 |
| 5| 6124 | 51.81 | 17.23 | 0.96 |
| 6| 6412 | 68.35 | 22.93 | 1.15 |
| 7| 6803 | 80.79 | 27.20 | 1.30 |
| 8| 6862 | 90.01 | 30.23 | 1.40 |
| 9| 6922 | 97.45 | 32.75 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1136 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1705 | 6851 | 80.67 | 30.67 | 1.32 |
| 10 | 37 | 2107 | 7093 | 94.83 | 36.27 | 1.49 |

