--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-15 08:06:55.754566126 UTC |
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
| 1| 5834 | 10.86 | 3.46 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.81 | 4.69 | 0.58 |
| 5| 6646 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 41.38 | 11.97 | 0.60 |
| 4 | 226 | 858 | 49.69 | 14.35 | 0.69 |
| 5 | 285 | 974 | 62.72 | 17.89 | 0.83 |
| 6 | 339 | 1081 | 68.22 | 19.64 | 0.89 |
| 7 | 393 | 1196 | 84.18 | 23.78 | 1.05 |
| 8 | 449 | 1303 | 87.42 | 24.96 | 1.09 |
| 9 | 506 | 1414 | 97.94 | 27.86 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2100 | 27.94 | 10.05 | 0.54 |
| 5| 2428 | 31.96 | 12.51 | 0.61 |
| 10| 3170 | 41.73 | 18.57 | 0.76 |
| 39| 7276 | 93.98 | 52.40 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.50 | 7.30 | 0.41 |
| 2| 797 | 25.47 | 8.78 | 0.45 |
| 3| 906 | 25.83 | 9.55 | 0.47 |
| 5| 1210 | 29.03 | 11.76 | 0.52 |
| 10| 1956 | 38.76 | 17.81 | 0.68 |
| 42| 6800 | 99.01 | 55.93 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.13 | 8.90 | 0.48 |
| 2| 778 | 30.94 | 10.07 | 0.51 |
| 3| 926 | 32.75 | 11.24 | 0.54 |
| 5| 1218 | 34.33 | 13.03 | 0.58 |
| 10| 2073 | 48.40 | 20.34 | 0.78 |
| 38| 6007 | 97.90 | 52.84 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.79 | 10.15 | 0.53 |
| 2| 799 | 35.85 | 11.38 | 0.56 |
| 3| 967 | 37.84 | 12.60 | 0.59 |
| 5| 1340 | 43.24 | 15.47 | 0.67 |
| 10| 2038 | 54.62 | 21.98 | 0.84 |
| 29| 4999 | 99.54 | 47.19 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.12 | 9.10 | 0.69 |
| 2| 5845 | 31.44 | 10.45 | 0.74 |
| 3| 6161 | 46.09 | 15.52 | 0.91 |
| 4| 6302 | 54.77 | 18.47 | 1.00 |
| 5| 6481 | 64.99 | 21.94 | 1.12 |
| 6| 6731 | 73.44 | 24.81 | 1.22 |
| 7| 6923 | 86.36 | 29.23 | 1.36 |
| 8| 6844 | 92.75 | 31.20 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 568 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1137 | 6512 | 61.31 | 22.98 | 1.10 |
| 10 | 39 | 2218 | 7157 | 98.49 | 37.73 | 1.53 |

