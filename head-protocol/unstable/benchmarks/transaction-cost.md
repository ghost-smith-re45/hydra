--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-17 07:14:54.178612663 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 99.06 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.38 | 9.43 | 0.51 |
| 3 | 170 | 747 | 42.62 | 12.24 | 0.62 |
| 4 | 225 | 862 | 53.76 | 15.32 | 0.73 |
| 5 | 284 | 969 | 59.85 | 17.24 | 0.80 |
| 6 | 338 | 1081 | 65.97 | 19.06 | 0.87 |
| 7 | 394 | 1192 | 72.51 | 20.99 | 0.94 |
| 8 | 450 | 1303 | 94.54 | 26.76 | 1.16 |
| 9 | 505 | 1414 | 97.78 | 27.77 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.29 | 7.69 | 0.48 |
| 2| 1924 | 25.47 | 8.70 | 0.50 |
| 3| 2014 | 25.87 | 9.47 | 0.52 |
| 5| 2440 | 32.33 | 12.62 | 0.61 |
| 10| 3004 | 38.08 | 17.53 | 0.72 |
| 39| 7545 | 97.98 | 53.52 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 22.81 | 7.37 | 0.42 |
| 2| 818 | 25.56 | 8.80 | 0.46 |
| 3| 830 | 24.09 | 9.04 | 0.45 |
| 5| 1132 | 28.11 | 11.49 | 0.51 |
| 10| 1946 | 38.76 | 17.81 | 0.68 |
| 41| 6598 | 98.85 | 55.19 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 27.54 | 8.47 | 0.46 |
| 2| 840 | 29.26 | 9.62 | 0.49 |
| 3| 1035 | 31.53 | 10.94 | 0.53 |
| 5| 1253 | 37.73 | 13.99 | 0.61 |
| 10| 2073 | 44.82 | 19.35 | 0.74 |
| 35| 5989 | 98.08 | 51.04 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 761 | 35.17 | 11.17 | 0.55 |
| 3| 1005 | 38.58 | 12.82 | 0.60 |
| 5| 1200 | 41.90 | 15.05 | 0.65 |
| 10| 2024 | 54.10 | 21.82 | 0.83 |
| 29| 4865 | 97.62 | 46.61 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5916 | 34.94 | 11.70 | 0.78 |
| 3| 6109 | 45.69 | 15.41 | 0.90 |
| 4| 6091 | 46.93 | 15.66 | 0.91 |
| 5| 6291 | 59.73 | 20.04 | 1.05 |
| 6| 6492 | 70.05 | 23.49 | 1.17 |
| 7| 6572 | 72.52 | 24.33 | 1.20 |
| 8| 6937 | 94.27 | 31.77 | 1.45 |
| 9| 6999 | 95.14 | 31.92 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.49 | 37.73 | 1.53 |

