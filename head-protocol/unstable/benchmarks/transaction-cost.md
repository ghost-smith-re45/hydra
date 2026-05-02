--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-02 07:19:30.452934251 UTC |
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
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 99.40 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 169 | 747 | 42.56 | 12.27 | 0.62 |
| 4 | 226 | 858 | 49.42 | 14.25 | 0.69 |
| 5 | 285 | 969 | 57.63 | 16.67 | 0.78 |
| 6 | 338 | 1081 | 64.43 | 18.66 | 0.85 |
| 7 | 392 | 1192 | 85.02 | 24.03 | 1.06 |
| 8 | 450 | 1303 | 80.80 | 23.47 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.29 | 7.69 | 0.48 |
| 2| 1985 | 26.76 | 9.04 | 0.52 |
| 3| 2065 | 27.35 | 9.87 | 0.53 |
| 5| 2435 | 32.37 | 12.61 | 0.61 |
| 10| 3191 | 42.08 | 18.67 | 0.77 |
| 39| 7636 | 98.20 | 53.59 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.80 | 7.39 | 0.42 |
| 2| 830 | 25.53 | 8.80 | 0.46 |
| 3| 895 | 25.10 | 9.32 | 0.46 |
| 5| 1216 | 30.13 | 12.06 | 0.53 |
| 10| 1912 | 38.68 | 17.80 | 0.68 |
| 41| 6461 | 96.00 | 54.38 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.51 | 8.47 | 0.46 |
| 2| 820 | 31.66 | 10.29 | 0.52 |
| 3| 869 | 32.09 | 11.03 | 0.53 |
| 5| 1246 | 34.51 | 13.10 | 0.58 |
| 10| 2030 | 44.63 | 19.30 | 0.74 |
| 37| 5938 | 98.48 | 52.35 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 815 | 35.81 | 11.37 | 0.56 |
| 3| 965 | 37.95 | 12.63 | 0.59 |
| 5| 1314 | 43.13 | 15.44 | 0.67 |
| 10| 1960 | 52.74 | 21.42 | 0.82 |
| 29| 4773 | 96.54 | 46.27 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5838 | 27.08 | 9.09 | 0.69 |
| 2| 6014 | 36.81 | 12.41 | 0.80 |
| 3| 6039 | 43.98 | 14.74 | 0.88 |
| 4| 6470 | 56.73 | 19.20 | 1.03 |
| 5| 6411 | 61.68 | 20.78 | 1.08 |
| 6| 6528 | 69.53 | 23.36 | 1.17 |
| 7| 6704 | 80.80 | 27.22 | 1.29 |
| 8| 6660 | 80.82 | 27.13 | 1.29 |
| 9| 6894 | 96.59 | 32.55 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 78.71 | 30.00 | 1.30 |
| 10 | 39 | 2220 | 7160 | 98.24 | 37.65 | 1.53 |

