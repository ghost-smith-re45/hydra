--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-24 06:40:30.975956717 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 170 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 227 | 858 | 49.72 | 14.38 | 0.69 |
| 5 | 283 | 974 | 58.23 | 16.79 | 0.78 |
| 6 | 338 | 1081 | 67.14 | 19.27 | 0.88 |
| 7 | 394 | 1196 | 84.58 | 23.88 | 1.06 |
| 8 | 449 | 1303 | 90.55 | 25.86 | 1.13 |
| 9 | 505 | 1414 | 93.65 | 26.89 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.29 | 7.69 | 0.48 |
| 2| 1979 | 27.00 | 9.10 | 0.52 |
| 3| 2161 | 28.31 | 10.14 | 0.55 |
| 5| 2493 | 33.61 | 12.97 | 0.63 |
| 10| 3258 | 42.86 | 18.88 | 0.78 |
| 37| 6966 | 88.24 | 49.48 | 1.53 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.57 | 7.31 | 0.41 |
| 2| 792 | 24.32 | 8.46 | 0.44 |
| 3| 828 | 24.02 | 9.01 | 0.45 |
| 5| 1208 | 30.10 | 12.06 | 0.53 |
| 10| 1843 | 37.16 | 17.38 | 0.66 |
| 42| 6715 | 97.61 | 55.54 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 1015 | 31.65 | 10.97 | 0.53 |
| 5| 1315 | 35.68 | 13.45 | 0.59 |
| 10| 2046 | 48.19 | 20.27 | 0.78 |
| 36| 6001 | 97.63 | 51.51 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.15 | 0.53 |
| 2| 874 | 36.60 | 11.61 | 0.57 |
| 3| 892 | 37.16 | 12.39 | 0.58 |
| 5| 1356 | 43.98 | 15.69 | 0.68 |
| 10| 1995 | 54.06 | 21.81 | 0.83 |
| 29| 4834 | 97.54 | 46.54 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5842 | 27.00 | 9.07 | 0.69 |
| 2| 5920 | 35.95 | 12.10 | 0.79 |
| 3| 5971 | 40.36 | 13.47 | 0.84 |
| 4| 6158 | 51.89 | 17.42 | 0.97 |
| 5| 6287 | 59.57 | 19.94 | 1.05 |
| 6| 6511 | 73.05 | 24.58 | 1.20 |
| 7| 6770 | 84.32 | 28.44 | 1.33 |
| 8| 7038 | 95.32 | 32.24 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6511 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2164 | 7127 | 96.88 | 37.08 | 1.51 |

