--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-29 05:04:24.251519716 UTC |
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
| 1| 5836 | 10.48 | 3.33 | 0.52 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.98 | 6.00 | 0.64 |
| 10| 7645 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 751 | 43.60 | 12.49 | 0.63 |
| 4 | 226 | 858 | 47.93 | 13.90 | 0.68 |
| 5 | 281 | 974 | 64.83 | 18.40 | 0.85 |
| 6 | 341 | 1081 | 65.14 | 18.82 | 0.86 |
| 7 | 395 | 1192 | 86.62 | 24.45 | 1.08 |
| 8 | 448 | 1303 | 89.97 | 25.61 | 1.12 |
| 9 | 506 | 1414 | 95.98 | 27.45 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1880 | 24.40 | 8.40 | 0.49 |
| 3| 2121 | 28.09 | 10.09 | 0.54 |
| 5| 2435 | 31.84 | 12.48 | 0.60 |
| 10| 3093 | 39.36 | 17.91 | 0.73 |
| 42| 7774 | 99.01 | 55.81 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 816 | 25.20 | 8.72 | 0.45 |
| 3| 830 | 24.09 | 9.04 | 0.45 |
| 5| 1191 | 28.77 | 11.71 | 0.52 |
| 10| 2006 | 38.61 | 17.77 | 0.68 |
| 40| 6379 | 96.39 | 53.82 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 27.50 | 8.46 | 0.46 |
| 2| 805 | 30.94 | 10.07 | 0.51 |
| 3| 946 | 30.94 | 10.75 | 0.52 |
| 5| 1356 | 38.49 | 14.22 | 0.62 |
| 10| 1967 | 44.11 | 19.13 | 0.73 |
| 37| 6237 | 99.88 | 52.83 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 805 | 35.88 | 11.39 | 0.56 |
| 3| 1046 | 39.23 | 13.02 | 0.61 |
| 5| 1242 | 42.45 | 15.23 | 0.66 |
| 10| 1853 | 51.78 | 21.12 | 0.80 |
| 28| 4648 | 94.53 | 45.08 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 27.12 | 9.10 | 0.69 |
| 2| 5930 | 35.84 | 12.03 | 0.79 |
| 3| 6063 | 44.68 | 15.04 | 0.89 |
| 4| 6220 | 51.43 | 17.25 | 0.96 |
| 5| 6451 | 65.28 | 22.05 | 1.12 |
| 6| 6599 | 72.39 | 24.40 | 1.20 |
| 7| 6807 | 84.66 | 28.62 | 1.34 |
| 8| 6881 | 92.38 | 31.16 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1136 | 6510 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 81.30 | 30.89 | 1.33 |
| 10 | 38 | 2160 | 7123 | 97.33 | 37.23 | 1.52 |

