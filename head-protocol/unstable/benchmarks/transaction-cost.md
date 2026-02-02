--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-02 05:40:15.47598353 UTC |
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
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.40 | 4.55 | 0.57 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 29.28 | 9.24 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 169 | 747 | 41.08 | 11.87 | 0.60 |
| 4 | 227 | 858 | 49.82 | 14.43 | 0.69 |
| 5 | 283 | 969 | 64.66 | 18.38 | 0.85 |
| 6 | 338 | 1081 | 75.99 | 21.51 | 0.97 |
| 7 | 395 | 1192 | 84.88 | 24.00 | 1.06 |
| 8 | 450 | 1303 | 83.36 | 24.08 | 1.05 |
| 9 | 506 | 1414 | 99.17 | 28.22 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1924 | 25.84 | 8.78 | 0.51 |
| 3| 2155 | 27.93 | 10.05 | 0.54 |
| 5| 2364 | 31.44 | 12.35 | 0.60 |
| 10| 3248 | 41.51 | 18.51 | 0.76 |
| 41| 7559 | 98.11 | 54.87 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 621 | 22.80 | 7.37 | 0.41 |
| 2| 762 | 24.32 | 8.46 | 0.44 |
| 3| 952 | 27.04 | 9.88 | 0.48 |
| 5| 1092 | 26.96 | 11.18 | 0.50 |
| 10| 2046 | 39.57 | 18.04 | 0.69 |
| 42| 6669 | 97.91 | 55.56 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 29.13 | 8.90 | 0.48 |
| 2| 886 | 29.82 | 9.80 | 0.50 |
| 3| 970 | 30.82 | 10.73 | 0.52 |
| 5| 1310 | 37.77 | 14.00 | 0.61 |
| 10| 1977 | 44.19 | 19.15 | 0.73 |
| 36| 6037 | 97.85 | 51.62 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.79 | 10.15 | 0.53 |
| 2| 837 | 35.88 | 11.39 | 0.56 |
| 3| 964 | 37.87 | 12.61 | 0.59 |
| 5| 1268 | 42.45 | 15.23 | 0.66 |
| 10| 2052 | 54.84 | 22.04 | 0.84 |
| 28| 4686 | 95.61 | 45.35 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5838 | 26.92 | 9.05 | 0.69 |
| 2| 5962 | 35.88 | 12.05 | 0.79 |
| 3| 5989 | 41.32 | 13.82 | 0.85 |
| 4| 6299 | 55.60 | 18.84 | 1.01 |
| 5| 6440 | 66.79 | 22.56 | 1.14 |
| 6| 6629 | 74.94 | 25.27 | 1.23 |
| 7| 6674 | 80.14 | 26.94 | 1.29 |
| 8| 6917 | 94.38 | 31.84 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 20 | 1136 | 6510 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2219 | 7158 | 99.82 | 38.19 | 1.55 |

