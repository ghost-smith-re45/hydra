--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-06 05:31:51.925841521 UTC |
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
| 2| 6038 | 12.53 | 3.97 | 0.55 |
| 3| 6242 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.79 | 5.94 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 225 | 858 | 50.86 | 14.60 | 0.70 |
| 5 | 284 | 969 | 55.83 | 16.18 | 0.76 |
| 6 | 339 | 1081 | 71.78 | 20.46 | 0.93 |
| 7 | 395 | 1192 | 79.41 | 22.82 | 1.01 |
| 8 | 450 | 1303 | 87.65 | 25.11 | 1.10 |
| 9 | 504 | 1414 | 96.64 | 27.67 | 1.19 |
| 10 | 560 | 1525 | 98.85 | 28.53 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.00 | 7.62 | 0.48 |
| 2| 1947 | 25.84 | 8.78 | 0.51 |
| 3| 2095 | 27.94 | 10.05 | 0.54 |
| 5| 2388 | 31.12 | 12.27 | 0.60 |
| 10| 3148 | 40.43 | 18.21 | 0.75 |
| 40| 7578 | 96.18 | 53.74 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.80 | 7.37 | 0.42 |
| 2| 741 | 23.54 | 8.23 | 0.43 |
| 3| 912 | 26.90 | 9.85 | 0.48 |
| 5| 1313 | 31.56 | 12.48 | 0.55 |
| 10| 2041 | 41.40 | 18.54 | 0.71 |
| 40| 6484 | 95.64 | 53.63 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.51 | 8.47 | 0.46 |
| 2| 728 | 30.27 | 9.86 | 0.50 |
| 3| 1057 | 32.25 | 11.16 | 0.54 |
| 5| 1295 | 37.58 | 13.95 | 0.61 |
| 10| 1913 | 46.61 | 19.79 | 0.75 |
| 38| 6218 | 99.84 | 53.46 | 1.62 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.83 | 10.16 | 0.53 |
| 2| 874 | 36.60 | 11.61 | 0.57 |
| 3| 950 | 37.91 | 12.62 | 0.59 |
| 5| 1204 | 41.93 | 15.06 | 0.65 |
| 10| 2080 | 55.00 | 22.08 | 0.85 |
| 29| 4844 | 97.30 | 46.48 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.92 | 9.04 | 0.69 |
| 2| 5930 | 35.88 | 12.06 | 0.79 |
| 3| 6143 | 45.94 | 15.46 | 0.90 |
| 4| 6290 | 54.45 | 18.36 | 1.00 |
| 5| 6378 | 61.34 | 20.65 | 1.08 |
| 6| 6548 | 74.48 | 25.09 | 1.22 |
| 7| 6676 | 80.86 | 27.26 | 1.29 |
| 8| 6832 | 91.49 | 30.84 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1710 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2161 | 7124 | 97.77 | 37.38 | 1.52 |

