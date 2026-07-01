--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-01 09:29:39.509615244 UTC |
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
| 1| 5836 | 10.95 | 3.49 | 0.52 |
| 2| 6039 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.60 | 5.87 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14286 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 169 | 747 | 39.86 | 11.58 | 0.59 |
| 4 | 228 | 858 | 47.87 | 13.89 | 0.67 |
| 5 | 284 | 969 | 59.68 | 17.13 | 0.80 |
| 6 | 339 | 1081 | 69.62 | 19.94 | 0.90 |
| 7 | 396 | 1192 | 73.73 | 21.23 | 0.95 |
| 8 | 450 | 1303 | 85.74 | 24.70 | 1.08 |
| 9 | 505 | 1414 | 95.42 | 27.25 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.29 | 7.69 | 0.48 |
| 2| 1988 | 26.58 | 9.01 | 0.52 |
| 3| 2018 | 26.02 | 9.51 | 0.52 |
| 5| 2430 | 32.12 | 12.55 | 0.61 |
| 10| 3219 | 41.54 | 18.52 | 0.76 |
| 39| 7561 | 99.38 | 53.90 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.57 | 7.31 | 0.41 |
| 2| 838 | 25.49 | 8.79 | 0.46 |
| 3| 888 | 25.16 | 9.33 | 0.46 |
| 5| 1316 | 31.15 | 12.36 | 0.55 |
| 10| 2064 | 41.20 | 18.49 | 0.71 |
| 41| 6445 | 97.80 | 54.90 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.54 | 8.47 | 0.46 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 903 | 30.15 | 10.52 | 0.51 |
| 5| 1249 | 37.10 | 13.79 | 0.60 |
| 10| 2202 | 47.04 | 20.02 | 0.77 |
| 37| 6122 | 98.67 | 52.43 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.85 | 11.38 | 0.56 |
| 3| 955 | 37.84 | 12.60 | 0.59 |
| 5| 1282 | 42.56 | 15.26 | 0.66 |
| 10| 2148 | 55.51 | 22.25 | 0.85 |
| 29| 4966 | 99.17 | 47.06 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 27.13 | 9.09 | 0.69 |
| 2| 6013 | 36.88 | 12.45 | 0.80 |
| 3| 6176 | 47.03 | 15.86 | 0.92 |
| 4| 6284 | 52.31 | 17.62 | 0.98 |
| 5| 6453 | 61.14 | 20.62 | 1.08 |
| 6| 6555 | 72.76 | 24.54 | 1.20 |
| 7| 6645 | 78.54 | 26.33 | 1.27 |
| 8| 6861 | 90.18 | 30.34 | 1.40 |
| 9| 7023 | 97.36 | 32.85 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 56 | 5868 | 20.08 | 6.82 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 99.12 | 37.95 | 1.54 |

