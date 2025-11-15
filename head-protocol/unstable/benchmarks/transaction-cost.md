--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-15 04:37:54.766399205 UTC |
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
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14286 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 747 | 42.77 | 12.32 | 0.62 |
| 4 | 226 | 858 | 50.96 | 14.62 | 0.71 |
| 5 | 284 | 969 | 57.67 | 16.65 | 0.78 |
| 6 | 339 | 1081 | 67.45 | 19.38 | 0.88 |
| 7 | 393 | 1192 | 72.03 | 20.91 | 0.94 |
| 8 | 452 | 1303 | 82.26 | 23.76 | 1.04 |
| 9 | 505 | 1414 | 98.53 | 28.12 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1928 | 25.55 | 8.71 | 0.50 |
| 3| 2054 | 26.91 | 9.76 | 0.53 |
| 5| 2426 | 32.65 | 12.70 | 0.61 |
| 10| 3281 | 43.07 | 18.93 | 0.78 |
| 39| 7462 | 94.19 | 52.51 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 695 | 22.62 | 7.97 | 0.42 |
| 3| 973 | 27.07 | 9.89 | 0.48 |
| 5| 1199 | 29.19 | 11.80 | 0.52 |
| 10| 2152 | 43.43 | 19.10 | 0.73 |
| 41| 6439 | 94.70 | 54.04 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.13 | 8.90 | 0.48 |
| 2| 803 | 30.95 | 10.07 | 0.51 |
| 3| 1009 | 31.57 | 10.95 | 0.53 |
| 5| 1284 | 35.05 | 13.25 | 0.59 |
| 10| 2080 | 48.89 | 20.48 | 0.78 |
| 37| 6029 | 98.65 | 52.43 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 1018 | 38.66 | 12.84 | 0.60 |
| 5| 1259 | 42.49 | 15.24 | 0.66 |
| 10| 2088 | 54.85 | 22.04 | 0.84 |
| 29| 4959 | 98.81 | 46.97 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 27.05 | 9.08 | 0.69 |
| 2| 5891 | 34.94 | 11.68 | 0.78 |
| 3| 6029 | 41.63 | 13.94 | 0.85 |
| 4| 6325 | 56.07 | 18.92 | 1.02 |
| 5| 6335 | 63.49 | 21.30 | 1.10 |
| 6| 6648 | 76.53 | 25.86 | 1.25 |
| 7| 6741 | 83.76 | 28.22 | 1.33 |
| 8| 6974 | 93.51 | 31.56 | 1.44 |
| 9| 6943 | 95.68 | 32.23 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 283 | 6002 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 566 | 6170 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.05 | 37.58 | 1.53 |

