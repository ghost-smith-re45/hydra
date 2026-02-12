--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-12 05:41:15.24084657 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6240 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.02 | 9.14 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 170 | 751 | 42.33 | 12.17 | 0.61 |
| 4 | 227 | 858 | 52.41 | 15.02 | 0.72 |
| 5 | 283 | 969 | 62.79 | 17.85 | 0.83 |
| 6 | 336 | 1081 | 74.65 | 21.07 | 0.95 |
| 7 | 393 | 1192 | 79.20 | 22.72 | 1.01 |
| 8 | 452 | 1307 | 88.95 | 25.36 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 23.92 | 7.60 | 0.48 |
| 2| 1952 | 25.85 | 8.78 | 0.51 |
| 3| 2158 | 27.97 | 10.06 | 0.54 |
| 5| 2359 | 31.22 | 12.29 | 0.59 |
| 10| 3236 | 42.72 | 18.84 | 0.77 |
| 43| 7816 | 99.19 | 56.52 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 607 | 22.84 | 7.38 | 0.41 |
| 2| 832 | 25.53 | 8.79 | 0.46 |
| 3| 978 | 27.04 | 9.88 | 0.48 |
| 5| 1279 | 30.19 | 12.08 | 0.54 |
| 10| 1948 | 37.80 | 17.55 | 0.67 |
| 39| 6407 | 98.32 | 53.70 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.13 | 8.90 | 0.48 |
| 2| 863 | 31.69 | 10.29 | 0.52 |
| 3| 915 | 32.68 | 11.22 | 0.54 |
| 5| 1207 | 34.30 | 13.02 | 0.57 |
| 10| 1931 | 46.88 | 19.87 | 0.76 |
| 36| 5882 | 97.52 | 51.45 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 865 | 36.60 | 11.61 | 0.57 |
| 3| 942 | 37.87 | 12.61 | 0.59 |
| 5| 1218 | 41.93 | 15.06 | 0.65 |
| 10| 1942 | 53.31 | 21.58 | 0.82 |
| 30| 4933 | 98.36 | 47.44 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.09 | 9.09 | 0.69 |
| 2| 5977 | 37.17 | 12.53 | 0.80 |
| 3| 6106 | 44.57 | 15.00 | 0.89 |
| 4| 6187 | 53.04 | 17.77 | 0.98 |
| 5| 6414 | 61.33 | 20.65 | 1.08 |
| 6| 6508 | 72.86 | 24.50 | 1.20 |
| 7| 6717 | 80.93 | 27.38 | 1.30 |
| 8| 6870 | 91.55 | 30.83 | 1.41 |
| 9| 6935 | 96.23 | 32.30 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6856 | 79.34 | 30.22 | 1.31 |
| 10 | 38 | 2161 | 7124 | 96.88 | 37.08 | 1.51 |

