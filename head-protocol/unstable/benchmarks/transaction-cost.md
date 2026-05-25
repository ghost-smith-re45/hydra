--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-25 09:31:08.836903665 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6042 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.40 | 4.55 | 0.57 |
| 5| 6638 | 18.93 | 5.98 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 751 | 43.84 | 12.56 | 0.63 |
| 4 | 228 | 858 | 54.04 | 15.41 | 0.74 |
| 5 | 280 | 974 | 59.26 | 17.03 | 0.79 |
| 6 | 340 | 1081 | 75.46 | 21.41 | 0.96 |
| 7 | 396 | 1192 | 74.98 | 21.63 | 0.96 |
| 8 | 451 | 1303 | 92.15 | 26.19 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.29 | 7.69 | 0.48 |
| 2| 1951 | 25.39 | 8.68 | 0.50 |
| 3| 2060 | 27.39 | 9.88 | 0.53 |
| 5| 2429 | 32.08 | 12.54 | 0.61 |
| 10| 3247 | 43.76 | 19.12 | 0.78 |
| 41| 7868 | 99.87 | 55.40 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.38 | 0.41 |
| 2| 701 | 22.62 | 7.95 | 0.42 |
| 3| 939 | 26.93 | 9.85 | 0.48 |
| 5| 1134 | 28.15 | 11.51 | 0.51 |
| 10| 2169 | 43.89 | 19.22 | 0.74 |
| 39| 6335 | 97.08 | 53.33 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 774 | 28.51 | 9.39 | 0.48 |
| 3| 1029 | 31.57 | 10.95 | 0.53 |
| 5| 1211 | 34.37 | 13.04 | 0.58 |
| 10| 1975 | 47.62 | 20.10 | 0.77 |
| 39| 6106 | 99.56 | 53.97 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 885 | 36.64 | 11.62 | 0.57 |
| 3| 1015 | 38.51 | 12.80 | 0.60 |
| 5| 1279 | 42.94 | 15.37 | 0.66 |
| 10| 2035 | 54.43 | 21.92 | 0.84 |
| 29| 4854 | 97.16 | 46.48 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.05 | 9.07 | 0.69 |
| 2| 5888 | 32.49 | 10.85 | 0.75 |
| 3| 6140 | 45.93 | 15.48 | 0.90 |
| 4| 6096 | 49.24 | 16.50 | 0.94 |
| 5| 6444 | 63.91 | 21.54 | 1.11 |
| 6| 6532 | 70.97 | 23.93 | 1.18 |
| 7| 6742 | 82.86 | 27.97 | 1.32 |
| 8| 6844 | 92.82 | 31.29 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 568 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6515 | 60.87 | 22.83 | 1.09 |
| 10 | 39 | 2221 | 7161 | 98.49 | 37.73 | 1.53 |

