--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-06 04:57:22.558375683 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 169 | 747 | 42.33 | 12.17 | 0.61 |
| 4 | 224 | 858 | 50.45 | 14.52 | 0.70 |
| 5 | 281 | 969 | 59.93 | 17.28 | 0.80 |
| 6 | 337 | 1081 | 74.01 | 21.00 | 0.95 |
| 7 | 394 | 1196 | 80.84 | 23.07 | 1.02 |
| 8 | 450 | 1303 | 80.33 | 23.26 | 1.02 |
| 9 | 507 | 1418 | 93.77 | 26.93 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.00 | 7.62 | 0.48 |
| 2| 1936 | 25.47 | 8.70 | 0.50 |
| 3| 2068 | 27.47 | 9.90 | 0.53 |
| 5| 2495 | 33.23 | 12.86 | 0.62 |
| 10| 3158 | 40.62 | 18.26 | 0.75 |
| 40| 7462 | 95.77 | 53.58 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 620 | 22.84 | 7.38 | 0.42 |
| 2| 839 | 25.43 | 8.78 | 0.46 |
| 3| 914 | 25.14 | 9.33 | 0.46 |
| 5| 1355 | 31.26 | 12.38 | 0.55 |
| 10| 2091 | 40.52 | 18.32 | 0.70 |
| 40| 6348 | 93.45 | 53.02 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 27.50 | 8.46 | 0.46 |
| 2| 732 | 30.23 | 9.85 | 0.50 |
| 3| 898 | 30.26 | 10.55 | 0.51 |
| 5| 1323 | 35.64 | 13.44 | 0.59 |
| 10| 1992 | 44.18 | 19.15 | 0.73 |
| 36| 5929 | 95.54 | 50.92 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.87 | 10.16 | 0.53 |
| 2| 832 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.13 | 12.38 | 0.58 |
| 5| 1404 | 43.99 | 15.69 | 0.68 |
| 10| 2138 | 55.60 | 22.27 | 0.85 |
| 29| 4990 | 99.25 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.00 | 9.07 | 0.69 |
| 2| 6021 | 36.81 | 12.41 | 0.80 |
| 3| 6064 | 43.47 | 14.58 | 0.87 |
| 4| 6209 | 53.68 | 18.04 | 0.99 |
| 5| 6444 | 61.64 | 20.82 | 1.08 |
| 6| 6371 | 62.57 | 20.94 | 1.09 |
| 7| 6657 | 80.25 | 27.00 | 1.29 |
| 8| 7067 | 97.10 | 32.94 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

