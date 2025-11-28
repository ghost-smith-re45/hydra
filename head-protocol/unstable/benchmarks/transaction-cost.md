--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-28 04:36:38.058574043 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6042 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7644 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 42.61 | 12.28 | 0.62 |
| 4 | 226 | 858 | 48.06 | 13.95 | 0.68 |
| 5 | 281 | 969 | 63.08 | 18.04 | 0.83 |
| 6 | 340 | 1081 | 66.15 | 19.04 | 0.87 |
| 7 | 395 | 1192 | 73.04 | 21.25 | 0.95 |
| 8 | 450 | 1303 | 82.94 | 23.88 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 23.92 | 7.60 | 0.48 |
| 2| 1966 | 26.47 | 8.98 | 0.52 |
| 3| 2097 | 27.94 | 10.05 | 0.54 |
| 5| 2322 | 30.34 | 12.04 | 0.58 |
| 10| 3365 | 44.12 | 19.24 | 0.79 |
| 39| 7524 | 95.14 | 52.78 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.54 | 7.30 | 0.41 |
| 2| 831 | 25.04 | 8.66 | 0.45 |
| 3| 895 | 25.02 | 9.30 | 0.46 |
| 5| 1258 | 30.94 | 12.31 | 0.54 |
| 10| 2050 | 41.65 | 18.62 | 0.71 |
| 41| 6528 | 93.97 | 53.85 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 26.83 | 8.26 | 0.45 |
| 2| 788 | 30.98 | 10.08 | 0.51 |
| 3| 955 | 33.51 | 11.47 | 0.55 |
| 5| 1343 | 38.29 | 14.17 | 0.62 |
| 10| 1957 | 43.54 | 18.97 | 0.72 |
| 37| 6131 | 99.25 | 52.63 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.81 | 11.37 | 0.56 |
| 3| 1020 | 38.62 | 12.83 | 0.60 |
| 5| 1363 | 44.07 | 15.71 | 0.68 |
| 10| 2147 | 56.09 | 22.43 | 0.86 |
| 29| 5014 | 99.69 | 47.17 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.08 | 9.08 | 0.69 |
| 2| 5969 | 36.81 | 12.42 | 0.80 |
| 3| 6020 | 41.63 | 13.94 | 0.85 |
| 4| 6133 | 48.00 | 16.05 | 0.92 |
| 5| 6393 | 61.94 | 20.90 | 1.08 |
| 6| 6450 | 67.00 | 22.49 | 1.14 |
| 7| 6581 | 79.84 | 26.85 | 1.28 |
| 8| 6780 | 91.36 | 30.71 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2223 | 7162 | 98.93 | 37.88 | 1.54 |

