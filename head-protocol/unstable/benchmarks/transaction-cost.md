--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-24 07:19:16.606656207 UTC |
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
| 1| 5840 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.98 | 4.75 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7650 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 39.82 | 11.57 | 0.59 |
| 4 | 227 | 858 | 49.50 | 14.28 | 0.69 |
| 5 | 283 | 969 | 63.70 | 18.12 | 0.84 |
| 6 | 337 | 1081 | 67.84 | 19.55 | 0.89 |
| 7 | 393 | 1192 | 72.39 | 20.96 | 0.94 |
| 8 | 450 | 1307 | 98.48 | 27.65 | 1.20 |
| 9 | 504 | 1418 | 96.16 | 27.49 | 1.19 |
| 10 | 561 | 1525 | 98.45 | 28.58 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 23.30 | 7.40 | 0.47 |
| 2| 1922 | 25.84 | 8.78 | 0.51 |
| 3| 2127 | 28.47 | 10.18 | 0.55 |
| 5| 2318 | 29.96 | 11.95 | 0.58 |
| 10| 3333 | 43.49 | 19.07 | 0.79 |
| 39| 7514 | 96.89 | 53.25 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.54 | 7.30 | 0.41 |
| 2| 741 | 23.61 | 8.24 | 0.43 |
| 3| 968 | 26.13 | 9.61 | 0.47 |
| 5| 1152 | 28.69 | 11.69 | 0.52 |
| 10| 2060 | 40.58 | 18.34 | 0.70 |
| 39| 6300 | 95.20 | 52.84 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 27.54 | 8.47 | 0.46 |
| 2| 771 | 28.47 | 9.38 | 0.48 |
| 3| 1019 | 34.18 | 11.67 | 0.56 |
| 5| 1214 | 34.33 | 13.03 | 0.58 |
| 10| 2103 | 48.51 | 20.36 | 0.78 |
| 36| 5963 | 96.56 | 51.19 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 959 | 37.95 | 12.63 | 0.59 |
| 5| 1271 | 42.64 | 15.28 | 0.66 |
| 10| 2125 | 55.43 | 22.23 | 0.85 |
| 29| 4947 | 99.94 | 47.25 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 5924 | 36.04 | 12.12 | 0.79 |
| 3| 5969 | 40.28 | 13.42 | 0.84 |
| 4| 6230 | 54.78 | 18.46 | 1.00 |
| 5| 6379 | 63.37 | 21.27 | 1.10 |
| 6| 6500 | 69.84 | 23.48 | 1.17 |
| 7| 6841 | 84.69 | 28.54 | 1.34 |
| 8| 7002 | 96.07 | 32.48 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.52 | 6.86 | 0.62 |
| 10 | 1 | 56 | 5867 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 40 | 2274 | 7190 | 99.66 | 38.24 | 1.55 |
| 10 | 37 | 2105 | 7090 | 94.83 | 36.27 | 1.49 |

