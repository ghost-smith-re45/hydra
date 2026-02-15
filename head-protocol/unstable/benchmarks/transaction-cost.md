--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-15 06:15:38.101039879 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.84 | 4.08 | 0.55 |
| 3| 6238 | 15.07 | 4.78 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14285 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2161 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 42.33 | 12.19 | 0.61 |
| 4 | 226 | 858 | 49.57 | 14.34 | 0.69 |
| 5 | 283 | 969 | 62.66 | 17.84 | 0.83 |
| 6 | 338 | 1081 | 70.11 | 20.06 | 0.91 |
| 7 | 393 | 1192 | 84.55 | 23.87 | 1.06 |
| 8 | 451 | 1303 | 90.14 | 25.80 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.76 | 8.76 | 0.51 |
| 3| 2067 | 26.94 | 9.77 | 0.53 |
| 5| 2371 | 31.46 | 12.35 | 0.60 |
| 10| 3327 | 44.16 | 19.23 | 0.79 |
| 39| 7501 | 95.49 | 52.81 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 785 | 25.35 | 8.75 | 0.45 |
| 3| 897 | 25.07 | 9.31 | 0.46 |
| 5| 1377 | 33.14 | 12.92 | 0.57 |
| 10| 2211 | 41.64 | 18.62 | 0.72 |
| 43| 6831 | 99.61 | 56.78 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 29.13 | 8.90 | 0.48 |
| 2| 886 | 29.97 | 9.84 | 0.50 |
| 3| 921 | 32.68 | 11.22 | 0.54 |
| 5| 1302 | 37.66 | 13.97 | 0.61 |
| 10| 2060 | 45.46 | 19.54 | 0.75 |
| 35| 5795 | 95.26 | 50.17 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 824 | 35.92 | 11.40 | 0.56 |
| 3| 969 | 37.91 | 12.62 | 0.59 |
| 5| 1372 | 43.99 | 15.69 | 0.68 |
| 10| 1966 | 53.42 | 21.61 | 0.82 |
| 30| 4884 | 99.00 | 47.62 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 27.12 | 9.10 | 0.69 |
| 2| 6041 | 36.97 | 12.46 | 0.80 |
| 3| 6035 | 44.87 | 15.07 | 0.89 |
| 4| 6317 | 55.20 | 18.59 | 1.01 |
| 5| 6431 | 61.29 | 20.65 | 1.08 |
| 6| 6681 | 76.71 | 25.93 | 1.25 |
| 7| 6514 | 76.66 | 25.64 | 1.24 |
| 8| 7037 | 95.73 | 32.38 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 286 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2222 | 7161 | 98.05 | 37.58 | 1.53 |

