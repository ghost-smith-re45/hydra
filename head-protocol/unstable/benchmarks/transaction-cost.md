--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-03 07:05:35.765307616 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6039 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.91 | 5.98 | 0.64 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14285 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 43.81 | 12.53 | 0.63 |
| 4 | 227 | 858 | 54.12 | 15.43 | 0.74 |
| 5 | 283 | 974 | 57.04 | 16.49 | 0.77 |
| 6 | 339 | 1081 | 67.68 | 19.47 | 0.89 |
| 7 | 394 | 1192 | 74.56 | 21.48 | 0.96 |
| 8 | 450 | 1303 | 81.42 | 23.62 | 1.04 |
| 9 | 504 | 1418 | 96.59 | 27.65 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1788 | 24.37 | 7.71 | 0.48 |
| 2| 1950 | 25.92 | 8.80 | 0.51 |
| 3| 2072 | 26.94 | 9.77 | 0.53 |
| 5| 2324 | 30.04 | 11.97 | 0.58 |
| 10| 3141 | 41.07 | 18.37 | 0.75 |
| 40| 7749 | 99.75 | 54.70 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.50 | 7.29 | 0.41 |
| 2| 792 | 23.56 | 8.22 | 0.43 |
| 3| 946 | 26.96 | 9.86 | 0.48 |
| 5| 1298 | 32.37 | 12.70 | 0.56 |
| 10| 2046 | 42.00 | 18.72 | 0.71 |
| 41| 6757 | 99.57 | 55.38 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.13 | 8.90 | 0.48 |
| 2| 880 | 29.90 | 9.82 | 0.50 |
| 3| 1056 | 34.15 | 11.66 | 0.56 |
| 5| 1299 | 35.04 | 13.25 | 0.59 |
| 10| 1930 | 45.83 | 19.56 | 0.75 |
| 36| 5841 | 97.92 | 51.59 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.16 | 0.53 |
| 2| 866 | 36.48 | 11.58 | 0.57 |
| 3| 1013 | 38.62 | 12.83 | 0.60 |
| 5| 1306 | 43.43 | 15.51 | 0.67 |
| 10| 2048 | 54.17 | 21.84 | 0.84 |
| 29| 4944 | 98.77 | 46.94 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 27.00 | 9.07 | 0.69 |
| 2| 5866 | 34.87 | 11.65 | 0.77 |
| 3| 6157 | 46.79 | 15.84 | 0.91 |
| 4| 6136 | 47.97 | 16.10 | 0.92 |
| 5| 6381 | 64.07 | 21.56 | 1.10 |
| 6| 6439 | 66.09 | 22.16 | 1.13 |
| 7| 6945 | 86.12 | 29.16 | 1.36 |
| 8| 6897 | 94.58 | 31.88 | 1.45 |
| 9| 6943 | 98.76 | 33.19 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6174 | 40.83 | 14.90 | 0.86 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1704 | 6850 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2222 | 7162 | 98.49 | 37.73 | 1.53 |

