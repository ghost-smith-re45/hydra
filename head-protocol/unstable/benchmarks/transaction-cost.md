--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-01 10:34:26.494395778 UTC |
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
| 1| 5837 | 10.95 | 3.49 | 0.52 |
| 2| 6038 | 12.72 | 4.03 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 43.91 | 12.57 | 0.63 |
| 4 | 227 | 862 | 48.20 | 13.99 | 0.68 |
| 5 | 284 | 974 | 60.84 | 17.38 | 0.81 |
| 6 | 340 | 1081 | 71.91 | 20.53 | 0.93 |
| 7 | 397 | 1192 | 82.43 | 23.33 | 1.04 |
| 8 | 448 | 1303 | 89.09 | 25.35 | 1.11 |
| 9 | 505 | 1414 | 91.57 | 26.45 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1948 | 25.51 | 8.70 | 0.50 |
| 3| 2146 | 28.76 | 10.27 | 0.55 |
| 5| 2475 | 32.49 | 12.64 | 0.61 |
| 10| 3130 | 41.23 | 18.42 | 0.75 |
| 39| 7619 | 99.58 | 53.96 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.77 | 7.36 | 0.41 |
| 2| 825 | 25.56 | 8.80 | 0.46 |
| 3| 949 | 26.61 | 9.77 | 0.48 |
| 5| 1291 | 32.29 | 12.69 | 0.56 |
| 10| 2100 | 43.22 | 19.06 | 0.73 |
| 41| 6609 | 97.01 | 54.71 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.47 | 9.38 | 0.48 |
| 3| 865 | 32.08 | 11.03 | 0.53 |
| 5| 1283 | 37.81 | 14.01 | 0.61 |
| 10| 2094 | 46.44 | 19.83 | 0.76 |
| 35| 5870 | 96.37 | 50.52 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.83 | 10.16 | 0.53 |
| 2| 826 | 35.85 | 11.38 | 0.56 |
| 3| 975 | 38.59 | 12.82 | 0.60 |
| 5| 1205 | 41.89 | 15.05 | 0.65 |
| 10| 2045 | 54.88 | 22.05 | 0.84 |
| 29| 4881 | 97.98 | 46.70 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.08 | 0.69 |
| 2| 5823 | 31.52 | 10.49 | 0.74 |
| 3| 6168 | 46.07 | 15.51 | 0.91 |
| 4| 6095 | 49.28 | 16.50 | 0.94 |
| 5| 6461 | 64.61 | 21.79 | 1.11 |
| 6| 6413 | 62.77 | 21.02 | 1.09 |
| 7| 6540 | 74.73 | 25.04 | 1.22 |
| 8| 6857 | 92.32 | 31.09 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 10 | 568 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1710 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7160 | 99.38 | 38.04 | 1.54 |

