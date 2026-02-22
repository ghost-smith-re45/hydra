--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-22 06:34:54.083084758 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.26 | 9.23 | 0.79 |
| 43| 14281 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10042 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 41.40 | 11.97 | 0.60 |
| 4 | 226 | 862 | 51.12 | 14.69 | 0.71 |
| 5 | 284 | 969 | 60.69 | 17.34 | 0.81 |
| 6 | 341 | 1085 | 73.55 | 20.85 | 0.94 |
| 7 | 395 | 1192 | 78.57 | 22.44 | 1.00 |
| 8 | 450 | 1303 | 87.53 | 25.08 | 1.10 |
| 10 | 561 | 1525 | 99.80 | 28.71 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1824 | 24.00 | 7.62 | 0.48 |
| 2| 1991 | 26.55 | 9.00 | 0.52 |
| 3| 2053 | 27.02 | 9.79 | 0.53 |
| 5| 2384 | 30.92 | 12.22 | 0.59 |
| 10| 3213 | 41.57 | 18.53 | 0.76 |
| 41| 7777 | 96.56 | 54.48 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.81 | 7.37 | 0.42 |
| 2| 813 | 25.59 | 8.81 | 0.46 |
| 3| 910 | 25.07 | 9.31 | 0.46 |
| 5| 1225 | 29.92 | 12.02 | 0.53 |
| 10| 1865 | 37.24 | 17.40 | 0.66 |
| 45| 6707 | 96.98 | 57.32 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.50 | 8.46 | 0.46 |
| 2| 829 | 31.58 | 10.26 | 0.52 |
| 3| 944 | 30.94 | 10.75 | 0.52 |
| 5| 1206 | 36.72 | 13.68 | 0.60 |
| 10| 1945 | 44.00 | 19.10 | 0.73 |
| 34| 5581 | 92.05 | 48.60 | 1.49 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 1034 | 39.26 | 13.03 | 0.61 |
| 5| 1207 | 41.82 | 15.03 | 0.65 |
| 10| 2132 | 55.43 | 22.24 | 0.85 |
| 29| 4826 | 97.50 | 46.56 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 26.96 | 9.06 | 0.69 |
| 2| 5892 | 34.87 | 11.65 | 0.78 |
| 3| 6014 | 41.52 | 13.90 | 0.85 |
| 4| 6215 | 53.89 | 18.13 | 0.99 |
| 5| 6454 | 65.25 | 21.96 | 1.12 |
| 6| 6491 | 69.94 | 23.48 | 1.17 |
| 7| 6750 | 80.44 | 27.10 | 1.29 |
| 8| 6630 | 80.53 | 27.06 | 1.29 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 5 | 286 | 6005 | 28.21 | 10.04 | 0.71 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6512 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1710 | 6857 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |

