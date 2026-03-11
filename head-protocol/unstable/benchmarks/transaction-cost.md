--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-11 06:32:42.332113935 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.76 | 4.67 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7651 | 29.14 | 9.19 | 0.79 |
| 43| 14286 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 640 | 33.25 | 9.61 | 0.52 |
| 3 | 169 | 747 | 43.71 | 12.51 | 0.63 |
| 4 | 226 | 858 | 48.24 | 14.02 | 0.68 |
| 5 | 282 | 969 | 64.97 | 18.46 | 0.85 |
| 6 | 338 | 1081 | 64.65 | 18.79 | 0.86 |
| 7 | 396 | 1192 | 76.35 | 21.95 | 0.98 |
| 8 | 451 | 1303 | 83.30 | 24.06 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1877 | 24.77 | 8.48 | 0.49 |
| 3| 2106 | 28.31 | 10.14 | 0.54 |
| 5| 2449 | 32.15 | 12.56 | 0.61 |
| 10| 3343 | 43.61 | 19.10 | 0.79 |
| 41| 7733 | 99.02 | 55.17 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.84 | 7.37 | 0.41 |
| 2| 761 | 23.63 | 8.24 | 0.43 |
| 3| 912 | 25.14 | 9.33 | 0.46 |
| 5| 1245 | 31.03 | 12.33 | 0.54 |
| 10| 2131 | 41.84 | 18.68 | 0.72 |
| 43| 6855 | 99.98 | 56.87 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.13 | 8.90 | 0.48 |
| 2| 813 | 29.22 | 9.61 | 0.49 |
| 3| 902 | 30.15 | 10.52 | 0.51 |
| 5| 1295 | 37.69 | 13.98 | 0.61 |
| 10| 2040 | 48.26 | 20.28 | 0.78 |
| 37| 6126 | 99.96 | 52.85 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.87 | 10.16 | 0.53 |
| 2| 857 | 36.60 | 11.61 | 0.57 |
| 3| 969 | 37.88 | 12.61 | 0.59 |
| 5| 1242 | 42.60 | 15.27 | 0.66 |
| 10| 2086 | 54.76 | 22.02 | 0.84 |
| 29| 4964 | 99.08 | 47.02 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 27.08 | 9.09 | 0.69 |
| 2| 5891 | 34.87 | 11.65 | 0.78 |
| 3| 6041 | 43.64 | 14.63 | 0.87 |
| 4| 6134 | 50.36 | 16.93 | 0.95 |
| 5| 6351 | 60.95 | 20.49 | 1.07 |
| 6| 6699 | 75.16 | 25.47 | 1.24 |
| 7| 6626 | 74.85 | 25.14 | 1.23 |
| 8| 7036 | 92.58 | 31.31 | 1.43 |
| 9| 7093 | 98.00 | 33.09 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1709 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

