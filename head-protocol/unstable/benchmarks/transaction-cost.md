--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-05 06:29:34.804520292 UTC |
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
| 1| 5834 | 10.95 | 3.49 | 0.52 |
| 2| 6041 | 12.92 | 4.11 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 19.27 | 6.11 | 0.64 |
| 10| 7650 | 29.55 | 9.33 | 0.79 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 751 | 40.27 | 11.70 | 0.59 |
| 4 | 225 | 862 | 52.27 | 14.96 | 0.72 |
| 5 | 283 | 974 | 57.74 | 16.66 | 0.78 |
| 6 | 337 | 1081 | 68.43 | 19.66 | 0.89 |
| 7 | 393 | 1196 | 78.62 | 22.46 | 1.00 |
| 8 | 449 | 1303 | 98.96 | 27.87 | 1.21 |
| 9 | 505 | 1414 | 96.92 | 27.79 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.37 | 7.71 | 0.48 |
| 2| 2010 | 26.92 | 9.09 | 0.52 |
| 3| 2011 | 25.94 | 9.49 | 0.52 |
| 5| 2529 | 34.75 | 13.27 | 0.64 |
| 10| 3074 | 40.30 | 18.16 | 0.74 |
| 41| 7782 | 99.29 | 55.20 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.81 | 7.37 | 0.42 |
| 2| 844 | 25.10 | 8.69 | 0.45 |
| 3| 853 | 24.07 | 9.03 | 0.45 |
| 5| 1188 | 29.03 | 11.77 | 0.52 |
| 10| 1992 | 39.83 | 18.10 | 0.69 |
| 40| 6317 | 95.17 | 53.51 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 29.13 | 8.90 | 0.48 |
| 2| 828 | 31.54 | 10.26 | 0.52 |
| 3| 1064 | 32.40 | 11.20 | 0.54 |
| 5| 1249 | 37.32 | 13.87 | 0.61 |
| 10| 1925 | 43.33 | 18.90 | 0.72 |
| 37| 6205 | 99.89 | 52.85 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 1046 | 39.30 | 13.04 | 0.61 |
| 5| 1320 | 43.39 | 15.50 | 0.67 |
| 10| 2218 | 56.39 | 22.50 | 0.87 |
| 29| 4683 | 95.49 | 45.95 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.00 | 9.07 | 0.69 |
| 2| 5845 | 31.44 | 10.45 | 0.74 |
| 3| 6133 | 46.03 | 15.52 | 0.90 |
| 4| 6121 | 50.54 | 16.92 | 0.95 |
| 5| 6441 | 62.54 | 21.08 | 1.09 |
| 6| 6481 | 72.50 | 24.35 | 1.20 |
| 7| 6860 | 85.65 | 28.94 | 1.35 |
| 8| 6968 | 94.38 | 31.85 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.05 | 6.02 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1136 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

