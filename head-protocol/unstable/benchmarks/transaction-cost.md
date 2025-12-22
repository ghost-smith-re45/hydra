--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-22 04:55:56.128064839 UTC |
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
| 2| 6041 | 12.54 | 3.97 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 169 | 747 | 42.45 | 12.22 | 0.61 |
| 4 | 228 | 862 | 54.04 | 15.41 | 0.74 |
| 5 | 282 | 969 | 56.34 | 16.33 | 0.77 |
| 6 | 339 | 1085 | 65.86 | 19.00 | 0.87 |
| 7 | 394 | 1192 | 82.76 | 23.45 | 1.04 |
| 8 | 448 | 1303 | 94.27 | 26.69 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1925 | 25.51 | 8.70 | 0.50 |
| 3| 2013 | 25.87 | 9.47 | 0.52 |
| 5| 2393 | 31.64 | 12.41 | 0.60 |
| 10| 3223 | 42.22 | 18.69 | 0.77 |
| 41| 7666 | 97.82 | 54.84 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 750 | 24.27 | 8.44 | 0.44 |
| 3| 875 | 25.05 | 9.32 | 0.46 |
| 5| 1288 | 31.31 | 12.40 | 0.55 |
| 10| 2052 | 39.81 | 18.10 | 0.69 |
| 40| 6441 | 97.67 | 54.18 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 27.54 | 8.47 | 0.46 |
| 2| 791 | 30.91 | 10.06 | 0.51 |
| 3| 976 | 30.90 | 10.74 | 0.52 |
| 5| 1301 | 37.81 | 14.01 | 0.61 |
| 10| 2105 | 48.90 | 20.48 | 0.79 |
| 37| 5980 | 96.84 | 51.94 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.87 | 10.16 | 0.53 |
| 2| 814 | 35.89 | 11.39 | 0.56 |
| 3| 934 | 37.87 | 12.61 | 0.59 |
| 5| 1245 | 42.65 | 15.28 | 0.66 |
| 10| 1896 | 52.63 | 21.37 | 0.81 |
| 29| 4929 | 99.54 | 47.15 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.00 | 9.06 | 0.69 |
| 2| 5892 | 34.87 | 11.67 | 0.78 |
| 3| 6014 | 41.39 | 13.87 | 0.85 |
| 4| 6277 | 54.96 | 18.53 | 1.00 |
| 5| 6426 | 64.31 | 21.74 | 1.11 |
| 6| 6563 | 71.69 | 24.15 | 1.19 |
| 7| 6622 | 81.87 | 27.53 | 1.30 |
| 8| 6827 | 92.21 | 31.00 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2222 | 7161 | 99.38 | 38.04 | 1.54 |

