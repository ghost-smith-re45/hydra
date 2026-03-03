--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-03 07:24:29.912743482 UTC |
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
| 1| 5838 | 10.40 | 3.30 | 0.51 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 42.57 | 12.27 | 0.62 |
| 4 | 227 | 858 | 48.12 | 13.94 | 0.68 |
| 5 | 283 | 969 | 60.33 | 17.25 | 0.80 |
| 6 | 338 | 1081 | 64.29 | 18.63 | 0.85 |
| 7 | 394 | 1196 | 83.83 | 23.73 | 1.05 |
| 8 | 450 | 1303 | 93.79 | 26.52 | 1.16 |
| 9 | 508 | 1418 | 99.19 | 28.39 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.40 | 8.39 | 0.49 |
| 3| 2082 | 26.99 | 9.78 | 0.53 |
| 5| 2322 | 30.08 | 11.98 | 0.58 |
| 10| 3206 | 41.93 | 18.62 | 0.76 |
| 39| 7532 | 97.37 | 53.35 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.84 | 7.39 | 0.42 |
| 2| 820 | 25.07 | 8.68 | 0.45 |
| 3| 895 | 25.10 | 9.32 | 0.46 |
| 5| 1249 | 31.27 | 12.39 | 0.55 |
| 10| 1979 | 37.47 | 17.45 | 0.67 |
| 43| 6707 | 95.65 | 55.65 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.13 | 8.90 | 0.48 |
| 2| 842 | 29.19 | 9.60 | 0.49 |
| 3| 912 | 32.69 | 11.22 | 0.54 |
| 5| 1288 | 37.67 | 13.98 | 0.61 |
| 10| 2223 | 50.32 | 20.92 | 0.81 |
| 35| 5906 | 96.51 | 50.56 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 989 | 38.55 | 12.81 | 0.60 |
| 5| 1216 | 41.93 | 15.06 | 0.65 |
| 10| 2045 | 54.84 | 22.06 | 0.84 |
| 29| 4865 | 97.65 | 46.60 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5822 | 31.45 | 10.46 | 0.74 |
| 3| 6195 | 45.68 | 15.44 | 0.90 |
| 4| 6072 | 49.39 | 16.50 | 0.94 |
| 5| 6544 | 67.10 | 22.71 | 1.14 |
| 6| 6714 | 74.22 | 25.18 | 1.23 |
| 7| 6688 | 83.92 | 28.22 | 1.33 |
| 8| 6901 | 92.79 | 31.24 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2218 | 7158 | 98.05 | 37.58 | 1.53 |

