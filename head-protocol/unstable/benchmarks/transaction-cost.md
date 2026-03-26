--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-26 07:02:24.672118337 UTC |
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
| 1| 5841 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6645 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 171 | 747 | 42.46 | 12.22 | 0.61 |
| 4 | 227 | 862 | 50.97 | 14.63 | 0.71 |
| 5 | 283 | 969 | 64.56 | 18.30 | 0.85 |
| 6 | 337 | 1085 | 71.37 | 20.36 | 0.92 |
| 7 | 394 | 1196 | 78.34 | 22.38 | 1.00 |
| 8 | 452 | 1303 | 94.37 | 26.72 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.93 | 7.32 | 0.47 |
| 2| 1922 | 25.85 | 8.78 | 0.51 |
| 3| 2099 | 28.10 | 10.09 | 0.54 |
| 5| 2315 | 30.41 | 12.06 | 0.58 |
| 10| 3211 | 42.97 | 18.91 | 0.78 |
| 40| 7653 | 97.18 | 54.00 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 603 | 22.84 | 7.37 | 0.41 |
| 2| 766 | 24.25 | 8.44 | 0.44 |
| 3| 893 | 25.13 | 9.34 | 0.46 |
| 5| 1264 | 29.92 | 12.01 | 0.53 |
| 10| 2026 | 40.90 | 18.41 | 0.70 |
| 44| 6839 | 99.71 | 57.40 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 982 | 33.47 | 11.46 | 0.55 |
| 5| 1176 | 36.24 | 13.54 | 0.59 |
| 10| 2153 | 49.66 | 20.71 | 0.80 |
| 34| 5734 | 99.29 | 50.59 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 803 | 35.89 | 11.39 | 0.56 |
| 3| 999 | 38.58 | 12.82 | 0.60 |
| 5| 1260 | 42.72 | 15.30 | 0.66 |
| 10| 1981 | 53.39 | 21.60 | 0.82 |
| 29| 5003 | 99.23 | 47.09 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 27.13 | 9.10 | 0.69 |
| 2| 5999 | 37.09 | 12.50 | 0.80 |
| 3| 5968 | 40.43 | 13.48 | 0.84 |
| 4| 6232 | 51.35 | 17.25 | 0.96 |
| 5| 6488 | 65.01 | 21.93 | 1.12 |
| 6| 6533 | 71.85 | 24.18 | 1.19 |
| 7| 6626 | 79.10 | 26.50 | 1.27 |
| 8| 6814 | 92.66 | 31.24 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 37 | 2107 | 7092 | 95.02 | 36.33 | 1.49 |

