--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-31 07:01:30.275320645 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7651 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 751 | 40.22 | 11.69 | 0.59 |
| 4 | 228 | 858 | 49.85 | 14.41 | 0.69 |
| 5 | 283 | 969 | 55.95 | 16.20 | 0.76 |
| 6 | 340 | 1081 | 73.85 | 20.99 | 0.95 |
| 7 | 394 | 1192 | 78.51 | 22.47 | 1.00 |
| 8 | 449 | 1303 | 92.15 | 26.14 | 1.14 |
| 9 | 506 | 1414 | 93.34 | 26.81 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 23.92 | 7.60 | 0.48 |
| 2| 1883 | 24.43 | 8.40 | 0.49 |
| 3| 2186 | 29.38 | 10.44 | 0.56 |
| 5| 2437 | 32.37 | 12.61 | 0.61 |
| 10| 3222 | 41.97 | 18.62 | 0.77 |
| 39| 7526 | 97.92 | 53.54 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.84 | 7.37 | 0.42 |
| 2| 818 | 25.57 | 8.80 | 0.46 |
| 3| 828 | 24.09 | 9.03 | 0.45 |
| 5| 1267 | 30.07 | 12.05 | 0.54 |
| 10| 1870 | 36.42 | 17.17 | 0.65 |
| 42| 6732 | 99.55 | 56.06 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 27.54 | 8.47 | 0.46 |
| 2| 838 | 29.26 | 9.62 | 0.49 |
| 3| 960 | 30.87 | 10.74 | 0.52 |
| 5| 1377 | 36.05 | 13.56 | 0.60 |
| 10| 1949 | 46.65 | 19.81 | 0.76 |
| 36| 5907 | 96.20 | 51.04 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.15 | 0.53 |
| 2| 805 | 35.92 | 11.40 | 0.56 |
| 3| 951 | 37.84 | 12.60 | 0.59 |
| 5| 1327 | 43.28 | 15.48 | 0.67 |
| 10| 2090 | 54.63 | 21.99 | 0.84 |
| 28| 4758 | 95.41 | 45.32 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.97 | 9.06 | 0.69 |
| 2| 5886 | 32.57 | 10.89 | 0.75 |
| 3| 6113 | 46.14 | 15.55 | 0.90 |
| 4| 6069 | 49.27 | 16.49 | 0.93 |
| 5| 6361 | 64.17 | 21.59 | 1.10 |
| 6| 6478 | 73.76 | 24.82 | 1.21 |
| 7| 6604 | 78.66 | 26.44 | 1.27 |
| 8| 6789 | 87.75 | 29.50 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.67 | 10.88 | 0.74 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

