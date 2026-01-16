--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-16 04:56:08.721749386 UTC |
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
| 1| 5836 | 10.78 | 3.43 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 19.36 | 6.14 | 0.64 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.35 | 9.42 | 0.51 |
| 3 | 171 | 747 | 43.72 | 12.52 | 0.63 |
| 4 | 227 | 858 | 53.54 | 15.27 | 0.73 |
| 5 | 281 | 969 | 60.84 | 17.40 | 0.81 |
| 6 | 339 | 1081 | 65.12 | 18.98 | 0.86 |
| 7 | 395 | 1196 | 74.66 | 21.51 | 0.96 |
| 8 | 450 | 1303 | 91.03 | 25.81 | 1.13 |
| 9 | 507 | 1414 | 96.07 | 27.42 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.37 | 7.71 | 0.48 |
| 2| 1951 | 25.84 | 8.78 | 0.51 |
| 3| 2069 | 27.31 | 9.86 | 0.53 |
| 5| 2473 | 33.20 | 12.85 | 0.62 |
| 10| 3215 | 41.89 | 18.61 | 0.76 |
| 38| 7358 | 93.16 | 51.55 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.31 | 0.41 |
| 2| 735 | 24.31 | 8.47 | 0.44 |
| 3| 987 | 28.27 | 10.21 | 0.50 |
| 5| 1278 | 30.10 | 12.06 | 0.54 |
| 10| 1911 | 37.39 | 17.42 | 0.66 |
| 41| 6565 | 99.05 | 55.27 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 832 | 29.22 | 9.61 | 0.49 |
| 3| 910 | 32.76 | 11.24 | 0.54 |
| 5| 1272 | 37.10 | 13.79 | 0.61 |
| 10| 2019 | 47.77 | 20.16 | 0.77 |
| 36| 5922 | 96.00 | 51.05 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 33.87 | 10.16 | 0.53 |
| 2| 808 | 35.89 | 11.39 | 0.56 |
| 3| 1015 | 38.59 | 12.82 | 0.60 |
| 5| 1299 | 43.20 | 15.46 | 0.67 |
| 10| 1963 | 53.08 | 21.52 | 0.82 |
| 30| 4933 | 99.12 | 47.68 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 26.96 | 9.06 | 0.69 |
| 2| 6019 | 37.16 | 12.53 | 0.81 |
| 3| 6056 | 42.60 | 14.28 | 0.86 |
| 4| 6258 | 54.86 | 18.47 | 1.00 |
| 5| 6361 | 62.68 | 21.08 | 1.09 |
| 6| 6579 | 73.49 | 24.85 | 1.21 |
| 7| 6665 | 76.95 | 25.89 | 1.25 |
| 8| 6755 | 87.53 | 29.40 | 1.37 |
| 9| 6958 | 95.59 | 32.11 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 283 | 6002 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 567 | 6171 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.28 | 22.29 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.67 | 30.67 | 1.32 |
| 10 | 40 | 2273 | 7190 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2220 | 7160 | 98.24 | 37.65 | 1.53 |

