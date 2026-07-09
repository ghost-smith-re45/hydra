--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-09 08:58:15.827661943 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.34 | 9.42 | 0.51 |
| 3 | 170 | 747 | 43.74 | 12.55 | 0.63 |
| 4 | 226 | 858 | 52.44 | 15.03 | 0.72 |
| 5 | 282 | 969 | 55.68 | 16.17 | 0.76 |
| 6 | 339 | 1081 | 71.50 | 20.39 | 0.92 |
| 7 | 394 | 1192 | 76.32 | 21.98 | 0.98 |
| 8 | 448 | 1303 | 80.71 | 23.35 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.00 | 7.62 | 0.48 |
| 2| 1914 | 25.47 | 8.70 | 0.50 |
| 3| 2056 | 27.06 | 9.80 | 0.53 |
| 5| 2389 | 31.03 | 12.25 | 0.59 |
| 10| 3089 | 39.89 | 18.04 | 0.74 |
| 40| 7430 | 95.56 | 53.48 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.50 | 7.29 | 0.41 |
| 2| 838 | 25.10 | 8.69 | 0.45 |
| 3| 883 | 25.82 | 9.55 | 0.47 |
| 5| 1176 | 29.03 | 11.77 | 0.52 |
| 10| 2060 | 40.75 | 18.38 | 0.70 |
| 42| 6714 | 99.74 | 56.11 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 27.47 | 8.46 | 0.46 |
| 2| 876 | 29.97 | 9.84 | 0.50 |
| 3| 920 | 32.72 | 11.23 | 0.54 |
| 5| 1315 | 35.61 | 13.43 | 0.59 |
| 10| 1939 | 46.80 | 19.86 | 0.76 |
| 36| 6040 | 98.02 | 51.65 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.16 | 0.53 |
| 2| 760 | 35.14 | 11.16 | 0.55 |
| 3| 955 | 37.91 | 12.62 | 0.59 |
| 5| 1226 | 41.97 | 15.07 | 0.65 |
| 10| 1955 | 53.26 | 21.57 | 0.82 |
| 30| 4990 | 99.98 | 47.88 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5800 | 27.09 | 9.09 | 0.69 |
| 2| 6025 | 37.03 | 12.49 | 0.80 |
| 3| 6085 | 45.08 | 15.16 | 0.89 |
| 4| 6363 | 57.39 | 19.42 | 1.03 |
| 5| 6404 | 61.52 | 20.71 | 1.08 |
| 6| 6581 | 74.46 | 25.10 | 1.22 |
| 7| 6762 | 82.73 | 27.92 | 1.32 |
| 8| 6802 | 86.36 | 28.99 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1709 | 6855 | 81.37 | 30.91 | 1.33 |
| 10 | 40 | 2273 | 7189 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2218 | 7157 | 97.61 | 37.43 | 1.52 |

