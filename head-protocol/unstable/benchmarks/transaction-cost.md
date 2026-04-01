--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-01 07:11:41.930144605 UTC |
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
| 1| 5836 | 10.64 | 3.38 | 0.52 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.29 | 11.96 | 0.60 |
| 4 | 225 | 858 | 53.89 | 15.35 | 0.73 |
| 5 | 282 | 969 | 60.99 | 17.44 | 0.81 |
| 6 | 337 | 1085 | 68.19 | 19.64 | 0.89 |
| 7 | 395 | 1192 | 76.21 | 21.91 | 0.98 |
| 8 | 450 | 1303 | 91.75 | 25.99 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2055 | 27.32 | 9.86 | 0.53 |
| 5| 2382 | 31.48 | 12.36 | 0.60 |
| 10| 3171 | 40.77 | 18.30 | 0.75 |
| 40| 7739 | 99.61 | 54.69 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.84 | 7.38 | 0.42 |
| 2| 697 | 22.58 | 7.94 | 0.42 |
| 3| 941 | 27.03 | 9.89 | 0.48 |
| 5| 1093 | 27.07 | 11.21 | 0.50 |
| 10| 1909 | 37.80 | 17.53 | 0.67 |
| 43| 6661 | 98.71 | 56.47 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 29.17 | 8.91 | 0.48 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 974 | 33.47 | 11.46 | 0.55 |
| 5| 1185 | 36.34 | 13.57 | 0.59 |
| 10| 2023 | 47.51 | 20.07 | 0.77 |
| 37| 6081 | 97.93 | 52.24 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 882 | 36.60 | 11.61 | 0.57 |
| 3| 962 | 37.95 | 12.63 | 0.59 |
| 5| 1327 | 43.28 | 15.48 | 0.67 |
| 10| 2033 | 54.05 | 21.81 | 0.83 |
| 30| 4945 | 99.96 | 47.90 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5941 | 35.89 | 12.06 | 0.79 |
| 3| 6148 | 45.71 | 15.45 | 0.90 |
| 4| 6207 | 51.57 | 17.30 | 0.96 |
| 5| 6325 | 59.49 | 19.94 | 1.05 |
| 6| 6626 | 75.59 | 25.54 | 1.24 |
| 7| 6799 | 83.88 | 28.22 | 1.33 |
| 8| 6895 | 89.68 | 30.23 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2276 | 7193 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

