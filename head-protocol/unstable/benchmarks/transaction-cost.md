--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-10 06:42:18.389138732 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6645 | 19.08 | 6.04 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10043 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 635 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 40.13 | 11.66 | 0.59 |
| 4 | 225 | 862 | 49.58 | 14.32 | 0.69 |
| 5 | 284 | 969 | 59.22 | 16.99 | 0.79 |
| 6 | 340 | 1085 | 67.83 | 19.44 | 0.89 |
| 7 | 395 | 1192 | 76.76 | 22.05 | 0.98 |
| 8 | 451 | 1303 | 82.33 | 23.68 | 1.04 |
| 9 | 507 | 1414 | 93.46 | 26.79 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.29 | 7.69 | 0.48 |
| 2| 1925 | 25.51 | 8.70 | 0.50 |
| 3| 2182 | 29.54 | 10.48 | 0.56 |
| 5| 2547 | 33.98 | 13.08 | 0.63 |
| 10| 2973 | 37.33 | 17.34 | 0.71 |
| 39| 7605 | 99.15 | 53.86 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 718 | 22.60 | 7.95 | 0.42 |
| 3| 895 | 25.10 | 9.32 | 0.46 |
| 5| 1260 | 31.17 | 12.36 | 0.55 |
| 10| 1973 | 39.60 | 18.05 | 0.69 |
| 40| 6365 | 94.57 | 53.30 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 920 | 32.75 | 11.24 | 0.54 |
| 5| 1296 | 37.73 | 13.99 | 0.61 |
| 10| 2048 | 47.95 | 20.21 | 0.77 |
| 36| 5954 | 95.71 | 50.98 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 872 | 36.60 | 11.61 | 0.57 |
| 3| 990 | 38.66 | 12.84 | 0.60 |
| 5| 1360 | 43.36 | 15.49 | 0.67 |
| 10| 2038 | 54.58 | 21.96 | 0.84 |
| 30| 4968 | 99.85 | 47.89 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5822 | 31.45 | 10.47 | 0.74 |
| 3| 6138 | 45.77 | 15.44 | 0.90 |
| 4| 6095 | 49.35 | 16.49 | 0.94 |
| 5| 6334 | 62.65 | 21.05 | 1.09 |
| 6| 6663 | 75.19 | 25.33 | 1.23 |
| 7| 6700 | 83.60 | 28.18 | 1.32 |
| 8| 6691 | 87.51 | 29.34 | 1.36 |
| 9| 7061 | 98.61 | 33.18 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 30 | 1706 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7158 | 99.56 | 38.10 | 1.54 |

