--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-03 04:44:53.955662616 UTC |
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
| 1| 5834 | 11.02 | 3.52 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 99.08 | 30.97 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.46 | 12.22 | 0.61 |
| 4 | 227 | 858 | 51.15 | 14.70 | 0.71 |
| 5 | 282 | 969 | 59.52 | 17.09 | 0.80 |
| 6 | 339 | 1081 | 71.90 | 20.45 | 0.93 |
| 7 | 393 | 1192 | 72.87 | 21.16 | 0.94 |
| 8 | 449 | 1303 | 87.57 | 25.04 | 1.10 |
| 9 | 505 | 1414 | 89.20 | 25.88 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1995 | 26.42 | 8.96 | 0.52 |
| 3| 2057 | 27.40 | 9.88 | 0.53 |
| 5| 2459 | 32.60 | 12.67 | 0.61 |
| 10| 3087 | 39.75 | 18.01 | 0.74 |
| 40| 7467 | 95.63 | 53.53 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 22.81 | 7.37 | 0.42 |
| 2| 808 | 25.16 | 8.70 | 0.45 |
| 3| 941 | 27.00 | 9.87 | 0.48 |
| 5| 1327 | 32.06 | 12.62 | 0.56 |
| 10| 1991 | 38.51 | 17.74 | 0.68 |
| 43| 6815 | 97.12 | 56.06 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.50 | 8.46 | 0.46 |
| 2| 807 | 29.26 | 9.62 | 0.49 |
| 3| 945 | 30.98 | 10.76 | 0.52 |
| 5| 1242 | 37.06 | 13.79 | 0.60 |
| 10| 1994 | 47.51 | 20.08 | 0.77 |
| 37| 6198 | 99.98 | 52.87 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 819 | 35.85 | 11.38 | 0.56 |
| 3| 991 | 38.62 | 12.83 | 0.60 |
| 5| 1316 | 43.28 | 15.47 | 0.67 |
| 10| 1983 | 53.46 | 21.62 | 0.83 |
| 29| 4900 | 98.59 | 46.91 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.09 | 9.09 | 0.69 |
| 2| 6060 | 36.80 | 12.43 | 0.80 |
| 3| 6208 | 47.01 | 15.91 | 0.92 |
| 4| 6228 | 51.05 | 17.17 | 0.96 |
| 5| 6326 | 59.26 | 19.87 | 1.05 |
| 6| 6518 | 73.49 | 24.83 | 1.21 |
| 7| 6765 | 84.73 | 28.63 | 1.34 |
| 8| 6890 | 91.71 | 30.92 | 1.42 |
| 9| 6886 | 97.54 | 32.75 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 38 | 2161 | 7123 | 97.07 | 37.14 | 1.52 |

