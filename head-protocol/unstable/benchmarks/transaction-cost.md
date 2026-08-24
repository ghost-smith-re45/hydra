--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-24 06:02:22.929727873 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 168 | 747 | 43.70 | 12.54 | 0.63 |
| 4 | 228 | 858 | 49.87 | 14.44 | 0.70 |
| 5 | 282 | 969 | 55.87 | 16.21 | 0.76 |
| 6 | 337 | 1081 | 66.90 | 19.37 | 0.88 |
| 7 | 394 | 1192 | 82.82 | 23.54 | 1.04 |
| 8 | 448 | 1303 | 88.72 | 25.26 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1931 | 25.89 | 8.79 | 0.51 |
| 3| 2151 | 29.34 | 10.43 | 0.56 |
| 5| 2411 | 31.48 | 12.36 | 0.60 |
| 10| 3118 | 40.54 | 18.22 | 0.75 |
| 38| 7428 | 97.59 | 52.73 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.77 | 7.36 | 0.41 |
| 2| 823 | 25.56 | 8.79 | 0.46 |
| 3| 944 | 26.09 | 9.60 | 0.47 |
| 5| 1267 | 29.94 | 12.03 | 0.53 |
| 10| 1948 | 39.49 | 18.03 | 0.69 |
| 40| 6613 | 99.03 | 54.59 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 27.51 | 8.47 | 0.46 |
| 2| 825 | 31.66 | 10.29 | 0.52 |
| 3| 956 | 31.27 | 10.86 | 0.52 |
| 5| 1249 | 35.04 | 13.25 | 0.58 |
| 10| 1950 | 46.61 | 19.79 | 0.76 |
| 37| 5954 | 98.08 | 52.25 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.79 | 10.15 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 967 | 37.95 | 12.63 | 0.59 |
| 5| 1432 | 44.66 | 15.90 | 0.69 |
| 10| 1958 | 53.42 | 21.61 | 0.82 |
| 29| 4840 | 97.23 | 46.49 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.58 | 0.64 |
| 2| 5846 | 31.48 | 10.46 | 0.74 |
| 3| 6018 | 43.70 | 14.69 | 0.87 |
| 4| 6092 | 49.67 | 16.60 | 0.94 |
| 5| 6380 | 60.48 | 20.30 | 1.07 |
| 6| 6500 | 67.90 | 22.81 | 1.15 |
| 7| 6586 | 77.69 | 26.14 | 1.26 |
| 8| 6696 | 81.39 | 27.31 | 1.30 |
| 9| 6853 | 94.39 | 31.70 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.96 | 7.01 | 0.63 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1706 | 6852 | 81.11 | 30.83 | 1.33 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

