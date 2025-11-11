--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-11 04:41:00.250914665 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6035 | 12.82 | 4.07 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 747 | 42.51 | 12.22 | 0.61 |
| 4 | 227 | 858 | 48.46 | 14.08 | 0.68 |
| 5 | 282 | 969 | 56.29 | 16.32 | 0.77 |
| 6 | 338 | 1081 | 64.57 | 18.74 | 0.85 |
| 7 | 394 | 1192 | 73.38 | 21.33 | 0.95 |
| 8 | 448 | 1303 | 81.08 | 23.54 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1825 | 24.29 | 7.69 | 0.48 |
| 2| 1922 | 25.39 | 8.67 | 0.50 |
| 3| 2151 | 27.94 | 10.05 | 0.54 |
| 5| 2359 | 31.37 | 12.33 | 0.60 |
| 10| 3158 | 41.82 | 18.59 | 0.76 |
| 40| 7546 | 97.65 | 54.10 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.81 | 7.37 | 0.42 |
| 2| 838 | 25.36 | 8.75 | 0.46 |
| 3| 981 | 26.57 | 9.76 | 0.48 |
| 5| 1199 | 29.19 | 11.80 | 0.52 |
| 10| 1966 | 38.74 | 17.80 | 0.68 |
| 39| 6427 | 97.99 | 53.65 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.54 | 8.47 | 0.46 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 989 | 33.43 | 11.44 | 0.55 |
| 5| 1240 | 36.91 | 13.75 | 0.60 |
| 10| 1937 | 46.58 | 19.79 | 0.75 |
| 34| 6038 | 97.44 | 50.24 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.15 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 966 | 37.80 | 12.59 | 0.59 |
| 5| 1257 | 42.72 | 15.30 | 0.66 |
| 10| 2161 | 55.60 | 22.27 | 0.86 |
| 30| 4904 | 99.11 | 47.65 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.09 | 9.08 | 0.69 |
| 2| 5917 | 34.87 | 11.67 | 0.78 |
| 3| 6112 | 44.81 | 15.04 | 0.89 |
| 4| 6378 | 56.25 | 19.00 | 1.02 |
| 5| 6434 | 63.84 | 21.49 | 1.10 |
| 6| 6515 | 73.18 | 24.67 | 1.21 |
| 7| 6627 | 81.96 | 27.58 | 1.30 |
| 8| 6776 | 88.49 | 29.72 | 1.38 |
| 9| 6840 | 97.01 | 32.53 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.08 | 6.83 | 0.62 |
| 10 | 10 | 568 | 6173 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1139 | 6514 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.22 | 30.52 | 1.32 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |

