--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-18 06:59:49.75005127 UTC |
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
| 1| 5836 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 13.08 | 4.16 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 42.37 | 12.20 | 0.61 |
| 4 | 226 | 858 | 47.96 | 13.90 | 0.68 |
| 5 | 282 | 969 | 59.90 | 17.25 | 0.80 |
| 6 | 340 | 1081 | 72.20 | 20.60 | 0.93 |
| 7 | 396 | 1192 | 80.61 | 22.97 | 1.02 |
| 8 | 449 | 1303 | 87.92 | 25.22 | 1.10 |
| 9 | 507 | 1414 | 90.19 | 25.95 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.37 | 7.71 | 0.48 |
| 2| 2001 | 26.84 | 9.06 | 0.52 |
| 3| 2122 | 28.47 | 10.18 | 0.55 |
| 5| 2505 | 33.02 | 12.81 | 0.62 |
| 10| 3273 | 43.21 | 18.98 | 0.78 |
| 41| 7773 | 99.86 | 55.36 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 22.81 | 7.38 | 0.42 |
| 2| 772 | 24.28 | 8.45 | 0.44 |
| 3| 943 | 26.84 | 9.83 | 0.48 |
| 5| 1217 | 29.91 | 12.02 | 0.53 |
| 10| 1944 | 39.77 | 18.11 | 0.69 |
| 40| 6579 | 99.39 | 54.69 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 844 | 31.66 | 10.29 | 0.52 |
| 3| 956 | 30.86 | 10.73 | 0.52 |
| 5| 1172 | 36.35 | 13.57 | 0.59 |
| 10| 2004 | 44.71 | 19.32 | 0.74 |
| 36| 5954 | 96.23 | 51.12 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.83 | 10.15 | 0.53 |
| 2| 800 | 35.89 | 11.39 | 0.56 |
| 3| 1015 | 38.55 | 12.81 | 0.60 |
| 5| 1272 | 42.72 | 15.30 | 0.66 |
| 10| 1967 | 53.75 | 21.71 | 0.83 |
| 30| 4906 | 99.66 | 47.79 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5936 | 35.96 | 12.07 | 0.79 |
| 3| 6086 | 42.52 | 14.27 | 0.86 |
| 4| 6314 | 52.23 | 17.60 | 0.98 |
| 5| 6468 | 63.12 | 21.30 | 1.10 |
| 6| 6509 | 71.88 | 24.21 | 1.19 |
| 7| 6606 | 81.55 | 27.39 | 1.30 |
| 8| 6965 | 94.47 | 31.90 | 1.45 |
| 9| 6957 | 97.89 | 32.89 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.49 | 37.73 | 1.53 |

