--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-12 07:12:13.089202207 UTC |
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
| 1| 5837 | 10.93 | 3.49 | 0.52 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6243 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 42.22 | 12.14 | 0.61 |
| 4 | 227 | 858 | 53.69 | 15.30 | 0.73 |
| 5 | 281 | 969 | 56.64 | 16.36 | 0.77 |
| 6 | 339 | 1081 | 65.96 | 19.06 | 0.87 |
| 7 | 395 | 1192 | 74.30 | 21.42 | 0.96 |
| 8 | 449 | 1303 | 92.99 | 26.49 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 1945 | 25.76 | 8.76 | 0.51 |
| 3| 2011 | 26.36 | 9.59 | 0.52 |
| 5| 2454 | 32.21 | 12.57 | 0.61 |
| 10| 3223 | 42.96 | 18.91 | 0.78 |
| 39| 7372 | 93.81 | 52.37 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.81 | 7.37 | 0.42 |
| 2| 755 | 24.32 | 8.46 | 0.44 |
| 3| 913 | 25.52 | 9.47 | 0.46 |
| 5| 1213 | 29.08 | 11.77 | 0.52 |
| 10| 1790 | 35.62 | 16.94 | 0.64 |
| 42| 6571 | 95.31 | 54.88 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 953 | 30.90 | 10.74 | 0.52 |
| 5| 1379 | 38.25 | 14.16 | 0.62 |
| 10| 2149 | 48.74 | 20.44 | 0.79 |
| 37| 6058 | 98.48 | 52.40 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.87 | 10.16 | 0.53 |
| 2| 821 | 35.85 | 11.38 | 0.56 |
| 3| 1003 | 38.63 | 12.83 | 0.60 |
| 5| 1246 | 42.61 | 15.27 | 0.66 |
| 10| 2049 | 54.06 | 21.81 | 0.83 |
| 28| 4838 | 97.41 | 45.90 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.08 | 9.09 | 0.69 |
| 2| 5960 | 35.88 | 12.04 | 0.79 |
| 3| 6111 | 45.49 | 15.36 | 0.90 |
| 4| 6153 | 50.61 | 16.94 | 0.95 |
| 5| 6481 | 64.48 | 21.75 | 1.11 |
| 6| 6597 | 75.77 | 25.57 | 1.24 |
| 7| 6730 | 80.69 | 27.17 | 1.29 |
| 8| 6873 | 93.41 | 31.54 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2164 | 7126 | 96.88 | 37.08 | 1.51 |

