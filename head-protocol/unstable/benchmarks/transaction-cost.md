--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-03 09:50:40.516574001 UTC |
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
| 1| 5836 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 12.91 | 4.10 | 0.55 |
| 3| 6239 | 14.78 | 4.68 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.64 | 9.36 | 0.79 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 751 | 41.01 | 11.85 | 0.60 |
| 4 | 226 | 858 | 53.84 | 15.39 | 0.73 |
| 5 | 283 | 969 | 59.70 | 17.14 | 0.80 |
| 6 | 338 | 1085 | 65.95 | 18.99 | 0.87 |
| 7 | 394 | 1192 | 83.00 | 23.55 | 1.04 |
| 8 | 452 | 1303 | 91.68 | 25.98 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2082 | 27.02 | 9.79 | 0.53 |
| 5| 2445 | 32.33 | 12.60 | 0.61 |
| 10| 3208 | 42.46 | 18.76 | 0.77 |
| 39| 7502 | 96.19 | 53.06 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.77 | 7.36 | 0.42 |
| 2| 699 | 22.62 | 7.96 | 0.42 |
| 3| 928 | 26.82 | 9.84 | 0.48 |
| 5| 1287 | 31.01 | 12.34 | 0.55 |
| 10| 2087 | 40.05 | 18.19 | 0.70 |
| 40| 6585 | 97.10 | 54.05 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.09 | 8.89 | 0.48 |
| 2| 866 | 29.97 | 9.84 | 0.50 |
| 3| 941 | 32.75 | 11.24 | 0.54 |
| 5| 1357 | 38.45 | 14.21 | 0.62 |
| 10| 1957 | 44.11 | 19.13 | 0.73 |
| 37| 6059 | 98.67 | 52.45 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.12 | 9.94 | 0.52 |
| 2| 824 | 35.85 | 11.38 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1242 | 42.61 | 15.27 | 0.66 |
| 10| 2091 | 54.96 | 22.07 | 0.85 |
| 28| 4859 | 96.99 | 45.83 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.00 | 9.08 | 0.69 |
| 2| 6028 | 36.73 | 12.40 | 0.80 |
| 3| 6080 | 45.50 | 15.35 | 0.90 |
| 4| 6291 | 55.13 | 18.62 | 1.01 |
| 5| 6343 | 58.11 | 19.50 | 1.04 |
| 6| 6740 | 74.45 | 25.16 | 1.23 |
| 7| 6686 | 82.78 | 27.83 | 1.31 |
| 8| 6883 | 89.69 | 30.22 | 1.40 |
| 9| 6864 | 96.41 | 32.35 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 79.15 | 30.16 | 1.31 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2222 | 7162 | 98.05 | 37.58 | 1.53 |

