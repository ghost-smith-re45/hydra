--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-01 10:23:15.837159107 UTC |
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
| 1| 5837 | 10.69 | 3.40 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 19.34 | 6.13 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 169 | 747 | 41.11 | 11.90 | 0.60 |
| 4 | 226 | 858 | 51.30 | 14.76 | 0.71 |
| 5 | 284 | 969 | 62.78 | 17.87 | 0.83 |
| 6 | 337 | 1081 | 69.94 | 20.02 | 0.91 |
| 7 | 394 | 1192 | 78.80 | 22.54 | 1.00 |
| 8 | 450 | 1303 | 83.93 | 24.27 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1750 | 22.93 | 7.32 | 0.47 |
| 2| 1953 | 25.92 | 8.80 | 0.51 |
| 3| 2101 | 27.93 | 10.05 | 0.54 |
| 5| 2443 | 32.44 | 12.63 | 0.61 |
| 10| 3177 | 41.81 | 18.59 | 0.76 |
| 38| 7459 | 96.95 | 52.57 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.80 | 7.37 | 0.41 |
| 2| 757 | 24.35 | 8.47 | 0.44 |
| 3| 999 | 27.00 | 9.88 | 0.48 |
| 5| 1223 | 29.08 | 11.77 | 0.52 |
| 10| 2033 | 39.43 | 18.00 | 0.69 |
| 41| 6602 | 98.47 | 55.06 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.47 | 8.46 | 0.46 |
| 2| 884 | 29.90 | 9.82 | 0.50 |
| 3| 957 | 30.87 | 10.74 | 0.52 |
| 5| 1273 | 35.12 | 13.27 | 0.59 |
| 10| 1924 | 46.69 | 19.81 | 0.76 |
| 36| 5840 | 95.03 | 50.75 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.16 | 0.53 |
| 2| 827 | 35.88 | 11.39 | 0.56 |
| 3| 895 | 37.16 | 12.39 | 0.58 |
| 5| 1257 | 42.60 | 15.27 | 0.66 |
| 10| 1982 | 53.91 | 21.77 | 0.83 |
| 28| 4892 | 97.66 | 46.00 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.00 | 9.07 | 0.69 |
| 2| 5937 | 35.92 | 12.05 | 0.79 |
| 3| 6064 | 43.82 | 14.68 | 0.88 |
| 4| 6298 | 55.76 | 18.88 | 1.01 |
| 5| 6365 | 62.54 | 21.05 | 1.09 |
| 6| 6518 | 73.47 | 24.76 | 1.21 |
| 7| 6623 | 79.32 | 26.63 | 1.27 |
| 8| 7084 | 98.04 | 33.17 | 1.49 |
| 9| 6903 | 96.03 | 32.34 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1710 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2218 | 7157 | 99.38 | 38.04 | 1.54 |

