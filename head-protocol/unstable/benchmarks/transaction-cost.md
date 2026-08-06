--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-06 07:50:54.401467554 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.99 | 4.13 | 0.55 |
| 3| 6243 | 14.72 | 4.66 | 0.58 |
| 5| 6646 | 19.08 | 6.04 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 747 | 42.25 | 12.15 | 0.61 |
| 4 | 227 | 862 | 49.10 | 14.18 | 0.69 |
| 5 | 282 | 974 | 58.38 | 16.88 | 0.79 |
| 6 | 339 | 1081 | 73.37 | 20.84 | 0.94 |
| 7 | 396 | 1192 | 82.87 | 23.52 | 1.04 |
| 8 | 449 | 1307 | 80.30 | 23.25 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2172 | 29.42 | 10.45 | 0.56 |
| 5| 2445 | 32.46 | 12.65 | 0.61 |
| 10| 3155 | 42.15 | 18.67 | 0.76 |
| 42| 7772 | 96.73 | 55.21 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 786 | 24.32 | 8.46 | 0.44 |
| 3| 897 | 25.79 | 9.53 | 0.47 |
| 5| 1139 | 28.04 | 11.47 | 0.51 |
| 10| 2058 | 40.52 | 18.32 | 0.70 |
| 40| 6318 | 93.72 | 53.12 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.17 | 8.91 | 0.48 |
| 2| 776 | 30.94 | 10.07 | 0.51 |
| 3| 873 | 32.05 | 11.02 | 0.53 |
| 5| 1324 | 35.60 | 13.43 | 0.59 |
| 10| 2029 | 44.98 | 19.39 | 0.74 |
| 36| 5949 | 97.67 | 51.50 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 33.87 | 10.16 | 0.53 |
| 2| 825 | 35.88 | 11.39 | 0.56 |
| 3| 951 | 37.87 | 12.61 | 0.59 |
| 5| 1282 | 42.49 | 15.24 | 0.66 |
| 10| 2017 | 54.29 | 21.86 | 0.84 |
| 29| 5043 | 99.98 | 47.30 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.00 | 9.06 | 0.69 |
| 2| 5960 | 35.92 | 12.06 | 0.79 |
| 3| 6038 | 44.62 | 15.01 | 0.88 |
| 4| 6219 | 53.69 | 18.03 | 0.99 |
| 5| 6319 | 60.94 | 20.49 | 1.07 |
| 6| 6697 | 75.05 | 25.37 | 1.23 |
| 7| 6797 | 82.32 | 27.74 | 1.31 |
| 8| 6845 | 92.79 | 31.19 | 1.43 |
| 9| 6928 | 97.18 | 32.57 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7159 | 99.12 | 37.95 | 1.54 |

