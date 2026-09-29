--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-29 11:39:02.279554066 UTC |
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
| 1| 5834 | 10.35 | 3.28 | 0.51 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.19 | 6.08 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 43.63 | 12.50 | 0.63 |
| 4 | 228 | 858 | 54.03 | 15.41 | 0.74 |
| 5 | 282 | 969 | 64.07 | 18.15 | 0.84 |
| 6 | 339 | 1081 | 65.93 | 19.02 | 0.87 |
| 7 | 394 | 1192 | 74.18 | 21.34 | 0.96 |
| 8 | 448 | 1303 | 95.68 | 26.93 | 1.17 |
| 9 | 506 | 1414 | 99.15 | 28.32 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.00 | 7.62 | 0.48 |
| 2| 1880 | 24.43 | 8.40 | 0.49 |
| 3| 2149 | 29.30 | 10.42 | 0.56 |
| 5| 2455 | 33.18 | 12.85 | 0.62 |
| 10| 3224 | 42.04 | 18.64 | 0.77 |
| 42| 7821 | 98.76 | 55.76 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.77 | 7.36 | 0.42 |
| 2| 754 | 24.25 | 8.44 | 0.44 |
| 3| 902 | 25.16 | 9.33 | 0.46 |
| 5| 1184 | 28.16 | 11.51 | 0.51 |
| 10| 1922 | 39.57 | 18.04 | 0.68 |
| 43| 6793 | 97.74 | 56.23 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 29.13 | 8.90 | 0.48 |
| 2| 736 | 30.19 | 9.84 | 0.50 |
| 3| 898 | 30.23 | 10.54 | 0.51 |
| 5| 1234 | 37.09 | 13.79 | 0.60 |
| 10| 1914 | 46.70 | 19.82 | 0.75 |
| 36| 5820 | 99.89 | 52.04 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.79 | 10.15 | 0.53 |
| 2| 869 | 36.64 | 11.62 | 0.57 |
| 3| 941 | 37.88 | 12.61 | 0.59 |
| 5| 1303 | 43.43 | 15.51 | 0.67 |
| 10| 2044 | 53.98 | 21.79 | 0.83 |
| 29| 4849 | 96.87 | 46.39 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.13 | 9.09 | 0.69 |
| 2| 5988 | 37.01 | 12.49 | 0.80 |
| 3| 6116 | 44.52 | 14.99 | 0.89 |
| 4| 6304 | 56.49 | 19.05 | 1.02 |
| 5| 6565 | 65.85 | 22.24 | 1.13 |
| 6| 6588 | 70.40 | 23.69 | 1.18 |
| 7| 6871 | 84.91 | 28.67 | 1.35 |
| 8| 6820 | 88.71 | 29.82 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 283 | 6003 | 27.58 | 9.82 | 0.71 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1705 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

