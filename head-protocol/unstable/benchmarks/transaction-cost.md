--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-01 05:05:08.792893101 UTC |
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
| 1| 5841 | 10.78 | 3.43 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 19.17 | 6.07 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 635 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 227 | 858 | 48.30 | 14.01 | 0.68 |
| 5 | 281 | 974 | 56.60 | 16.40 | 0.77 |
| 6 | 341 | 1081 | 67.79 | 19.46 | 0.89 |
| 7 | 396 | 1192 | 74.96 | 21.66 | 0.96 |
| 8 | 451 | 1303 | 87.77 | 25.19 | 1.10 |
| 9 | 504 | 1414 | 92.92 | 26.66 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1934 | 25.51 | 8.70 | 0.50 |
| 3| 2076 | 26.94 | 9.77 | 0.53 |
| 5| 2426 | 32.52 | 12.65 | 0.61 |
| 10| 3196 | 41.57 | 18.53 | 0.76 |
| 40| 7594 | 96.72 | 53.82 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.84 | 7.38 | 0.42 |
| 2| 759 | 24.05 | 8.39 | 0.44 |
| 3| 955 | 26.64 | 9.78 | 0.48 |
| 5| 1288 | 30.11 | 12.06 | 0.54 |
| 10| 1990 | 38.42 | 17.72 | 0.68 |
| 40| 6616 | 97.50 | 54.19 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.17 | 8.91 | 0.48 |
| 2| 808 | 30.90 | 10.06 | 0.51 |
| 3| 944 | 30.87 | 10.74 | 0.52 |
| 5| 1341 | 36.36 | 13.65 | 0.60 |
| 10| 2117 | 46.48 | 19.84 | 0.76 |
| 34| 5497 | 96.74 | 49.80 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 711 | 33.83 | 10.15 | 0.53 |
| 2| 761 | 35.21 | 11.18 | 0.55 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1394 | 43.88 | 15.66 | 0.68 |
| 10| 2020 | 54.13 | 21.83 | 0.83 |
| 30| 5027 | 99.98 | 47.94 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 5944 | 35.88 | 12.04 | 0.79 |
| 3| 6164 | 45.77 | 15.44 | 0.90 |
| 4| 6273 | 54.92 | 18.48 | 1.00 |
| 5| 6337 | 60.64 | 20.36 | 1.07 |
| 6| 6482 | 73.35 | 24.68 | 1.21 |
| 7| 6443 | 72.08 | 24.15 | 1.19 |
| 8| 6874 | 93.79 | 31.73 | 1.44 |
| 9| 6874 | 96.54 | 32.41 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.98 | 22.53 | 1.08 |
| 10 | 38 | 2163 | 7126 | 96.19 | 36.84 | 1.51 |

