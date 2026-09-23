--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-23 10:26:47.288019661 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6035 | 13.08 | 4.16 | 0.55 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7651 | 28.94 | 9.11 | 0.79 |
| 43| 14283 | 99.06 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 42.57 | 12.25 | 0.62 |
| 4 | 226 | 858 | 53.71 | 15.28 | 0.73 |
| 5 | 284 | 969 | 62.35 | 17.73 | 0.82 |
| 6 | 338 | 1081 | 73.35 | 20.87 | 0.94 |
| 7 | 393 | 1192 | 82.08 | 23.24 | 1.03 |
| 8 | 450 | 1303 | 91.62 | 25.96 | 1.13 |
| 9 | 506 | 1418 | 93.49 | 26.85 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1925 | 25.47 | 8.70 | 0.50 |
| 3| 2124 | 28.09 | 10.09 | 0.54 |
| 5| 2454 | 32.33 | 12.60 | 0.61 |
| 10| 3166 | 41.54 | 18.52 | 0.76 |
| 39| 7323 | 94.53 | 52.56 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.84 | 7.37 | 0.41 |
| 2| 741 | 24.31 | 8.45 | 0.44 |
| 3| 902 | 25.13 | 9.32 | 0.46 |
| 5| 1180 | 29.22 | 11.81 | 0.52 |
| 10| 1951 | 38.66 | 17.78 | 0.68 |
| 43| 6804 | 98.58 | 56.48 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 27.54 | 8.47 | 0.46 |
| 2| 732 | 30.23 | 9.85 | 0.50 |
| 3| 868 | 32.04 | 11.02 | 0.53 |
| 5| 1327 | 38.40 | 14.20 | 0.62 |
| 10| 2007 | 45.42 | 19.52 | 0.75 |
| 34| 5967 | 98.17 | 50.39 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 864 | 36.56 | 11.60 | 0.57 |
| 3| 967 | 37.91 | 12.62 | 0.59 |
| 5| 1326 | 43.28 | 15.48 | 0.67 |
| 10| 2236 | 56.64 | 22.59 | 0.87 |
| 29| 4924 | 98.24 | 46.77 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 27.04 | 9.07 | 0.69 |
| 2| 6024 | 36.89 | 12.44 | 0.80 |
| 3| 5991 | 41.53 | 13.92 | 0.85 |
| 4| 6118 | 46.69 | 15.60 | 0.91 |
| 5| 6312 | 59.15 | 19.84 | 1.05 |
| 6| 6468 | 68.71 | 23.07 | 1.16 |
| 7| 6849 | 83.04 | 28.01 | 1.32 |
| 8| 6894 | 91.35 | 30.73 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.82 | 6.63 | 0.61 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |

