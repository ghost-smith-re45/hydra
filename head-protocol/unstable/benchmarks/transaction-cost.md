--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-04 06:30:27.381785964 UTC |
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
| 1| 5838 | 10.61 | 3.37 | 0.52 |
| 2| 6041 | 12.82 | 4.07 | 0.55 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.33 | 9.66 | 0.52 |
| 3 | 170 | 751 | 41.00 | 11.85 | 0.60 |
| 4 | 227 | 862 | 49.87 | 14.41 | 0.70 |
| 5 | 283 | 969 | 55.93 | 16.23 | 0.76 |
| 6 | 337 | 1081 | 64.43 | 18.70 | 0.85 |
| 7 | 396 | 1192 | 80.82 | 23.02 | 1.02 |
| 8 | 448 | 1303 | 87.47 | 25.02 | 1.09 |
| 9 | 504 | 1414 | 92.96 | 26.67 | 1.16 |
| 10 | 560 | 1525 | 98.17 | 28.51 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 23.92 | 7.60 | 0.48 |
| 2| 1983 | 26.76 | 9.04 | 0.52 |
| 3| 2107 | 27.97 | 10.06 | 0.54 |
| 5| 2463 | 32.31 | 12.60 | 0.61 |
| 10| 3197 | 42.19 | 18.68 | 0.77 |
| 40| 7693 | 98.89 | 54.48 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.81 | 7.37 | 0.42 |
| 2| 747 | 24.35 | 8.48 | 0.44 |
| 3| 958 | 26.98 | 9.87 | 0.48 |
| 5| 1188 | 29.65 | 11.96 | 0.53 |
| 10| 2058 | 42.29 | 18.79 | 0.72 |
| 42| 6700 | 97.96 | 55.64 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 816 | 29.26 | 9.62 | 0.49 |
| 3| 1013 | 31.61 | 10.96 | 0.53 |
| 5| 1278 | 35.01 | 13.24 | 0.58 |
| 10| 1961 | 44.07 | 19.12 | 0.73 |
| 36| 5808 | 99.83 | 51.98 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 33.15 | 9.95 | 0.52 |
| 2| 769 | 35.17 | 11.17 | 0.55 |
| 3| 940 | 37.80 | 12.59 | 0.59 |
| 5| 1157 | 41.22 | 14.85 | 0.64 |
| 10| 2134 | 55.82 | 22.34 | 0.86 |
| 29| 4958 | 99.39 | 47.09 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 27.13 | 9.09 | 0.69 |
| 2| 6017 | 37.04 | 12.51 | 0.80 |
| 3| 6136 | 44.88 | 15.07 | 0.89 |
| 4| 6152 | 47.93 | 16.06 | 0.92 |
| 5| 6352 | 62.99 | 21.18 | 1.09 |
| 6| 6513 | 69.90 | 23.48 | 1.17 |
| 7| 6781 | 84.14 | 28.44 | 1.33 |
| 8| 6849 | 92.84 | 31.26 | 1.43 |
| 9| 7090 | 98.88 | 33.28 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.64 | 6.67 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1136 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.34 | 30.22 | 1.31 |
| 10 | 38 | 2164 | 7126 | 96.00 | 36.77 | 1.50 |

