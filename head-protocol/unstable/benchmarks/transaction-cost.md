--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-22 08:53:56.576057207 UTC |
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
| 1| 5834 | 10.36 | 3.28 | 0.51 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.42 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2164 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 40.40 | 11.75 | 0.59 |
| 4 | 227 | 858 | 52.29 | 14.97 | 0.72 |
| 5 | 281 | 974 | 58.41 | 16.86 | 0.79 |
| 6 | 340 | 1081 | 71.89 | 20.45 | 0.93 |
| 7 | 393 | 1192 | 84.95 | 24.02 | 1.06 |
| 8 | 449 | 1303 | 85.81 | 24.67 | 1.08 |
| 9 | 505 | 1414 | 94.19 | 27.08 | 1.17 |
| 10 | 560 | 1525 | 97.99 | 28.52 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2060 | 27.32 | 9.86 | 0.53 |
| 5| 2388 | 31.34 | 12.32 | 0.60 |
| 10| 3225 | 41.53 | 18.52 | 0.76 |
| 40| 7666 | 99.03 | 54.49 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 622 | 22.53 | 7.32 | 0.41 |
| 2| 756 | 23.63 | 8.24 | 0.43 |
| 3| 897 | 25.79 | 9.53 | 0.47 |
| 5| 1271 | 30.90 | 12.30 | 0.54 |
| 10| 1875 | 38.06 | 17.63 | 0.67 |
| 42| 6670 | 97.63 | 55.51 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.09 | 8.89 | 0.48 |
| 2| 770 | 30.95 | 10.07 | 0.51 |
| 3| 899 | 30.23 | 10.54 | 0.51 |
| 5| 1206 | 34.33 | 13.03 | 0.57 |
| 10| 1977 | 44.23 | 19.16 | 0.73 |
| 36| 6106 | 99.38 | 52.03 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.79 | 10.15 | 0.53 |
| 2| 802 | 35.89 | 11.39 | 0.56 |
| 3| 891 | 37.24 | 12.41 | 0.58 |
| 5| 1297 | 43.35 | 15.49 | 0.67 |
| 10| 1990 | 54.06 | 21.81 | 0.83 |
| 30| 5055 | 99.68 | 47.85 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 26.92 | 9.04 | 0.69 |
| 2| 5937 | 35.91 | 12.07 | 0.79 |
| 3| 6117 | 46.21 | 15.58 | 0.91 |
| 4| 6236 | 53.82 | 18.09 | 0.99 |
| 5| 6475 | 65.16 | 22.00 | 1.12 |
| 6| 6588 | 70.40 | 23.70 | 1.18 |
| 7| 6766 | 84.90 | 28.63 | 1.34 |
| 8| 6806 | 89.62 | 30.15 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1706 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 99.82 | 38.19 | 1.55 |

