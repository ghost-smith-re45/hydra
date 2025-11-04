--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-04 04:37:59.984987252 UTC |
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
| 1| 5834 | 10.85 | 3.45 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6643 | 19.36 | 6.14 | 0.64 |
| 10| 7647 | 29.02 | 9.14 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 226 | 858 | 48.06 | 13.98 | 0.68 |
| 5 | 284 | 969 | 62.41 | 17.81 | 0.83 |
| 6 | 339 | 1081 | 66.34 | 19.12 | 0.87 |
| 7 | 394 | 1192 | 73.01 | 21.24 | 0.95 |
| 8 | 450 | 1303 | 93.88 | 26.55 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.00 | 7.62 | 0.48 |
| 2| 1941 | 25.76 | 8.76 | 0.51 |
| 3| 2089 | 26.94 | 9.77 | 0.53 |
| 5| 2359 | 31.57 | 12.38 | 0.60 |
| 10| 3124 | 40.62 | 18.26 | 0.75 |
| 40| 7594 | 98.17 | 54.25 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 693 | 22.55 | 7.93 | 0.42 |
| 3| 947 | 26.02 | 9.58 | 0.47 |
| 5| 1285 | 32.50 | 12.74 | 0.56 |
| 10| 1963 | 38.75 | 17.80 | 0.68 |
| 42| 6721 | 98.11 | 55.68 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 27.50 | 8.46 | 0.46 |
| 2| 779 | 30.87 | 10.05 | 0.51 |
| 3| 996 | 31.58 | 10.95 | 0.53 |
| 5| 1176 | 36.20 | 13.53 | 0.59 |
| 10| 1991 | 44.83 | 19.35 | 0.74 |
| 37| 6059 | 98.55 | 52.44 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 33.83 | 10.15 | 0.53 |
| 2| 799 | 35.85 | 11.38 | 0.56 |
| 3| 962 | 37.84 | 12.60 | 0.59 |
| 5| 1271 | 42.61 | 15.27 | 0.66 |
| 10| 2198 | 55.29 | 22.19 | 0.85 |
| 29| 4886 | 98.21 | 46.74 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 27.09 | 9.10 | 0.69 |
| 2| 5866 | 32.49 | 10.85 | 0.75 |
| 3| 6178 | 46.45 | 15.73 | 0.91 |
| 4| 6162 | 50.38 | 16.91 | 0.95 |
| 5| 6331 | 62.91 | 21.16 | 1.09 |
| 6| 6607 | 74.19 | 25.02 | 1.22 |
| 7| 6953 | 87.07 | 29.52 | 1.37 |
| 8| 6846 | 89.29 | 30.01 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2165 | 7127 | 96.00 | 36.77 | 1.50 |

