--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-21 06:29:39.978660357 UTC |
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
| 1| 5834 | 10.28 | 3.25 | 0.51 |
| 2| 6039 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 19.00 | 6.01 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 751 | 42.85 | 12.34 | 0.62 |
| 4 | 226 | 858 | 48.07 | 13.96 | 0.68 |
| 5 | 283 | 969 | 62.91 | 17.94 | 0.83 |
| 6 | 340 | 1081 | 71.36 | 20.32 | 0.92 |
| 7 | 395 | 1196 | 74.92 | 21.66 | 0.96 |
| 8 | 450 | 1303 | 84.86 | 24.34 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.37 | 7.71 | 0.48 |
| 2| 1932 | 25.85 | 8.78 | 0.51 |
| 3| 2139 | 27.94 | 10.05 | 0.54 |
| 5| 2384 | 31.45 | 12.35 | 0.60 |
| 10| 3233 | 43.34 | 19.00 | 0.78 |
| 40| 7596 | 98.15 | 54.28 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.38 | 0.41 |
| 2| 701 | 22.55 | 7.93 | 0.42 |
| 3| 946 | 26.87 | 9.85 | 0.48 |
| 5| 1254 | 31.19 | 12.37 | 0.55 |
| 10| 1988 | 38.62 | 17.77 | 0.68 |
| 42| 6639 | 96.03 | 55.09 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.13 | 8.90 | 0.48 |
| 2| 776 | 30.94 | 10.07 | 0.51 |
| 3| 906 | 32.69 | 11.22 | 0.54 |
| 5| 1311 | 35.72 | 13.46 | 0.59 |
| 10| 2118 | 46.27 | 19.79 | 0.76 |
| 37| 5882 | 96.07 | 51.65 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 841 | 35.92 | 11.40 | 0.56 |
| 3| 976 | 38.63 | 12.83 | 0.60 |
| 5| 1202 | 41.89 | 15.05 | 0.65 |
| 10| 1969 | 53.23 | 21.56 | 0.82 |
| 29| 4934 | 98.89 | 46.97 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.09 | 9.08 | 0.69 |
| 2| 5930 | 36.07 | 12.14 | 0.79 |
| 3| 6086 | 45.07 | 15.16 | 0.89 |
| 4| 6221 | 53.36 | 17.96 | 0.98 |
| 5| 6271 | 57.40 | 19.20 | 1.03 |
| 6| 6519 | 73.48 | 24.67 | 1.21 |
| 7| 6606 | 76.71 | 25.78 | 1.25 |
| 8| 6908 | 93.61 | 31.56 | 1.44 |
| 9| 6815 | 90.61 | 30.44 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 5 | 285 | 6004 | 30.67 | 10.88 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.47 | 22.36 | 1.08 |
| 10 | 39 | 2224 | 7163 | 99.12 | 37.95 | 1.54 |

