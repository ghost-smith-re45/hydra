--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-12 07:47:53.534594063 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7648 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 168 | 747 | 40.17 | 11.66 | 0.59 |
| 4 | 226 | 858 | 53.82 | 15.31 | 0.73 |
| 5 | 281 | 969 | 63.04 | 17.94 | 0.83 |
| 6 | 339 | 1081 | 75.89 | 21.48 | 0.97 |
| 7 | 394 | 1192 | 87.26 | 24.65 | 1.09 |
| 8 | 452 | 1303 | 96.14 | 27.04 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.00 | 7.62 | 0.48 |
| 2| 1954 | 25.81 | 8.77 | 0.51 |
| 3| 2098 | 28.10 | 10.09 | 0.54 |
| 5| 2346 | 30.08 | 11.98 | 0.58 |
| 10| 3208 | 42.97 | 18.91 | 0.77 |
| 43| 7866 | 99.51 | 56.61 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.84 | 7.38 | 0.42 |
| 2| 755 | 23.65 | 8.25 | 0.43 |
| 3| 830 | 24.02 | 9.03 | 0.45 |
| 5| 1194 | 30.05 | 12.07 | 0.53 |
| 10| 1959 | 38.46 | 17.72 | 0.67 |
| 41| 6431 | 93.56 | 53.73 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.50 | 8.46 | 0.46 |
| 2| 737 | 30.19 | 9.84 | 0.50 |
| 3| 902 | 30.15 | 10.52 | 0.51 |
| 5| 1210 | 34.22 | 13.00 | 0.57 |
| 10| 2001 | 47.40 | 20.03 | 0.77 |
| 37| 6120 | 99.54 | 52.72 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 33.87 | 10.16 | 0.53 |
| 2| 866 | 36.64 | 11.62 | 0.57 |
| 3| 892 | 37.20 | 12.40 | 0.58 |
| 5| 1337 | 43.40 | 15.50 | 0.67 |
| 10| 2000 | 54.16 | 21.83 | 0.83 |
| 28| 4793 | 96.64 | 45.69 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.00 | 9.06 | 0.69 |
| 2| 5935 | 35.96 | 12.06 | 0.79 |
| 3| 6088 | 44.56 | 14.99 | 0.89 |
| 4| 6225 | 53.68 | 18.03 | 0.99 |
| 5| 6342 | 59.21 | 19.85 | 1.05 |
| 6| 6661 | 75.16 | 25.48 | 1.23 |
| 7| 6626 | 76.81 | 25.83 | 1.25 |
| 8| 6865 | 90.16 | 30.32 | 1.40 |
| 9| 6835 | 94.44 | 31.76 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.52 | 6.86 | 0.62 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 283 | 6002 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 39 | 2221 | 7161 | 98.93 | 37.88 | 1.54 |

