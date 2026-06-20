--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-20 09:07:01.852345599 UTC |
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
| 2| 6037 | 12.70 | 4.03 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7650 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 751 | 41.07 | 11.87 | 0.60 |
| 4 | 226 | 858 | 52.47 | 15.01 | 0.72 |
| 5 | 281 | 969 | 64.05 | 18.18 | 0.84 |
| 6 | 340 | 1081 | 74.24 | 21.12 | 0.95 |
| 7 | 395 | 1192 | 81.94 | 23.24 | 1.03 |
| 8 | 448 | 1303 | 94.07 | 26.60 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 23.92 | 7.60 | 0.48 |
| 2| 1978 | 26.92 | 9.09 | 0.52 |
| 3| 2125 | 28.09 | 10.09 | 0.54 |
| 5| 2437 | 32.32 | 12.60 | 0.61 |
| 10| 3173 | 41.12 | 18.38 | 0.75 |
| 43| 7871 | 98.29 | 56.28 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.50 | 7.29 | 0.41 |
| 2| 699 | 22.58 | 7.95 | 0.42 |
| 3| 984 | 28.05 | 10.16 | 0.49 |
| 5| 1203 | 29.07 | 11.77 | 0.52 |
| 10| 1981 | 38.44 | 17.72 | 0.68 |
| 42| 6736 | 98.18 | 55.67 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.51 | 8.47 | 0.46 |
| 2| 784 | 30.91 | 10.06 | 0.51 |
| 3| 911 | 32.80 | 11.25 | 0.54 |
| 5| 1235 | 34.52 | 13.10 | 0.58 |
| 10| 2110 | 49.47 | 20.66 | 0.79 |
| 35| 6010 | 97.03 | 50.74 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.83 | 10.16 | 0.53 |
| 2| 868 | 36.60 | 11.61 | 0.57 |
| 3| 1008 | 38.55 | 12.81 | 0.60 |
| 5| 1274 | 42.97 | 15.38 | 0.66 |
| 10| 2100 | 54.50 | 21.96 | 0.84 |
| 29| 4777 | 97.24 | 46.44 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5803 | 26.97 | 9.05 | 0.69 |
| 2| 5907 | 32.48 | 10.86 | 0.75 |
| 3| 5996 | 41.36 | 13.84 | 0.85 |
| 4| 6186 | 50.30 | 16.85 | 0.95 |
| 5| 6310 | 62.77 | 21.11 | 1.09 |
| 6| 6568 | 75.07 | 25.35 | 1.23 |
| 7| 6763 | 83.44 | 28.12 | 1.32 |
| 8| 6913 | 90.02 | 30.33 | 1.40 |
| 9| 6970 | 98.48 | 33.03 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2275 | 7192 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2214 | 7154 | 98.93 | 37.88 | 1.54 |

