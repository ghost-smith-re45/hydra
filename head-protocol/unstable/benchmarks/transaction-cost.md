--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-15 04:56:34.089952321 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6041 | 12.41 | 3.92 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 28.88 | 9.10 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 751 | 44.10 | 12.66 | 0.63 |
| 4 | 228 | 862 | 49.65 | 14.34 | 0.69 |
| 5 | 282 | 974 | 56.32 | 16.36 | 0.77 |
| 6 | 338 | 1081 | 72.81 | 20.62 | 0.93 |
| 7 | 395 | 1192 | 78.61 | 22.45 | 1.00 |
| 8 | 449 | 1303 | 96.23 | 27.11 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.37 | 7.71 | 0.48 |
| 2| 1947 | 25.89 | 8.79 | 0.51 |
| 3| 2060 | 27.39 | 9.88 | 0.53 |
| 5| 2394 | 31.03 | 12.25 | 0.59 |
| 10| 3170 | 40.55 | 18.24 | 0.75 |
| 41| 7731 | 98.96 | 55.15 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.57 | 7.31 | 0.41 |
| 2| 697 | 22.62 | 7.95 | 0.42 |
| 3| 975 | 27.83 | 10.10 | 0.49 |
| 5| 1328 | 32.34 | 12.70 | 0.56 |
| 10| 1956 | 38.07 | 17.66 | 0.67 |
| 38| 6123 | 91.05 | 51.01 | 1.52 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.13 | 8.90 | 0.48 |
| 2| 816 | 29.26 | 9.62 | 0.49 |
| 3| 1063 | 32.40 | 11.20 | 0.54 |
| 5| 1243 | 37.02 | 13.78 | 0.60 |
| 10| 2199 | 47.18 | 20.05 | 0.77 |
| 35| 5903 | 95.84 | 50.33 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.89 | 11.39 | 0.56 |
| 3| 896 | 37.13 | 12.38 | 0.58 |
| 5| 1229 | 41.97 | 15.07 | 0.65 |
| 10| 1851 | 52.00 | 21.18 | 0.80 |
| 29| 4897 | 98.37 | 46.82 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.08 | 9.08 | 0.69 |
| 2| 5979 | 37.01 | 12.48 | 0.80 |
| 3| 6039 | 44.05 | 14.77 | 0.88 |
| 4| 6338 | 56.09 | 18.94 | 1.02 |
| 5| 6263 | 59.69 | 20.01 | 1.05 |
| 6| 6522 | 69.96 | 23.57 | 1.17 |
| 7| 6689 | 80.71 | 27.15 | 1.29 |
| 8| 6729 | 85.28 | 28.67 | 1.34 |
| 9| 6998 | 98.32 | 33.08 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2223 | 7162 | 98.93 | 37.88 | 1.54 |

