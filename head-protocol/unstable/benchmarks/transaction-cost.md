--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-10 08:54:09.366766904 UTC |
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
| 1| 5836 | 10.76 | 3.42 | 0.52 |
| 2| 6035 | 12.42 | 3.93 | 0.54 |
| 3| 6238 | 15.05 | 4.78 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7650 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 751 | 42.23 | 12.15 | 0.61 |
| 4 | 227 | 858 | 49.65 | 14.36 | 0.69 |
| 5 | 283 | 969 | 62.81 | 17.91 | 0.83 |
| 6 | 339 | 1081 | 64.75 | 18.81 | 0.86 |
| 7 | 394 | 1192 | 72.66 | 21.11 | 0.94 |
| 8 | 448 | 1303 | 96.91 | 27.33 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.51 | 8.70 | 0.50 |
| 3| 2055 | 27.06 | 9.80 | 0.53 |
| 5| 2340 | 30.26 | 12.02 | 0.58 |
| 10| 3141 | 41.16 | 18.39 | 0.75 |
| 40| 7577 | 97.06 | 53.96 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.54 | 7.30 | 0.41 |
| 2| 695 | 22.58 | 7.96 | 0.42 |
| 3| 975 | 26.06 | 9.59 | 0.47 |
| 5| 1170 | 28.08 | 11.49 | 0.51 |
| 10| 1979 | 39.77 | 18.10 | 0.69 |
| 43| 6846 | 98.65 | 56.53 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.50 | 8.46 | 0.46 |
| 2| 781 | 30.87 | 10.05 | 0.51 |
| 3| 869 | 32.01 | 11.01 | 0.53 |
| 5| 1261 | 35.08 | 13.26 | 0.58 |
| 10| 2057 | 47.85 | 20.18 | 0.77 |
| 36| 5984 | 98.73 | 51.82 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 1002 | 38.59 | 12.82 | 0.60 |
| 5| 1361 | 43.95 | 15.68 | 0.68 |
| 10| 1954 | 53.31 | 21.58 | 0.82 |
| 30| 4982 | 99.45 | 47.79 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.00 | 9.06 | 0.69 |
| 2| 5890 | 32.60 | 10.89 | 0.75 |
| 3| 6178 | 47.11 | 15.90 | 0.92 |
| 4| 6281 | 54.78 | 18.51 | 1.00 |
| 5| 6436 | 65.00 | 21.97 | 1.12 |
| 6| 6507 | 70.15 | 23.57 | 1.17 |
| 7| 6751 | 83.52 | 28.17 | 1.33 |
| 8| 6951 | 94.09 | 31.79 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6002 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.05 | 37.58 | 1.53 |

