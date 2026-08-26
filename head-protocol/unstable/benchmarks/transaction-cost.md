--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-26 05:58:08.40260577 UTC |
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
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 42.49 | 12.21 | 0.61 |
| 4 | 227 | 858 | 51.97 | 14.86 | 0.72 |
| 5 | 284 | 969 | 64.21 | 18.21 | 0.84 |
| 6 | 338 | 1081 | 75.15 | 21.26 | 0.96 |
| 7 | 395 | 1192 | 74.96 | 21.66 | 0.96 |
| 8 | 451 | 1307 | 92.69 | 26.37 | 1.15 |
| 9 | 504 | 1414 | 91.91 | 26.59 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.00 | 7.62 | 0.48 |
| 2| 1884 | 24.43 | 8.40 | 0.49 |
| 3| 2081 | 26.95 | 9.77 | 0.53 |
| 5| 2425 | 32.61 | 12.67 | 0.61 |
| 10| 3258 | 43.30 | 18.99 | 0.78 |
| 40| 7516 | 97.46 | 54.08 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.50 | 7.29 | 0.41 |
| 2| 829 | 25.53 | 8.79 | 0.46 |
| 3| 881 | 25.78 | 9.53 | 0.47 |
| 5| 1183 | 29.14 | 11.78 | 0.52 |
| 10| 1959 | 39.04 | 17.89 | 0.68 |
| 42| 6688 | 99.43 | 56.00 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.13 | 8.90 | 0.48 |
| 2| 821 | 29.22 | 9.61 | 0.49 |
| 3| 945 | 30.94 | 10.75 | 0.52 |
| 5| 1307 | 37.81 | 14.01 | 0.61 |
| 10| 1964 | 47.10 | 19.94 | 0.76 |
| 36| 5902 | 96.90 | 51.27 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.79 | 10.15 | 0.53 |
| 2| 818 | 35.85 | 11.38 | 0.56 |
| 3| 950 | 37.91 | 12.62 | 0.59 |
| 5| 1242 | 42.57 | 15.26 | 0.66 |
| 10| 1985 | 53.19 | 21.55 | 0.82 |
| 29| 4951 | 99.65 | 47.19 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.08 | 0.69 |
| 2| 5970 | 35.92 | 12.06 | 0.79 |
| 3| 6183 | 46.81 | 15.81 | 0.91 |
| 4| 6119 | 48.97 | 16.38 | 0.93 |
| 5| 6351 | 60.66 | 20.36 | 1.07 |
| 6| 6384 | 62.47 | 20.92 | 1.09 |
| 7| 6815 | 85.22 | 28.78 | 1.35 |
| 8| 6823 | 87.34 | 29.39 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.49 | 37.73 | 1.53 |

