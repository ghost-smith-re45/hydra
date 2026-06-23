--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-23 09:04:44.963148102 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.53 | 3.97 | 0.55 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.22 | 12.14 | 0.61 |
| 4 | 226 | 858 | 52.27 | 14.96 | 0.72 |
| 5 | 283 | 969 | 63.25 | 18.11 | 0.83 |
| 6 | 339 | 1085 | 63.83 | 18.51 | 0.85 |
| 7 | 394 | 1192 | 83.11 | 23.66 | 1.04 |
| 8 | 449 | 1303 | 89.92 | 25.61 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.00 | 7.62 | 0.48 |
| 2| 2006 | 26.84 | 9.06 | 0.52 |
| 3| 2139 | 28.05 | 10.08 | 0.54 |
| 5| 2514 | 32.95 | 12.79 | 0.62 |
| 10| 2973 | 37.86 | 17.47 | 0.71 |
| 41| 7765 | 99.44 | 55.27 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.77 | 7.36 | 0.42 |
| 2| 795 | 25.52 | 8.80 | 0.45 |
| 3| 968 | 26.92 | 9.85 | 0.48 |
| 5| 1251 | 31.17 | 12.38 | 0.55 |
| 10| 1996 | 39.47 | 18.04 | 0.69 |
| 42| 6707 | 98.51 | 55.76 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.51 | 8.47 | 0.46 |
| 2| 885 | 29.97 | 9.84 | 0.50 |
| 3| 910 | 32.65 | 11.21 | 0.53 |
| 5| 1320 | 35.69 | 13.45 | 0.59 |
| 10| 2168 | 46.92 | 19.99 | 0.77 |
| 36| 5951 | 97.76 | 51.53 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.16 | 0.53 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 980 | 38.55 | 12.81 | 0.60 |
| 5| 1224 | 41.97 | 15.07 | 0.65 |
| 10| 2026 | 54.02 | 21.80 | 0.83 |
| 29| 4900 | 98.11 | 46.75 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.00 | 9.07 | 0.69 |
| 2| 5996 | 37.05 | 12.48 | 0.80 |
| 3| 6166 | 45.86 | 15.46 | 0.90 |
| 4| 6288 | 54.94 | 18.52 | 1.00 |
| 5| 6541 | 66.89 | 22.67 | 1.14 |
| 6| 6343 | 63.83 | 21.30 | 1.10 |
| 7| 6653 | 76.57 | 25.78 | 1.25 |
| 8| 6709 | 90.86 | 30.54 | 1.40 |
| 9| 6823 | 88.10 | 29.61 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.05 | 37.58 | 1.53 |

