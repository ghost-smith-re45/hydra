--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-28 09:08:24.554709671 UTC |
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
| 1| 5841 | 10.40 | 3.30 | 0.52 |
| 2| 6041 | 12.41 | 3.92 | 0.54 |
| 3| 6236 | 14.67 | 4.64 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14285 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 42.38 | 12.20 | 0.61 |
| 4 | 227 | 858 | 48.09 | 13.93 | 0.68 |
| 5 | 283 | 969 | 57.84 | 16.69 | 0.78 |
| 6 | 338 | 1081 | 68.03 | 19.52 | 0.89 |
| 7 | 392 | 1192 | 74.73 | 21.57 | 0.96 |
| 8 | 448 | 1307 | 82.13 | 23.68 | 1.04 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1937 | 25.39 | 8.68 | 0.50 |
| 3| 2012 | 26.31 | 9.58 | 0.52 |
| 5| 2400 | 31.00 | 12.24 | 0.59 |
| 10| 3077 | 40.11 | 18.10 | 0.74 |
| 40| 7675 | 98.75 | 54.41 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.84 | 7.38 | 0.42 |
| 2| 822 | 25.39 | 8.76 | 0.45 |
| 3| 915 | 25.76 | 9.53 | 0.47 |
| 5| 1188 | 29.14 | 11.79 | 0.52 |
| 10| 2093 | 43.86 | 19.24 | 0.74 |
| 43| 6818 | 99.48 | 56.68 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.50 | 8.46 | 0.46 |
| 2| 741 | 30.23 | 9.85 | 0.50 |
| 3| 950 | 30.90 | 10.74 | 0.52 |
| 5| 1248 | 35.05 | 13.25 | 0.58 |
| 10| 2134 | 45.80 | 19.65 | 0.76 |
| 37| 5939 | 97.30 | 52.03 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 816 | 35.88 | 11.39 | 0.56 |
| 3| 953 | 37.88 | 12.61 | 0.59 |
| 5| 1257 | 42.72 | 15.30 | 0.66 |
| 10| 1995 | 53.97 | 21.79 | 0.83 |
| 30| 4794 | 97.30 | 47.12 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.13 | 9.09 | 0.69 |
| 2| 5958 | 37.13 | 12.49 | 0.80 |
| 3| 6162 | 45.65 | 15.40 | 0.90 |
| 4| 6289 | 54.62 | 18.40 | 1.00 |
| 5| 6389 | 63.65 | 21.48 | 1.10 |
| 6| 6320 | 63.43 | 21.21 | 1.09 |
| 7| 6731 | 79.31 | 26.74 | 1.28 |
| 8| 6919 | 89.91 | 30.25 | 1.40 |
| 9| 6740 | 92.10 | 30.81 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7159 | 99.56 | 38.10 | 1.54 |

