--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-07 06:48:00.429589321 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.84 | 4.08 | 0.55 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 751 | 41.40 | 11.97 | 0.60 |
| 4 | 227 | 858 | 49.72 | 14.35 | 0.69 |
| 5 | 283 | 969 | 64.46 | 18.31 | 0.85 |
| 6 | 341 | 1081 | 72.95 | 20.66 | 0.94 |
| 7 | 394 | 1192 | 84.41 | 23.84 | 1.06 |
| 8 | 450 | 1303 | 96.23 | 27.11 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.29 | 7.69 | 0.48 |
| 2| 1886 | 24.47 | 8.41 | 0.49 |
| 3| 2085 | 27.32 | 9.86 | 0.53 |
| 5| 2364 | 31.41 | 12.34 | 0.60 |
| 10| 3284 | 43.10 | 18.94 | 0.78 |
| 42| 7549 | 95.58 | 54.84 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.84 | 7.39 | 0.42 |
| 2| 808 | 25.57 | 8.80 | 0.46 |
| 3| 911 | 25.72 | 9.52 | 0.47 |
| 5| 1151 | 28.80 | 11.71 | 0.52 |
| 10| 2035 | 40.45 | 18.29 | 0.70 |
| 42| 6679 | 98.89 | 55.86 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 27.50 | 8.46 | 0.46 |
| 2| 865 | 29.90 | 9.82 | 0.50 |
| 3| 952 | 33.43 | 11.44 | 0.54 |
| 5| 1131 | 35.64 | 13.36 | 0.58 |
| 10| 2048 | 48.30 | 20.31 | 0.78 |
| 36| 6164 | 99.35 | 52.06 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 849 | 36.60 | 11.61 | 0.57 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1267 | 42.49 | 15.24 | 0.66 |
| 10| 2131 | 55.77 | 22.33 | 0.86 |
| 28| 4731 | 96.28 | 45.56 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 26.96 | 9.06 | 0.69 |
| 2| 5981 | 35.87 | 12.06 | 0.79 |
| 3| 6114 | 45.95 | 15.49 | 0.90 |
| 4| 6163 | 54.12 | 18.16 | 0.99 |
| 5| 6391 | 64.04 | 21.59 | 1.10 |
| 6| 6466 | 72.58 | 24.44 | 1.20 |
| 7| 6850 | 84.85 | 28.69 | 1.34 |
| 8| 6943 | 93.67 | 31.60 | 1.44 |
| 9| 7091 | 99.57 | 33.54 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.85 | 7.43 | 0.64 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |

