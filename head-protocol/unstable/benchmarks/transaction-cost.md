--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-25 04:42:20.032977053 UTC |
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
| 1| 5837 | 10.26 | 3.25 | 0.51 |
| 2| 6037 | 12.84 | 4.08 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 41.28 | 11.92 | 0.60 |
| 4 | 225 | 858 | 47.98 | 13.91 | 0.68 |
| 5 | 283 | 969 | 61.25 | 17.54 | 0.81 |
| 6 | 337 | 1081 | 64.00 | 18.55 | 0.85 |
| 7 | 393 | 1192 | 87.08 | 24.52 | 1.08 |
| 8 | 450 | 1303 | 93.99 | 26.62 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.37 | 7.71 | 0.48 |
| 2| 1940 | 25.84 | 8.78 | 0.51 |
| 3| 2124 | 28.39 | 10.16 | 0.55 |
| 5| 2369 | 31.29 | 12.31 | 0.60 |
| 10| 3209 | 41.64 | 18.55 | 0.76 |
| 39| 7627 | 99.04 | 53.84 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 638 | 22.50 | 7.30 | 0.41 |
| 2| 695 | 22.62 | 7.96 | 0.42 |
| 3| 940 | 26.68 | 9.79 | 0.48 |
| 5| 1197 | 29.77 | 11.97 | 0.53 |
| 10| 1885 | 36.37 | 17.14 | 0.65 |
| 43| 6866 | 99.17 | 56.62 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.09 | 8.89 | 0.48 |
| 2| 803 | 30.98 | 10.08 | 0.51 |
| 3| 925 | 32.75 | 11.24 | 0.54 |
| 5| 1231 | 36.95 | 13.76 | 0.60 |
| 10| 2080 | 45.54 | 19.57 | 0.75 |
| 35| 6075 | 98.25 | 51.07 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 933 | 37.91 | 12.62 | 0.59 |
| 5| 1280 | 42.68 | 15.29 | 0.66 |
| 10| 1959 | 53.42 | 21.61 | 0.82 |
| 29| 4743 | 96.58 | 46.26 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5824 | 27.08 | 9.08 | 0.69 |
| 2| 5954 | 35.83 | 12.04 | 0.79 |
| 3| 6061 | 44.79 | 15.05 | 0.89 |
| 4| 6118 | 48.88 | 16.36 | 0.93 |
| 5| 6307 | 60.81 | 20.41 | 1.07 |
| 6| 6573 | 74.53 | 25.13 | 1.22 |
| 7| 6694 | 83.90 | 28.23 | 1.33 |
| 8| 7000 | 94.86 | 32.08 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2221 | 7161 | 99.38 | 38.04 | 1.54 |

