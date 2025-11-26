--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-26 04:45:40.619779169 UTC |
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
| 2| 6035 | 12.54 | 3.97 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7651 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 41.34 | 11.99 | 0.60 |
| 4 | 228 | 858 | 52.40 | 15.00 | 0.72 |
| 5 | 282 | 969 | 62.28 | 17.72 | 0.82 |
| 6 | 338 | 1085 | 75.52 | 21.35 | 0.96 |
| 7 | 395 | 1196 | 82.43 | 23.41 | 1.04 |
| 8 | 450 | 1303 | 90.92 | 25.73 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.29 | 7.69 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2013 | 25.87 | 9.47 | 0.52 |
| 5| 2408 | 31.40 | 12.34 | 0.60 |
| 10| 3088 | 39.46 | 17.94 | 0.73 |
| 40| 7694 | 98.63 | 54.38 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.80 | 7.36 | 0.41 |
| 2| 723 | 22.56 | 7.94 | 0.42 |
| 3| 872 | 25.13 | 9.34 | 0.46 |
| 5| 1175 | 29.18 | 11.79 | 0.52 |
| 10| 2040 | 39.65 | 18.06 | 0.69 |
| 43| 6816 | 99.69 | 56.77 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.51 | 8.47 | 0.46 |
| 2| 785 | 30.95 | 10.07 | 0.51 |
| 3| 944 | 30.90 | 10.74 | 0.52 |
| 5| 1337 | 35.69 | 13.45 | 0.59 |
| 10| 2127 | 46.46 | 19.85 | 0.76 |
| 35| 5605 | 92.45 | 49.32 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.16 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 1000 | 38.66 | 12.84 | 0.60 |
| 5| 1216 | 41.93 | 15.06 | 0.65 |
| 10| 1956 | 53.16 | 21.54 | 0.82 |
| 29| 4752 | 96.80 | 46.30 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 26.96 | 9.05 | 0.69 |
| 2| 5932 | 35.80 | 12.04 | 0.79 |
| 3| 6109 | 42.80 | 14.39 | 0.87 |
| 4| 6332 | 55.71 | 18.85 | 1.01 |
| 5| 6386 | 63.72 | 21.44 | 1.10 |
| 6| 6567 | 74.56 | 25.11 | 1.22 |
| 7| 6718 | 83.43 | 28.11 | 1.32 |
| 8| 6693 | 84.71 | 28.44 | 1.33 |
| 9| 6981 | 98.64 | 33.18 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 56 | 5867 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 284 | 6003 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1134 | 6509 | 60.17 | 22.59 | 1.09 |
| 10 | 39 | 2222 | 7162 | 97.61 | 37.43 | 1.52 |

