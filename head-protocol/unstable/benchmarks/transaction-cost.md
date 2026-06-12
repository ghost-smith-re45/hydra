--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-12 09:45:57.468750514 UTC |
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
| 1| 5840 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.31 | 9.25 | 0.79 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10084 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 751 | 43.79 | 12.52 | 0.63 |
| 4 | 228 | 858 | 53.67 | 15.28 | 0.73 |
| 5 | 283 | 969 | 60.81 | 17.40 | 0.81 |
| 6 | 338 | 1081 | 64.28 | 18.62 | 0.85 |
| 7 | 394 | 1192 | 83.71 | 23.85 | 1.05 |
| 8 | 452 | 1303 | 83.14 | 24.03 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1883 | 24.77 | 8.48 | 0.49 |
| 3| 2070 | 26.86 | 9.75 | 0.53 |
| 5| 2316 | 30.49 | 12.08 | 0.59 |
| 10| 3204 | 42.22 | 18.69 | 0.77 |
| 40| 7713 | 99.82 | 54.69 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.39 | 0.42 |
| 2| 722 | 22.56 | 7.94 | 0.42 |
| 3| 1011 | 28.23 | 10.22 | 0.50 |
| 5| 1180 | 29.11 | 11.79 | 0.52 |
| 10| 1900 | 38.52 | 17.75 | 0.67 |
| 39| 6570 | 98.00 | 53.62 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.50 | 8.46 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 940 | 32.72 | 11.23 | 0.54 |
| 5| 1223 | 37.13 | 13.80 | 0.60 |
| 10| 2037 | 48.23 | 20.28 | 0.78 |
| 37| 6085 | 98.75 | 52.47 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 874 | 36.60 | 11.61 | 0.57 |
| 3| 1018 | 38.59 | 12.82 | 0.60 |
| 5| 1208 | 42.01 | 15.08 | 0.65 |
| 10| 2061 | 53.98 | 21.79 | 0.83 |
| 30| 5002 | 99.73 | 47.86 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5798 | 27.09 | 9.10 | 0.69 |
| 2| 5912 | 36.04 | 12.10 | 0.79 |
| 3| 5945 | 40.28 | 13.44 | 0.83 |
| 4| 6282 | 54.73 | 18.44 | 1.00 |
| 5| 6313 | 56.78 | 19.03 | 1.02 |
| 6| 6664 | 75.15 | 25.36 | 1.23 |
| 7| 6732 | 80.41 | 27.13 | 1.29 |
| 8| 7009 | 95.53 | 32.37 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1703 | 6849 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2222 | 7161 | 98.93 | 37.88 | 1.54 |

