--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-06 08:13:13.048472122 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 29.19 | 9.21 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 169 | 747 | 43.88 | 12.56 | 0.63 |
| 4 | 227 | 858 | 51.13 | 14.69 | 0.71 |
| 5 | 282 | 969 | 61.69 | 17.68 | 0.82 |
| 6 | 339 | 1081 | 65.94 | 18.98 | 0.87 |
| 7 | 395 | 1192 | 87.39 | 24.69 | 1.09 |
| 8 | 451 | 1303 | 90.12 | 25.70 | 1.12 |
| 9 | 504 | 1414 | 94.13 | 27.07 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 23.92 | 7.60 | 0.48 |
| 2| 1982 | 26.47 | 8.98 | 0.52 |
| 3| 2123 | 28.39 | 10.16 | 0.55 |
| 5| 2422 | 32.80 | 12.73 | 0.61 |
| 10| 3253 | 43.77 | 19.12 | 0.78 |
| 41| 7588 | 95.51 | 54.18 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 831 | 25.59 | 8.81 | 0.46 |
| 3| 829 | 24.02 | 9.01 | 0.45 |
| 5| 1206 | 29.82 | 11.99 | 0.53 |
| 10| 2147 | 42.45 | 18.85 | 0.72 |
| 42| 6700 | 98.15 | 55.66 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 29.17 | 8.91 | 0.48 |
| 2| 779 | 30.98 | 10.08 | 0.51 |
| 3| 995 | 31.58 | 10.95 | 0.53 |
| 5| 1339 | 35.68 | 13.45 | 0.59 |
| 10| 2077 | 45.80 | 19.63 | 0.75 |
| 36| 5945 | 98.61 | 51.78 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 33.15 | 9.95 | 0.52 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 964 | 37.91 | 12.62 | 0.59 |
| 5| 1208 | 42.01 | 15.08 | 0.65 |
| 10| 1965 | 53.20 | 21.55 | 0.82 |
| 29| 4871 | 98.45 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.13 | 9.09 | 0.69 |
| 2| 6019 | 37.05 | 12.50 | 0.80 |
| 3| 6065 | 43.55 | 14.61 | 0.87 |
| 4| 6254 | 54.73 | 18.46 | 1.00 |
| 5| 6565 | 66.27 | 22.46 | 1.14 |
| 6| 6616 | 70.05 | 23.57 | 1.18 |
| 7| 6851 | 85.96 | 29.13 | 1.36 |
| 8| 6636 | 89.92 | 30.16 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 571 | 6175 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1135 | 6509 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1708 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 99.38 | 38.04 | 1.54 |

