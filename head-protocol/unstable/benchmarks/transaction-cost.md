--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-08 04:37:38.988451205 UTC |
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
| 1| 5837 | 10.76 | 3.42 | 0.52 |
| 2| 6041 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 15.07 | 4.78 | 0.58 |
| 5| 6643 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 29.09 | 9.17 | 0.79 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.35 | 9.42 | 0.51 |
| 3 | 171 | 747 | 39.93 | 11.62 | 0.59 |
| 4 | 226 | 858 | 48.25 | 14.02 | 0.68 |
| 5 | 281 | 969 | 57.68 | 16.65 | 0.78 |
| 6 | 336 | 1081 | 64.65 | 18.79 | 0.86 |
| 7 | 396 | 1192 | 72.71 | 21.08 | 0.94 |
| 8 | 451 | 1307 | 91.64 | 26.01 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 24.00 | 7.62 | 0.48 |
| 2| 1933 | 25.80 | 8.77 | 0.51 |
| 3| 2055 | 27.02 | 9.79 | 0.53 |
| 5| 2388 | 31.05 | 12.25 | 0.59 |
| 10| 3035 | 38.78 | 17.74 | 0.73 |
| 40| 7601 | 97.36 | 54.03 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 22.81 | 7.37 | 0.42 |
| 2| 800 | 24.05 | 8.40 | 0.44 |
| 3| 825 | 24.13 | 9.04 | 0.45 |
| 5| 1186 | 29.18 | 11.80 | 0.52 |
| 10| 1970 | 38.04 | 17.61 | 0.67 |
| 39| 6407 | 98.44 | 53.75 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 29.13 | 8.90 | 0.48 |
| 2| 786 | 30.91 | 10.06 | 0.51 |
| 3| 969 | 30.87 | 10.74 | 0.52 |
| 5| 1238 | 37.06 | 13.78 | 0.60 |
| 10| 1926 | 46.58 | 19.79 | 0.75 |
| 37| 6083 | 99.41 | 52.63 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 937 | 37.95 | 12.63 | 0.59 |
| 5| 1226 | 41.97 | 15.07 | 0.65 |
| 10| 2130 | 55.10 | 22.12 | 0.85 |
| 29| 5059 | 99.83 | 47.26 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5800 | 27.13 | 9.11 | 0.69 |
| 2| 5937 | 36.07 | 12.11 | 0.79 |
| 3| 6083 | 44.93 | 15.08 | 0.89 |
| 4| 6294 | 55.20 | 18.60 | 1.01 |
| 5| 6383 | 60.43 | 20.29 | 1.07 |
| 6| 6513 | 69.89 | 23.51 | 1.17 |
| 7| 6749 | 81.21 | 27.33 | 1.30 |
| 8| 6663 | 84.31 | 28.28 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 20.08 | 6.82 | 0.62 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1706 | 6852 | 81.55 | 30.98 | 1.33 |
| 10 | 38 | 2163 | 7125 | 96.44 | 36.92 | 1.51 |

