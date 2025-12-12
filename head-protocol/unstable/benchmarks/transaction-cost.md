--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-12 04:50:26.467953256 UTC |
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
| 1| 5836 | 10.26 | 3.25 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.69 | 4.65 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.31 | 9.25 | 0.79 |
| 43| 14279 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 42.49 | 12.21 | 0.61 |
| 4 | 226 | 858 | 53.92 | 15.36 | 0.73 |
| 5 | 283 | 969 | 59.44 | 17.10 | 0.80 |
| 6 | 339 | 1081 | 75.97 | 21.50 | 0.97 |
| 7 | 393 | 1192 | 73.56 | 21.19 | 0.95 |
| 8 | 449 | 1303 | 96.36 | 27.15 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1949 | 25.80 | 8.77 | 0.51 |
| 3| 2157 | 29.01 | 10.35 | 0.55 |
| 5| 2442 | 32.33 | 12.60 | 0.61 |
| 10| 3149 | 40.70 | 18.28 | 0.75 |
| 42| 7652 | 97.04 | 55.26 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 22.81 | 7.37 | 0.42 |
| 2| 700 | 22.62 | 7.97 | 0.42 |
| 3| 944 | 26.16 | 9.61 | 0.47 |
| 5| 1263 | 30.15 | 12.07 | 0.54 |
| 10| 2095 | 42.21 | 18.77 | 0.72 |
| 40| 6579 | 98.60 | 54.44 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.54 | 8.47 | 0.46 |
| 2| 890 | 29.97 | 9.84 | 0.50 |
| 3| 1085 | 32.36 | 11.19 | 0.54 |
| 5| 1311 | 35.72 | 13.46 | 0.59 |
| 10| 2177 | 49.59 | 20.69 | 0.80 |
| 35| 5813 | 95.47 | 50.20 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.83 | 10.15 | 0.53 |
| 2| 841 | 36.56 | 11.60 | 0.57 |
| 3| 938 | 37.88 | 12.61 | 0.59 |
| 5| 1271 | 42.65 | 15.28 | 0.66 |
| 10| 2032 | 53.91 | 21.77 | 0.83 |
| 30| 5026 | 99.87 | 47.89 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.09 | 9.08 | 0.69 |
| 2| 5820 | 31.56 | 10.49 | 0.74 |
| 3| 6210 | 46.49 | 15.75 | 0.91 |
| 4| 6209 | 50.36 | 16.87 | 0.95 |
| 5| 6300 | 56.97 | 19.10 | 1.03 |
| 6| 6619 | 74.92 | 25.25 | 1.23 |
| 7| 6637 | 81.93 | 27.52 | 1.30 |
| 8| 6962 | 94.21 | 31.76 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.26 | 6.78 | 0.62 |
| 10 | 1 | 57 | 5869 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2222 | 7162 | 98.93 | 37.88 | 1.54 |

