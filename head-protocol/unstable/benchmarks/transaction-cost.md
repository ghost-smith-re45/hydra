--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-30 04:56:05.507803195 UTC |
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
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.48 | 4.58 | 0.57 |
| 5| 6641 | 18.52 | 5.84 | 0.63 |
| 10| 7647 | 29.40 | 9.28 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 40.25 | 11.69 | 0.59 |
| 4 | 227 | 858 | 53.76 | 15.32 | 0.73 |
| 5 | 281 | 969 | 64.61 | 18.37 | 0.85 |
| 6 | 337 | 1085 | 67.90 | 19.49 | 0.89 |
| 7 | 394 | 1196 | 87.78 | 24.83 | 1.09 |
| 8 | 450 | 1303 | 94.18 | 26.57 | 1.16 |
| 9 | 505 | 1418 | 94.13 | 27.12 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 2004 | 27.00 | 9.10 | 0.52 |
| 3| 2017 | 25.95 | 9.49 | 0.52 |
| 5| 2442 | 32.49 | 12.64 | 0.61 |
| 10| 3025 | 38.56 | 17.68 | 0.72 |
| 40| 7590 | 97.80 | 54.15 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 824 | 25.10 | 8.68 | 0.45 |
| 3| 919 | 25.02 | 9.30 | 0.46 |
| 5| 1208 | 29.10 | 11.79 | 0.52 |
| 10| 1974 | 38.76 | 17.80 | 0.68 |
| 39| 6544 | 96.82 | 53.31 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 806 | 30.90 | 10.06 | 0.51 |
| 3| 1085 | 32.25 | 11.16 | 0.54 |
| 5| 1334 | 38.45 | 14.21 | 0.62 |
| 10| 1976 | 47.36 | 20.02 | 0.76 |
| 34| 5977 | 97.47 | 50.23 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.87 | 10.16 | 0.53 |
| 2| 870 | 36.56 | 11.60 | 0.57 |
| 3| 953 | 37.95 | 12.63 | 0.59 |
| 5| 1281 | 42.61 | 15.27 | 0.66 |
| 10| 2026 | 54.03 | 21.80 | 0.83 |
| 29| 4782 | 96.88 | 46.35 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 27.16 | 9.10 | 0.69 |
| 2| 5941 | 35.92 | 12.05 | 0.79 |
| 3| 6093 | 45.90 | 15.48 | 0.90 |
| 4| 6143 | 52.93 | 17.76 | 0.98 |
| 5| 6288 | 59.88 | 20.09 | 1.06 |
| 6| 6445 | 69.50 | 23.35 | 1.16 |
| 7| 6628 | 79.60 | 26.83 | 1.28 |
| 8| 6767 | 88.52 | 29.78 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2219 | 7159 | 97.61 | 37.43 | 1.52 |

