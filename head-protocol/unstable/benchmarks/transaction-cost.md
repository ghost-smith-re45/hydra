--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-13 05:37:12.869252294 UTC |
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
| 1| 5836 | 11.04 | 3.52 | 0.52 |
| 2| 6037 | 12.78 | 4.06 | 0.55 |
| 3| 6236 | 14.90 | 4.72 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.09 | 9.17 | 0.79 |
| 43| 14279 | 99.13 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 41.11 | 11.90 | 0.60 |
| 4 | 227 | 858 | 48.28 | 14.01 | 0.68 |
| 5 | 284 | 974 | 56.20 | 16.33 | 0.76 |
| 6 | 338 | 1081 | 74.98 | 21.19 | 0.96 |
| 7 | 394 | 1192 | 82.57 | 23.44 | 1.04 |
| 8 | 450 | 1303 | 94.47 | 26.69 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.29 | 7.69 | 0.48 |
| 2| 1886 | 24.85 | 8.50 | 0.50 |
| 3| 2013 | 25.95 | 9.49 | 0.52 |
| 5| 2384 | 30.89 | 12.21 | 0.59 |
| 10| 3216 | 42.08 | 18.65 | 0.77 |
| 42| 7710 | 99.52 | 55.94 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.39 | 0.41 |
| 2| 803 | 25.55 | 8.80 | 0.46 |
| 3| 878 | 25.78 | 9.53 | 0.47 |
| 5| 1237 | 31.01 | 12.32 | 0.54 |
| 10| 1933 | 38.52 | 17.75 | 0.67 |
| 41| 6455 | 95.81 | 54.36 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 27.54 | 8.47 | 0.46 |
| 2| 844 | 31.62 | 10.27 | 0.52 |
| 3| 1034 | 31.65 | 10.97 | 0.53 |
| 5| 1238 | 34.37 | 13.04 | 0.58 |
| 10| 2023 | 47.14 | 19.97 | 0.76 |
| 35| 5640 | 93.07 | 49.49 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 818 | 35.88 | 11.39 | 0.56 |
| 3| 951 | 37.88 | 12.61 | 0.59 |
| 5| 1323 | 43.36 | 15.49 | 0.67 |
| 10| 2189 | 55.49 | 22.24 | 0.86 |
| 28| 4868 | 96.92 | 45.76 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.05 | 9.07 | 0.69 |
| 2| 5998 | 37.09 | 12.51 | 0.80 |
| 3| 6019 | 43.70 | 14.67 | 0.87 |
| 4| 6189 | 50.29 | 16.87 | 0.95 |
| 5| 6345 | 56.64 | 19.03 | 1.02 |
| 6| 6449 | 67.96 | 22.83 | 1.15 |
| 7| 6460 | 73.80 | 24.72 | 1.21 |
| 8| 6628 | 79.67 | 26.64 | 1.28 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1138 | 6512 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.05 | 37.58 | 1.53 |

