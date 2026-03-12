--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-12 06:31:14.54216149 UTC |
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
| 1| 5837 | 10.78 | 3.43 | 0.52 |
| 2| 6035 | 12.70 | 4.03 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.40 | 9.28 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.31 | 9.40 | 0.51 |
| 3 | 169 | 747 | 42.34 | 12.19 | 0.61 |
| 4 | 228 | 858 | 53.86 | 15.34 | 0.73 |
| 5 | 283 | 969 | 56.32 | 16.35 | 0.77 |
| 6 | 337 | 1081 | 73.36 | 20.80 | 0.94 |
| 7 | 394 | 1192 | 82.93 | 23.53 | 1.04 |
| 8 | 448 | 1303 | 98.44 | 27.64 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 23.92 | 7.60 | 0.48 |
| 2| 1953 | 25.76 | 8.76 | 0.51 |
| 3| 2056 | 27.39 | 9.88 | 0.53 |
| 5| 2398 | 31.52 | 12.37 | 0.60 |
| 10| 3164 | 41.08 | 18.37 | 0.75 |
| 40| 7783 | 98.86 | 54.47 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.84 | 7.39 | 0.41 |
| 2| 764 | 23.59 | 8.23 | 0.43 |
| 3| 948 | 27.04 | 9.88 | 0.48 |
| 5| 1254 | 31.01 | 12.33 | 0.54 |
| 10| 1890 | 37.35 | 17.43 | 0.66 |
| 39| 6441 | 95.93 | 53.08 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 946 | 30.94 | 10.75 | 0.52 |
| 5| 1176 | 36.24 | 13.54 | 0.59 |
| 10| 2279 | 47.52 | 20.17 | 0.78 |
| 38| 6084 | 99.74 | 53.37 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 832 | 35.85 | 11.38 | 0.56 |
| 3| 1014 | 38.55 | 12.81 | 0.60 |
| 5| 1400 | 44.11 | 15.72 | 0.68 |
| 10| 2025 | 53.99 | 21.79 | 0.83 |
| 30| 4976 | 99.69 | 47.85 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 26.97 | 9.05 | 0.69 |
| 2| 5892 | 34.87 | 11.67 | 0.78 |
| 3| 5991 | 41.48 | 13.89 | 0.85 |
| 4| 6279 | 55.03 | 18.53 | 1.00 |
| 5| 6457 | 63.73 | 21.51 | 1.10 |
| 6| 6734 | 75.75 | 25.66 | 1.24 |
| 7| 6752 | 83.73 | 28.19 | 1.33 |
| 8| 6634 | 79.74 | 26.65 | 1.28 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 284 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7158 | 97.61 | 37.43 | 1.52 |

