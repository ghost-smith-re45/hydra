--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-09 07:06:54.331141946 UTC |
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
| 1| 5837 | 10.78 | 3.43 | 0.52 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7651 | 29.12 | 9.18 | 0.79 |
| 43| 14285 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.81 | 12.53 | 0.63 |
| 4 | 227 | 858 | 47.72 | 13.85 | 0.67 |
| 5 | 283 | 969 | 64.20 | 18.21 | 0.84 |
| 6 | 338 | 1081 | 74.00 | 21.03 | 0.95 |
| 7 | 394 | 1192 | 74.61 | 21.49 | 0.96 |
| 8 | 451 | 1303 | 91.92 | 26.13 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 23.92 | 7.60 | 0.48 |
| 2| 2002 | 26.58 | 9.01 | 0.52 |
| 3| 2013 | 25.98 | 9.50 | 0.52 |
| 5| 2386 | 31.03 | 12.25 | 0.59 |
| 10| 3180 | 42.18 | 18.68 | 0.77 |
| 39| 7625 | 99.24 | 53.88 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.50 | 7.29 | 0.41 |
| 2| 824 | 25.52 | 8.80 | 0.46 |
| 3| 896 | 25.55 | 9.47 | 0.46 |
| 5| 1158 | 28.16 | 11.51 | 0.51 |
| 10| 2128 | 40.86 | 18.40 | 0.71 |
| 41| 6757 | 99.25 | 55.30 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 27.51 | 8.47 | 0.46 |
| 2| 857 | 31.66 | 10.29 | 0.52 |
| 3| 868 | 32.05 | 11.02 | 0.53 |
| 5| 1282 | 37.78 | 14.00 | 0.61 |
| 10| 1975 | 47.52 | 20.06 | 0.77 |
| 35| 5933 | 96.50 | 50.55 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 864 | 36.60 | 11.61 | 0.57 |
| 3| 1038 | 39.26 | 13.03 | 0.61 |
| 5| 1158 | 41.22 | 14.85 | 0.64 |
| 10| 2094 | 54.70 | 22.01 | 0.84 |
| 28| 4915 | 98.71 | 46.34 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5841 | 27.05 | 9.08 | 0.69 |
| 2| 5898 | 32.60 | 10.89 | 0.75 |
| 3| 5994 | 40.24 | 13.41 | 0.84 |
| 4| 6315 | 56.15 | 18.92 | 1.02 |
| 5| 6356 | 60.66 | 20.37 | 1.07 |
| 6| 6472 | 69.18 | 23.19 | 1.16 |
| 7| 6603 | 78.86 | 26.46 | 1.27 |
| 8| 7001 | 95.32 | 32.22 | 1.46 |
| 9| 6939 | 95.30 | 31.98 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 38 | 2165 | 7127 | 96.44 | 36.92 | 1.51 |

