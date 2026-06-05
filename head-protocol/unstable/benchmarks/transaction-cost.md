--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-05 09:20:39.468884189 UTC |
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
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 39.81 | 11.57 | 0.59 |
| 4 | 227 | 862 | 53.79 | 15.35 | 0.73 |
| 5 | 283 | 969 | 64.11 | 18.19 | 0.84 |
| 6 | 340 | 1081 | 75.25 | 21.25 | 0.96 |
| 7 | 395 | 1192 | 86.23 | 24.31 | 1.07 |
| 8 | 450 | 1303 | 86.19 | 24.60 | 1.08 |
| 9 | 504 | 1414 | 94.24 | 27.09 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2087 | 26.94 | 9.77 | 0.53 |
| 5| 2275 | 29.42 | 11.78 | 0.57 |
| 10| 3180 | 41.11 | 18.38 | 0.75 |
| 40| 7720 | 99.47 | 54.60 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.54 | 7.30 | 0.41 |
| 2| 765 | 23.56 | 8.22 | 0.43 |
| 3| 969 | 26.14 | 9.61 | 0.47 |
| 5| 1381 | 33.39 | 12.98 | 0.57 |
| 10| 2096 | 42.29 | 18.79 | 0.72 |
| 39| 6310 | 95.11 | 52.79 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 27.54 | 8.47 | 0.46 |
| 2| 825 | 29.22 | 9.61 | 0.49 |
| 3| 910 | 32.76 | 11.24 | 0.54 |
| 5| 1320 | 35.98 | 13.54 | 0.60 |
| 10| 1920 | 46.92 | 19.87 | 0.76 |
| 36| 6110 | 98.80 | 51.86 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 833 | 36.64 | 11.62 | 0.57 |
| 3| 1011 | 38.59 | 12.82 | 0.60 |
| 5| 1378 | 43.92 | 15.67 | 0.68 |
| 10| 2055 | 54.51 | 21.94 | 0.84 |
| 30| 4887 | 99.20 | 47.69 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5893 | 34.87 | 11.66 | 0.78 |
| 3| 6046 | 41.28 | 13.81 | 0.85 |
| 4| 6274 | 51.34 | 17.28 | 0.97 |
| 5| 6421 | 61.58 | 20.70 | 1.08 |
| 6| 6528 | 73.25 | 24.63 | 1.21 |
| 7| 6681 | 83.86 | 28.24 | 1.33 |
| 8| 6927 | 93.19 | 31.38 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 10 | 568 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 39 | 2219 | 7159 | 99.38 | 38.04 | 1.54 |

