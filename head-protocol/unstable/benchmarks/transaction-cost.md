--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-21 06:24:33.923515423 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 227 | 858 | 51.15 | 14.72 | 0.71 |
| 5 | 283 | 969 | 57.86 | 16.72 | 0.78 |
| 6 | 338 | 1081 | 68.28 | 19.66 | 0.89 |
| 7 | 394 | 1192 | 80.69 | 22.95 | 1.02 |
| 8 | 449 | 1303 | 82.93 | 23.98 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1943 | 25.80 | 8.77 | 0.51 |
| 3| 2071 | 26.95 | 9.77 | 0.53 |
| 5| 2276 | 28.89 | 11.65 | 0.57 |
| 10| 3185 | 41.26 | 18.42 | 0.76 |
| 38| 7311 | 93.10 | 51.55 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 22.54 | 7.30 | 0.41 |
| 2| 699 | 22.55 | 7.94 | 0.42 |
| 3| 830 | 24.13 | 9.06 | 0.45 |
| 5| 1214 | 29.18 | 11.81 | 0.52 |
| 10| 1983 | 39.70 | 18.08 | 0.69 |
| 41| 6583 | 97.14 | 54.74 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.50 | 8.46 | 0.46 |
| 2| 736 | 30.20 | 9.84 | 0.50 |
| 3| 924 | 32.79 | 11.25 | 0.54 |
| 5| 1332 | 38.33 | 14.18 | 0.62 |
| 10| 1996 | 47.20 | 19.98 | 0.76 |
| 36| 5900 | 97.34 | 51.40 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 707 | 33.83 | 10.15 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 993 | 38.62 | 12.83 | 0.60 |
| 5| 1294 | 43.24 | 15.46 | 0.67 |
| 10| 2019 | 54.12 | 21.82 | 0.83 |
| 29| 4918 | 97.85 | 46.67 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5839 | 27.08 | 9.09 | 0.69 |
| 2| 5950 | 35.76 | 12.01 | 0.79 |
| 3| 6173 | 47.20 | 15.93 | 0.92 |
| 4| 6193 | 50.30 | 16.88 | 0.95 |
| 5| 6515 | 65.08 | 22.01 | 1.12 |
| 6| 6603 | 74.76 | 25.21 | 1.23 |
| 7| 6747 | 83.92 | 28.34 | 1.33 |
| 8| 6976 | 92.73 | 31.41 | 1.43 |
| 9| 6830 | 93.39 | 31.43 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 569 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1705 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2222 | 7162 | 98.93 | 37.88 | 1.54 |

