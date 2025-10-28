--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-28 04:38:34.628673655 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 169 | 747 | 40.28 | 11.70 | 0.59 |
| 4 | 227 | 858 | 48.82 | 14.11 | 0.68 |
| 5 | 282 | 969 | 63.23 | 18.02 | 0.83 |
| 6 | 338 | 1081 | 75.53 | 21.32 | 0.96 |
| 7 | 393 | 1192 | 72.19 | 20.91 | 0.94 |
| 8 | 449 | 1303 | 87.18 | 24.94 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 23.92 | 7.60 | 0.48 |
| 2| 1975 | 26.39 | 8.96 | 0.51 |
| 3| 2117 | 28.02 | 10.07 | 0.54 |
| 5| 2369 | 31.46 | 12.35 | 0.60 |
| 10| 3222 | 43.50 | 19.04 | 0.78 |
| 39| 7563 | 97.43 | 53.40 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 840 | 25.45 | 8.77 | 0.46 |
| 3| 958 | 26.60 | 9.77 | 0.48 |
| 5| 1214 | 29.91 | 12.01 | 0.53 |
| 10| 2008 | 39.75 | 18.09 | 0.69 |
| 40| 6567 | 99.52 | 54.71 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 29.17 | 8.91 | 0.48 |
| 2| 808 | 31.58 | 10.27 | 0.52 |
| 3| 865 | 32.09 | 11.03 | 0.53 |
| 5| 1342 | 38.49 | 14.22 | 0.62 |
| 10| 2011 | 45.09 | 19.41 | 0.74 |
| 40| 6174 | 99.49 | 54.59 | 1.62 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.83 | 10.15 | 0.53 |
| 2| 860 | 36.52 | 11.59 | 0.57 |
| 3| 985 | 38.62 | 12.83 | 0.60 |
| 5| 1220 | 42.01 | 15.08 | 0.65 |
| 10| 1925 | 52.67 | 21.38 | 0.81 |
| 29| 4853 | 97.69 | 46.59 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.04 | 9.09 | 0.69 |
| 2| 6037 | 36.89 | 12.44 | 0.80 |
| 3| 6141 | 44.92 | 15.10 | 0.89 |
| 4| 6189 | 52.52 | 17.61 | 0.97 |
| 5| 6286 | 59.54 | 19.97 | 1.05 |
| 6| 6505 | 72.43 | 24.32 | 1.20 |
| 7| 6774 | 85.36 | 28.82 | 1.35 |
| 8| 6841 | 94.11 | 31.69 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 567 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1704 | 6851 | 79.53 | 30.29 | 1.31 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

