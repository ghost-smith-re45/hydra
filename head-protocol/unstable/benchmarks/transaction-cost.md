--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-12 05:05:58.120789594 UTC |
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
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6646 | 19.08 | 6.04 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14283 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 169 | 747 | 43.84 | 12.56 | 0.63 |
| 4 | 227 | 858 | 53.70 | 15.30 | 0.73 |
| 5 | 282 | 969 | 61.18 | 17.49 | 0.81 |
| 6 | 341 | 1081 | 75.41 | 21.33 | 0.96 |
| 7 | 396 | 1192 | 76.64 | 22.02 | 0.98 |
| 8 | 448 | 1303 | 85.40 | 24.57 | 1.07 |
| 9 | 504 | 1414 | 94.39 | 27.24 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.37 | 7.71 | 0.48 |
| 2| 1952 | 25.80 | 8.77 | 0.51 |
| 3| 2086 | 27.35 | 9.87 | 0.53 |
| 5| 2516 | 33.86 | 13.03 | 0.63 |
| 10| 3135 | 41.23 | 18.41 | 0.75 |
| 39| 7650 | 98.36 | 53.65 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.50 | 7.29 | 0.41 |
| 2| 743 | 24.04 | 8.40 | 0.44 |
| 3| 962 | 26.98 | 9.86 | 0.48 |
| 5| 1209 | 29.81 | 12.00 | 0.53 |
| 10| 1976 | 38.55 | 17.75 | 0.68 |
| 40| 6512 | 98.73 | 54.46 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.47 | 8.46 | 0.46 |
| 2| 785 | 30.91 | 10.06 | 0.51 |
| 3| 932 | 32.76 | 11.24 | 0.54 |
| 5| 1266 | 34.70 | 13.14 | 0.58 |
| 10| 1871 | 45.79 | 19.55 | 0.74 |
| 36| 6005 | 98.20 | 51.66 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.16 | 0.53 |
| 2| 803 | 35.88 | 11.39 | 0.56 |
| 3| 1007 | 38.55 | 12.81 | 0.60 |
| 5| 1229 | 41.86 | 15.04 | 0.65 |
| 10| 2040 | 54.05 | 21.81 | 0.83 |
| 30| 4925 | 99.64 | 47.80 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.05 | 9.07 | 0.69 |
| 2| 6017 | 37.01 | 12.47 | 0.80 |
| 3| 6085 | 44.81 | 15.06 | 0.89 |
| 4| 6233 | 54.59 | 18.44 | 1.00 |
| 5| 6437 | 65.28 | 21.99 | 1.12 |
| 6| 6606 | 74.37 | 25.06 | 1.22 |
| 7| 6740 | 83.51 | 28.17 | 1.32 |
| 8| 6972 | 96.61 | 32.65 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 566 | 6170 | 38.62 | 14.15 | 0.84 |
| 10 | 40 | 2279 | 7196 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2218 | 7158 | 98.05 | 37.58 | 1.53 |

