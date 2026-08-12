--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-12 06:48:02.084734461 UTC |
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
| 2| 6037 | 12.73 | 4.04 | 0.55 |
| 3| 6242 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 44.02 | 12.62 | 0.63 |
| 4 | 225 | 862 | 51.13 | 14.72 | 0.71 |
| 5 | 284 | 969 | 62.38 | 17.74 | 0.82 |
| 6 | 340 | 1081 | 74.38 | 21.00 | 0.95 |
| 7 | 394 | 1192 | 80.77 | 23.01 | 1.02 |
| 8 | 449 | 1303 | 82.57 | 23.79 | 1.05 |
| 9 | 506 | 1414 | 98.71 | 28.16 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 2011 | 26.96 | 9.09 | 0.52 |
| 3| 2149 | 28.47 | 10.18 | 0.55 |
| 5| 2280 | 29.33 | 11.76 | 0.57 |
| 10| 3142 | 40.69 | 18.28 | 0.75 |
| 38| 7344 | 95.34 | 52.12 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.80 | 7.37 | 0.41 |
| 2| 854 | 25.33 | 8.74 | 0.46 |
| 3| 882 | 25.13 | 9.32 | 0.46 |
| 5| 1189 | 29.03 | 11.75 | 0.52 |
| 10| 1915 | 37.33 | 17.43 | 0.66 |
| 40| 6591 | 95.83 | 53.72 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 29.13 | 8.90 | 0.48 |
| 2| 828 | 31.58 | 10.26 | 0.52 |
| 3| 1040 | 31.61 | 10.96 | 0.53 |
| 5| 1217 | 37.06 | 13.78 | 0.60 |
| 10| 2048 | 48.42 | 20.34 | 0.78 |
| 36| 5805 | 94.95 | 50.71 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.79 | 10.15 | 0.53 |
| 2| 864 | 36.60 | 11.61 | 0.57 |
| 3| 942 | 37.88 | 12.61 | 0.59 |
| 5| 1253 | 42.64 | 15.28 | 0.66 |
| 10| 2021 | 54.43 | 21.92 | 0.84 |
| 29| 4872 | 98.43 | 46.85 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.05 | 9.07 | 0.69 |
| 2| 5897 | 32.60 | 10.89 | 0.75 |
| 3| 6140 | 45.76 | 15.46 | 0.90 |
| 4| 6302 | 56.20 | 18.96 | 1.02 |
| 5| 6380 | 62.89 | 21.09 | 1.09 |
| 6| 6481 | 68.17 | 22.85 | 1.15 |
| 7| 6697 | 82.31 | 27.73 | 1.31 |
| 8| 6977 | 93.46 | 31.49 | 1.44 |
| 9| 7009 | 99.96 | 33.80 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2221 | 7161 | 97.61 | 37.43 | 1.52 |

