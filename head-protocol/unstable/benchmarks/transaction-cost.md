--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-28 06:11:03.300552506 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 15.22 | 4.84 | 0.58 |
| 5| 6641 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 751 | 39.97 | 11.62 | 0.59 |
| 4 | 225 | 858 | 51.43 | 14.81 | 0.71 |
| 5 | 282 | 969 | 57.50 | 16.61 | 0.78 |
| 6 | 340 | 1085 | 65.89 | 19.01 | 0.87 |
| 7 | 393 | 1192 | 77.69 | 22.41 | 0.99 |
| 8 | 450 | 1303 | 89.44 | 25.53 | 1.11 |
| 9 | 504 | 1414 | 93.50 | 26.80 | 1.16 |
| 10 | 560 | 1525 | 97.53 | 28.23 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.37 | 7.71 | 0.48 |
| 2| 1924 | 25.84 | 8.78 | 0.51 |
| 3| 2161 | 29.01 | 10.35 | 0.55 |
| 5| 2452 | 33.03 | 12.79 | 0.62 |
| 10| 3120 | 40.81 | 18.30 | 0.75 |
| 38| 7473 | 97.58 | 52.76 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.39 | 0.41 |
| 2| 699 | 22.55 | 7.94 | 0.42 |
| 3| 930 | 26.01 | 9.58 | 0.47 |
| 5| 1198 | 29.18 | 11.80 | 0.52 |
| 10| 2004 | 38.65 | 17.77 | 0.68 |
| 40| 6544 | 98.64 | 54.43 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 812 | 29.15 | 9.59 | 0.49 |
| 3| 910 | 32.76 | 11.24 | 0.54 |
| 5| 1292 | 34.94 | 13.22 | 0.58 |
| 10| 1991 | 47.29 | 20.00 | 0.76 |
| 38| 6139 | 99.53 | 53.34 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.83 | 10.15 | 0.53 |
| 2| 812 | 35.88 | 11.39 | 0.56 |
| 3| 1001 | 38.55 | 12.81 | 0.60 |
| 5| 1361 | 43.65 | 15.59 | 0.68 |
| 10| 2106 | 54.63 | 21.99 | 0.84 |
| 29| 4820 | 96.77 | 46.34 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.13 | 9.09 | 0.69 |
| 2| 5941 | 36.04 | 12.10 | 0.79 |
| 3| 6138 | 45.97 | 15.51 | 0.90 |
| 4| 6224 | 54.21 | 18.22 | 0.99 |
| 5| 6327 | 60.07 | 20.21 | 1.06 |
| 6| 6316 | 63.73 | 21.26 | 1.10 |
| 7| 6657 | 80.69 | 27.23 | 1.29 |
| 8| 6826 | 90.32 | 30.48 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1705 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2278 | 7194 | 98.77 | 37.94 | 1.54 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

