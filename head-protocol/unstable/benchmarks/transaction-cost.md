--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-17 05:38:30.230039398 UTC |
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
| 1| 5836 | 10.95 | 3.49 | 0.52 |
| 2| 6041 | 12.34 | 3.90 | 0.54 |
| 3| 6236 | 14.88 | 4.72 | 0.58 |
| 5| 6638 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14286 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 43.55 | 12.48 | 0.62 |
| 4 | 227 | 858 | 48.95 | 14.14 | 0.69 |
| 5 | 283 | 974 | 63.97 | 18.13 | 0.84 |
| 6 | 339 | 1081 | 65.99 | 19.07 | 0.87 |
| 7 | 395 | 1192 | 80.62 | 22.93 | 1.02 |
| 8 | 449 | 1303 | 96.65 | 27.26 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1825 | 24.37 | 7.71 | 0.48 |
| 2| 1962 | 26.92 | 9.08 | 0.52 |
| 3| 2127 | 28.34 | 10.15 | 0.55 |
| 5| 2345 | 29.93 | 11.94 | 0.58 |
| 10| 3023 | 38.49 | 17.66 | 0.72 |
| 40| 7564 | 99.56 | 54.61 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 813 | 25.49 | 8.78 | 0.46 |
| 3| 831 | 24.13 | 9.06 | 0.45 |
| 5| 1184 | 28.16 | 11.51 | 0.51 |
| 10| 1976 | 38.43 | 17.72 | 0.68 |
| 43| 6673 | 97.30 | 56.08 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.54 | 8.47 | 0.46 |
| 2| 796 | 30.95 | 10.07 | 0.51 |
| 3| 1066 | 34.07 | 11.64 | 0.56 |
| 5| 1332 | 37.62 | 13.96 | 0.61 |
| 10| 1967 | 44.11 | 19.13 | 0.73 |
| 38| 5935 | 97.65 | 52.74 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.87 | 10.16 | 0.53 |
| 2| 897 | 36.56 | 11.60 | 0.57 |
| 3| 937 | 37.84 | 12.60 | 0.59 |
| 5| 1347 | 44.04 | 15.70 | 0.68 |
| 10| 1955 | 53.28 | 21.57 | 0.82 |
| 29| 5008 | 98.90 | 47.01 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.00 | 9.07 | 0.69 |
| 2| 5901 | 32.48 | 10.86 | 0.75 |
| 3| 6115 | 44.81 | 15.08 | 0.89 |
| 4| 6341 | 55.91 | 18.84 | 1.02 |
| 5| 6569 | 66.04 | 22.30 | 1.13 |
| 6| 6483 | 69.34 | 23.34 | 1.16 |
| 7| 6630 | 80.20 | 26.93 | 1.28 |
| 8| 6826 | 89.47 | 30.10 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1137 | 6511 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6855 | 81.11 | 30.83 | 1.33 |
| 10 | 36 | 2051 | 7060 | 91.46 | 35.01 | 1.45 |

