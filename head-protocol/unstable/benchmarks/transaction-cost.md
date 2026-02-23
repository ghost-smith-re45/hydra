--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-23 06:44:37.17550428 UTC |
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
| 1| 5836 | 10.36 | 3.28 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6242 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.93 | 5.98 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 42.57 | 12.25 | 0.62 |
| 4 | 225 | 858 | 49.69 | 14.37 | 0.69 |
| 5 | 283 | 969 | 62.85 | 17.95 | 0.83 |
| 6 | 339 | 1081 | 75.71 | 21.44 | 0.96 |
| 7 | 396 | 1196 | 86.17 | 24.21 | 1.07 |
| 8 | 450 | 1307 | 80.80 | 23.47 | 1.03 |
| 9 | 505 | 1414 | 88.60 | 25.57 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.29 | 7.69 | 0.48 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2102 | 28.31 | 10.14 | 0.54 |
| 5| 2316 | 30.22 | 12.01 | 0.58 |
| 10| 3028 | 38.33 | 17.62 | 0.72 |
| 39| 7521 | 97.39 | 53.36 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.31 | 0.41 |
| 2| 808 | 25.53 | 8.79 | 0.46 |
| 3| 1026 | 27.81 | 10.11 | 0.49 |
| 5| 1168 | 28.12 | 11.50 | 0.51 |
| 10| 1822 | 35.58 | 16.92 | 0.64 |
| 40| 6357 | 94.91 | 53.43 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 27.54 | 8.47 | 0.46 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 986 | 33.40 | 11.44 | 0.55 |
| 5| 1131 | 35.68 | 13.36 | 0.58 |
| 10| 2074 | 44.89 | 19.38 | 0.74 |
| 37| 5990 | 97.77 | 52.19 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 809 | 35.89 | 11.39 | 0.56 |
| 3| 986 | 38.59 | 12.82 | 0.60 |
| 5| 1199 | 41.82 | 15.03 | 0.65 |
| 10| 1934 | 53.08 | 21.52 | 0.82 |
| 28| 4756 | 96.38 | 45.59 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.05 | 9.07 | 0.69 |
| 2| 5913 | 35.84 | 12.03 | 0.79 |
| 3| 6141 | 45.95 | 15.48 | 0.90 |
| 4| 6272 | 54.93 | 18.54 | 1.00 |
| 5| 6385 | 61.07 | 20.53 | 1.07 |
| 6| 6503 | 67.40 | 22.67 | 1.14 |
| 7| 6749 | 79.25 | 26.65 | 1.28 |
| 8| 6885 | 93.79 | 31.73 | 1.44 |
| 9| 7017 | 99.96 | 33.56 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6855 | 80.67 | 30.67 | 1.32 |
| 10 | 37 | 2105 | 7090 | 93.95 | 35.96 | 1.48 |

