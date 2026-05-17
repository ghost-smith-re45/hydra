--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-17 07:56:45.864355015 UTC |
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
| 1| 5838 | 10.66 | 3.39 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.93 | 5.98 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 42.35 | 12.18 | 0.61 |
| 4 | 226 | 862 | 49.41 | 14.27 | 0.69 |
| 5 | 282 | 969 | 60.91 | 17.42 | 0.81 |
| 6 | 337 | 1081 | 75.59 | 21.37 | 0.96 |
| 7 | 396 | 1196 | 82.66 | 23.46 | 1.04 |
| 8 | 449 | 1307 | 88.31 | 25.32 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1822 | 24.29 | 7.69 | 0.48 |
| 2| 1982 | 26.87 | 9.07 | 0.52 |
| 3| 2197 | 29.17 | 10.39 | 0.56 |
| 5| 2472 | 32.99 | 12.80 | 0.62 |
| 10| 3181 | 41.16 | 18.41 | 0.76 |
| 38| 7391 | 96.74 | 52.50 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.50 | 7.29 | 0.41 |
| 2| 766 | 23.98 | 8.37 | 0.44 |
| 3| 888 | 25.78 | 9.55 | 0.47 |
| 5| 1169 | 28.54 | 11.62 | 0.52 |
| 10| 2047 | 41.23 | 18.49 | 0.71 |
| 43| 6787 | 99.46 | 56.71 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.51 | 8.47 | 0.46 |
| 2| 804 | 30.98 | 10.08 | 0.51 |
| 3| 914 | 32.68 | 11.22 | 0.54 |
| 5| 1283 | 35.00 | 13.24 | 0.58 |
| 10| 2158 | 46.17 | 19.76 | 0.76 |
| 34| 5645 | 96.94 | 49.87 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.16 | 0.53 |
| 2| 823 | 35.81 | 11.37 | 0.56 |
| 3| 1077 | 39.18 | 13.01 | 0.61 |
| 5| 1253 | 42.53 | 15.25 | 0.66 |
| 10| 2065 | 54.59 | 21.98 | 0.84 |
| 30| 4701 | 97.15 | 47.02 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 27.05 | 9.08 | 0.69 |
| 2| 5845 | 31.40 | 10.44 | 0.74 |
| 3| 6104 | 44.93 | 15.08 | 0.89 |
| 4| 6234 | 51.53 | 17.29 | 0.97 |
| 5| 6413 | 61.21 | 20.62 | 1.08 |
| 6| 6673 | 75.54 | 25.48 | 1.24 |
| 7| 6705 | 80.06 | 26.93 | 1.29 |
| 8| 6706 | 87.04 | 29.28 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 10 | 568 | 6172 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6511 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1702 | 6848 | 79.15 | 30.16 | 1.31 |
| 10 | 40 | 2276 | 7193 | 99.84 | 38.30 | 1.55 |
| 10 | 39 | 2222 | 7161 | 98.93 | 37.88 | 1.54 |

