--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-18 09:07:46.109960421 UTC |
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
| 1| 5836 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.97 | 4.75 | 0.58 |
| 5| 6641 | 18.90 | 5.97 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 169 | 747 | 43.79 | 12.56 | 0.63 |
| 4 | 227 | 858 | 53.95 | 15.39 | 0.73 |
| 5 | 282 | 969 | 64.76 | 18.38 | 0.85 |
| 6 | 339 | 1081 | 71.28 | 20.30 | 0.92 |
| 7 | 392 | 1192 | 86.41 | 24.32 | 1.08 |
| 8 | 448 | 1303 | 98.88 | 27.85 | 1.21 |
| 9 | 504 | 1414 | 89.78 | 26.08 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 22.93 | 7.32 | 0.47 |
| 2| 1991 | 27.00 | 9.10 | 0.52 |
| 3| 2060 | 27.06 | 9.80 | 0.53 |
| 5| 2393 | 31.41 | 12.34 | 0.60 |
| 10| 3205 | 41.90 | 18.61 | 0.76 |
| 40| 7657 | 98.30 | 54.31 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.57 | 7.32 | 0.41 |
| 2| 823 | 25.08 | 8.67 | 0.45 |
| 3| 1044 | 28.09 | 10.17 | 0.50 |
| 5| 1157 | 28.12 | 11.50 | 0.51 |
| 10| 2065 | 41.36 | 18.56 | 0.71 |
| 41| 6525 | 95.24 | 54.19 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 597 | 28.46 | 8.69 | 0.47 |
| 2| 802 | 30.91 | 10.06 | 0.51 |
| 3| 864 | 32.09 | 11.03 | 0.53 |
| 5| 1385 | 36.44 | 13.67 | 0.60 |
| 10| 2002 | 47.26 | 19.99 | 0.76 |
| 36| 6122 | 98.54 | 51.80 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 937 | 37.88 | 12.61 | 0.59 |
| 5| 1317 | 43.25 | 15.47 | 0.67 |
| 10| 1970 | 53.19 | 21.55 | 0.82 |
| 30| 4834 | 98.73 | 47.50 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.04 | 9.09 | 0.69 |
| 2| 5938 | 35.87 | 12.06 | 0.79 |
| 3| 5993 | 40.50 | 13.52 | 0.84 |
| 4| 6369 | 55.84 | 18.90 | 1.02 |
| 5| 6313 | 62.06 | 20.81 | 1.08 |
| 6| 6686 | 76.12 | 25.75 | 1.25 |
| 7| 6710 | 80.55 | 27.16 | 1.29 |
| 8| 7016 | 95.68 | 32.36 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 283 | 6002 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1706 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2222 | 7161 | 99.31 | 38.01 | 1.54 |

