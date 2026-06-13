--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-13 09:02:52.841639384 UTC |
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
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.76 | 4.67 | 0.58 |
| 5| 6645 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 29.30 | 9.24 | 0.79 |
| 43| 14281 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10079 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 747 | 43.84 | 12.55 | 0.63 |
| 4 | 226 | 858 | 48.03 | 13.92 | 0.68 |
| 5 | 285 | 969 | 62.57 | 17.82 | 0.83 |
| 6 | 340 | 1081 | 75.27 | 21.26 | 0.96 |
| 7 | 394 | 1192 | 83.79 | 23.68 | 1.05 |
| 8 | 449 | 1303 | 84.83 | 24.33 | 1.07 |
| 9 | 506 | 1414 | 97.58 | 28.07 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1824 | 24.00 | 7.62 | 0.48 |
| 2| 2005 | 26.55 | 9.00 | 0.52 |
| 3| 2055 | 27.35 | 9.87 | 0.53 |
| 5| 2443 | 32.29 | 12.61 | 0.61 |
| 10| 3028 | 38.52 | 17.67 | 0.72 |
| 41| 7635 | 98.38 | 54.97 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 22.81 | 7.37 | 0.42 |
| 2| 718 | 22.56 | 7.94 | 0.42 |
| 3| 871 | 25.12 | 9.32 | 0.46 |
| 5| 1120 | 27.12 | 11.22 | 0.50 |
| 10| 2146 | 40.84 | 18.39 | 0.71 |
| 43| 6671 | 99.09 | 56.56 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 27.50 | 8.46 | 0.46 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 903 | 30.15 | 10.52 | 0.51 |
| 5| 1329 | 35.68 | 13.45 | 0.59 |
| 10| 1966 | 46.61 | 19.80 | 0.76 |
| 36| 5964 | 98.04 | 51.60 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 1023 | 38.55 | 12.81 | 0.60 |
| 5| 1274 | 42.72 | 15.30 | 0.66 |
| 10| 2206 | 55.77 | 22.35 | 0.86 |
| 29| 4960 | 98.69 | 46.92 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.00 | 9.07 | 0.69 |
| 2| 5987 | 36.93 | 12.45 | 0.80 |
| 3| 6102 | 44.80 | 15.07 | 0.89 |
| 4| 6340 | 55.83 | 18.83 | 1.02 |
| 5| 6474 | 66.08 | 22.34 | 1.13 |
| 6| 6522 | 69.47 | 23.33 | 1.17 |
| 7| 6994 | 86.24 | 29.20 | 1.37 |
| 8| 6710 | 84.93 | 28.53 | 1.34 |
| 9| 6940 | 96.92 | 32.69 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 10 | 570 | 6175 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6514 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |

