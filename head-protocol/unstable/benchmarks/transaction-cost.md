--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-26 05:13:33.602673464 UTC |
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
| 1| 5836 | 10.35 | 3.28 | 0.51 |
| 2| 6041 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 751 | 42.73 | 12.29 | 0.62 |
| 4 | 227 | 862 | 50.36 | 14.48 | 0.70 |
| 5 | 284 | 969 | 64.11 | 18.19 | 0.84 |
| 6 | 338 | 1081 | 68.01 | 19.48 | 0.89 |
| 7 | 394 | 1192 | 78.73 | 22.52 | 1.00 |
| 8 | 449 | 1307 | 90.93 | 25.74 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.44 | 8.41 | 0.49 |
| 3| 2013 | 26.28 | 9.57 | 0.52 |
| 5| 2454 | 32.52 | 12.65 | 0.61 |
| 10| 3119 | 41.23 | 18.41 | 0.75 |
| 38| 7656 | 99.32 | 53.24 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 766 | 24.05 | 8.39 | 0.44 |
| 3| 872 | 25.12 | 9.33 | 0.46 |
| 5| 1176 | 29.65 | 11.95 | 0.53 |
| 10| 2030 | 40.32 | 18.26 | 0.70 |
| 41| 6473 | 95.79 | 54.33 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.13 | 8.90 | 0.48 |
| 2| 853 | 31.69 | 10.29 | 0.52 |
| 3| 910 | 32.80 | 11.25 | 0.54 |
| 5| 1226 | 36.95 | 13.76 | 0.60 |
| 10| 2003 | 47.32 | 20.01 | 0.76 |
| 36| 5968 | 98.16 | 51.67 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 861 | 36.56 | 11.60 | 0.57 |
| 3| 961 | 37.91 | 12.62 | 0.59 |
| 5| 1274 | 42.64 | 15.28 | 0.66 |
| 10| 2130 | 54.84 | 22.04 | 0.85 |
| 30| 4814 | 96.90 | 46.98 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.00 | 9.07 | 0.69 |
| 2| 5914 | 36.08 | 12.13 | 0.79 |
| 3| 6018 | 43.67 | 14.66 | 0.87 |
| 4| 6212 | 53.75 | 18.07 | 0.99 |
| 5| 6571 | 65.92 | 22.28 | 1.13 |
| 6| 6559 | 72.60 | 24.41 | 1.20 |
| 7| 6660 | 79.84 | 26.87 | 1.28 |
| 8| 6902 | 93.37 | 31.44 | 1.43 |
| 9| 6785 | 91.29 | 30.58 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.98 | 10.65 | 0.73 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

