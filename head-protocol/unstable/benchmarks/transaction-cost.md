--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-24 07:07:59.943018837 UTC |
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
| 1| 5836 | 10.69 | 3.40 | 0.52 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 14.97 | 4.75 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 640 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 43.88 | 12.56 | 0.63 |
| 4 | 227 | 862 | 52.73 | 15.10 | 0.72 |
| 5 | 283 | 969 | 62.69 | 17.88 | 0.83 |
| 6 | 339 | 1081 | 68.11 | 19.58 | 0.89 |
| 7 | 394 | 1192 | 82.55 | 23.39 | 1.04 |
| 8 | 451 | 1303 | 81.41 | 23.66 | 1.04 |
| 10 | 560 | 1529 | 98.81 | 28.73 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.93 | 7.32 | 0.47 |
| 2| 1942 | 25.80 | 8.77 | 0.51 |
| 3| 2106 | 28.42 | 10.17 | 0.55 |
| 5| 2429 | 32.48 | 12.64 | 0.61 |
| 10| 3205 | 41.31 | 18.44 | 0.76 |
| 40| 7741 | 99.71 | 54.70 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 22.81 | 7.38 | 0.42 |
| 2| 773 | 24.04 | 8.40 | 0.44 |
| 3| 874 | 25.47 | 9.46 | 0.46 |
| 5| 1234 | 29.70 | 11.97 | 0.53 |
| 10| 1840 | 35.67 | 16.93 | 0.64 |
| 42| 6826 | 99.05 | 55.91 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 27.50 | 8.46 | 0.46 |
| 2| 828 | 29.26 | 9.62 | 0.49 |
| 3| 1045 | 32.24 | 11.16 | 0.54 |
| 5| 1319 | 38.49 | 14.22 | 0.62 |
| 10| 1997 | 44.15 | 19.14 | 0.73 |
| 34| 5791 | 96.37 | 49.86 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 835 | 35.85 | 11.38 | 0.56 |
| 3| 951 | 37.95 | 12.63 | 0.59 |
| 5| 1241 | 42.53 | 15.25 | 0.66 |
| 10| 2130 | 54.58 | 21.97 | 0.84 |
| 30| 4936 | 99.85 | 47.85 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.13 | 9.10 | 0.69 |
| 2| 5978 | 37.09 | 12.47 | 0.80 |
| 3| 6097 | 44.95 | 15.10 | 0.89 |
| 4| 6207 | 54.18 | 18.19 | 0.99 |
| 5| 6431 | 61.53 | 20.72 | 1.08 |
| 6| 6593 | 74.63 | 25.16 | 1.22 |
| 7| 6607 | 78.12 | 26.29 | 1.26 |
| 8| 6916 | 94.38 | 31.87 | 1.45 |
| 9| 7006 | 98.74 | 33.28 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1710 | 6857 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2217 | 7156 | 97.79 | 37.50 | 1.53 |

