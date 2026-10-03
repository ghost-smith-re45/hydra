--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-03 10:56:50.776716555 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 751 | 41.11 | 11.88 | 0.60 |
| 4 | 227 | 862 | 54.42 | 15.55 | 0.74 |
| 5 | 282 | 969 | 62.85 | 17.89 | 0.83 |
| 6 | 339 | 1085 | 69.77 | 19.94 | 0.91 |
| 7 | 395 | 1192 | 74.76 | 21.62 | 0.96 |
| 8 | 450 | 1303 | 80.69 | 23.39 | 1.03 |
| 9 | 505 | 1414 | 93.13 | 26.82 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 24.37 | 7.71 | 0.48 |
| 2| 1998 | 26.55 | 9.00 | 0.52 |
| 3| 2148 | 29.34 | 10.43 | 0.56 |
| 5| 2434 | 32.36 | 12.61 | 0.61 |
| 10| 3070 | 40.08 | 18.09 | 0.74 |
| 40| 7527 | 95.41 | 53.47 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.81 | 7.37 | 0.42 |
| 2| 718 | 22.56 | 7.94 | 0.42 |
| 3| 875 | 25.51 | 9.47 | 0.46 |
| 5| 1319 | 31.69 | 12.52 | 0.55 |
| 10| 1985 | 38.50 | 17.73 | 0.68 |
| 42| 6783 | 99.88 | 56.18 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 29.13 | 8.90 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 950 | 33.47 | 11.45 | 0.55 |
| 5| 1300 | 35.80 | 13.48 | 0.59 |
| 10| 1918 | 46.76 | 19.84 | 0.76 |
| 36| 5900 | 96.41 | 51.13 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 831 | 35.92 | 11.40 | 0.56 |
| 3| 1018 | 38.55 | 12.81 | 0.60 |
| 5| 1265 | 42.61 | 15.27 | 0.66 |
| 10| 2039 | 54.58 | 21.98 | 0.84 |
| 30| 4823 | 97.92 | 47.27 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 5822 | 31.48 | 10.48 | 0.74 |
| 3| 6197 | 46.87 | 15.83 | 0.92 |
| 4| 6161 | 50.64 | 17.00 | 0.95 |
| 5| 6406 | 61.83 | 20.78 | 1.08 |
| 6| 6421 | 65.00 | 21.72 | 1.11 |
| 7| 6672 | 79.00 | 26.57 | 1.27 |
| 8| 6977 | 95.34 | 32.15 | 1.46 |
| 9| 6997 | 99.48 | 33.53 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2218 | 7158 | 97.61 | 37.43 | 1.52 |

