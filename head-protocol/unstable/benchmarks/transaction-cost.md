--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-09 04:38:55.231400827 UTC |
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
| 1| 5837 | 10.26 | 3.25 | 0.51 |
| 2| 6037 | 13.10 | 4.17 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.38 | 9.27 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1270 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 41.23 | 11.93 | 0.60 |
| 4 | 228 | 858 | 48.42 | 14.07 | 0.68 |
| 5 | 282 | 969 | 56.11 | 16.27 | 0.76 |
| 6 | 339 | 1081 | 73.10 | 20.74 | 0.94 |
| 7 | 395 | 1192 | 77.09 | 22.18 | 0.99 |
| 8 | 449 | 1303 | 84.79 | 24.32 | 1.07 |
| 9 | 506 | 1414 | 91.50 | 26.49 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.29 | 7.69 | 0.48 |
| 2| 1936 | 25.92 | 8.80 | 0.51 |
| 3| 2119 | 27.94 | 10.05 | 0.54 |
| 5| 2418 | 32.04 | 12.53 | 0.61 |
| 10| 3209 | 41.43 | 18.49 | 0.76 |
| 42| 7890 | 98.91 | 55.82 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.81 | 7.37 | 0.42 |
| 2| 811 | 25.56 | 8.79 | 0.46 |
| 3| 1035 | 27.52 | 10.03 | 0.49 |
| 5| 1284 | 30.09 | 12.07 | 0.54 |
| 10| 1910 | 38.59 | 17.78 | 0.67 |
| 41| 6616 | 96.14 | 54.42 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.50 | 8.46 | 0.46 |
| 2| 849 | 31.66 | 10.28 | 0.52 |
| 3| 1016 | 31.54 | 10.94 | 0.53 |
| 5| 1369 | 36.43 | 13.67 | 0.60 |
| 10| 1929 | 46.73 | 19.83 | 0.76 |
| 36| 5881 | 96.50 | 51.17 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 761 | 35.17 | 11.17 | 0.55 |
| 3| 1002 | 38.96 | 12.93 | 0.60 |
| 5| 1157 | 41.22 | 14.85 | 0.64 |
| 10| 2111 | 54.84 | 22.06 | 0.85 |
| 30| 4918 | 98.70 | 47.54 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5786 | 27.00 | 9.08 | 0.69 |
| 2| 5956 | 35.96 | 12.07 | 0.79 |
| 3| 6138 | 46.07 | 15.52 | 0.90 |
| 4| 6279 | 55.17 | 18.59 | 1.01 |
| 5| 6420 | 64.50 | 21.67 | 1.11 |
| 6| 6316 | 61.45 | 20.48 | 1.07 |
| 7| 6685 | 82.87 | 27.90 | 1.32 |
| 8| 7180 | 95.85 | 32.51 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2163 | 7125 | 97.77 | 37.38 | 1.52 |

