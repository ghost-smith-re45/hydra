--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-02 07:00:27.329869329 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 751 | 41.24 | 11.91 | 0.60 |
| 4 | 226 | 858 | 51.01 | 14.66 | 0.71 |
| 5 | 283 | 969 | 56.47 | 16.40 | 0.77 |
| 6 | 339 | 1081 | 68.86 | 19.71 | 0.90 |
| 7 | 395 | 1192 | 74.54 | 21.52 | 0.96 |
| 8 | 450 | 1303 | 81.02 | 23.47 | 1.03 |
| 9 | 504 | 1414 | 90.91 | 26.18 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.40 | 8.40 | 0.49 |
| 3| 2053 | 27.02 | 9.79 | 0.53 |
| 5| 2330 | 30.30 | 12.03 | 0.58 |
| 10| 3103 | 39.36 | 17.91 | 0.73 |
| 39| 7596 | 97.30 | 53.36 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.80 | 7.38 | 0.41 |
| 2| 746 | 24.35 | 8.47 | 0.44 |
| 3| 849 | 24.07 | 9.03 | 0.45 |
| 5| 1144 | 28.11 | 11.49 | 0.51 |
| 10| 1948 | 38.23 | 17.68 | 0.67 |
| 42| 6736 | 99.29 | 55.98 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 29.09 | 8.89 | 0.48 |
| 2| 836 | 29.22 | 9.61 | 0.49 |
| 3| 967 | 30.94 | 10.75 | 0.52 |
| 5| 1190 | 36.27 | 13.55 | 0.59 |
| 10| 2134 | 46.02 | 19.70 | 0.76 |
| 36| 6162 | 99.16 | 52.01 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 33.83 | 10.16 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 1021 | 38.92 | 12.92 | 0.60 |
| 5| 1205 | 41.97 | 15.07 | 0.65 |
| 10| 2008 | 54.28 | 21.88 | 0.83 |
| 30| 4987 | 99.79 | 47.86 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.58 | 0.64 |
| 2| 5912 | 35.84 | 12.04 | 0.79 |
| 3| 6018 | 43.57 | 14.61 | 0.87 |
| 4| 6211 | 53.82 | 18.09 | 0.99 |
| 5| 6405 | 64.62 | 21.72 | 1.11 |
| 6| 6592 | 74.68 | 25.13 | 1.22 |
| 7| 6718 | 83.37 | 28.10 | 1.32 |
| 8| 6914 | 92.55 | 31.16 | 1.43 |
| 9| 6992 | 92.55 | 31.13 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 22.29 | 7.58 | 0.64 |
| 10 | 5 | 287 | 6006 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1705 | 6851 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2222 | 7161 | 99.56 | 38.10 | 1.54 |

