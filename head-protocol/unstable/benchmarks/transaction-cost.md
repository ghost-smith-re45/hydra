--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-06 04:37:25.298085552 UTC |
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
| 2| 6035 | 12.72 | 4.03 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 41.36 | 11.94 | 0.60 |
| 4 | 224 | 858 | 48.04 | 13.92 | 0.68 |
| 5 | 283 | 974 | 56.16 | 16.26 | 0.76 |
| 6 | 338 | 1081 | 75.43 | 21.30 | 0.96 |
| 7 | 394 | 1192 | 76.72 | 22.04 | 0.98 |
| 8 | 450 | 1303 | 95.83 | 26.96 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 23.92 | 7.60 | 0.48 |
| 2| 1915 | 25.55 | 8.71 | 0.50 |
| 3| 2115 | 28.05 | 10.08 | 0.54 |
| 5| 2456 | 31.99 | 12.52 | 0.61 |
| 10| 3158 | 42.35 | 18.72 | 0.77 |
| 41| 7728 | 98.32 | 54.96 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 769 | 24.35 | 8.47 | 0.44 |
| 3| 831 | 24.06 | 9.04 | 0.45 |
| 5| 1159 | 28.00 | 11.46 | 0.51 |
| 10| 1969 | 39.09 | 17.90 | 0.68 |
| 41| 6425 | 95.70 | 54.30 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 27.50 | 8.46 | 0.46 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 970 | 33.51 | 11.47 | 0.55 |
| 5| 1295 | 35.76 | 13.47 | 0.59 |
| 10| 2167 | 46.48 | 19.86 | 0.76 |
| 35| 5870 | 97.27 | 50.76 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 33.15 | 9.95 | 0.52 |
| 2| 851 | 36.60 | 11.61 | 0.57 |
| 3| 938 | 37.84 | 12.60 | 0.59 |
| 5| 1210 | 41.78 | 15.02 | 0.65 |
| 10| 2215 | 56.14 | 22.44 | 0.86 |
| 29| 4989 | 98.60 | 46.88 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.05 | 9.08 | 0.69 |
| 2| 5822 | 31.48 | 10.47 | 0.74 |
| 3| 6016 | 43.53 | 14.59 | 0.87 |
| 4| 6270 | 55.51 | 18.76 | 1.01 |
| 5| 6263 | 59.32 | 19.88 | 1.05 |
| 6| 6704 | 76.56 | 25.86 | 1.25 |
| 7| 6686 | 78.81 | 26.47 | 1.27 |
| 8| 6953 | 92.07 | 31.06 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1703 | 6849 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2275 | 7191 | 99.84 | 38.30 | 1.55 |
| 10 | 39 | 2217 | 7156 | 98.49 | 37.73 | 1.53 |

