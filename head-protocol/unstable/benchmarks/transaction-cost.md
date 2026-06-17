--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-17 10:20:44.378820567 UTC |
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
| 1| 5834 | 10.57 | 3.36 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6646 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14285 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 112 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 171 | 747 | 40.12 | 11.65 | 0.59 |
| 4 | 227 | 862 | 51.04 | 14.67 | 0.71 |
| 5 | 282 | 969 | 55.24 | 16.06 | 0.75 |
| 6 | 336 | 1081 | 67.92 | 19.53 | 0.89 |
| 7 | 392 | 1192 | 78.28 | 22.37 | 1.00 |
| 8 | 451 | 1303 | 86.13 | 24.80 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 23.92 | 7.60 | 0.48 |
| 2| 1977 | 26.55 | 9.00 | 0.52 |
| 3| 2116 | 28.39 | 10.16 | 0.55 |
| 5| 2479 | 33.43 | 12.91 | 0.62 |
| 10| 3204 | 42.24 | 18.71 | 0.77 |
| 40| 7661 | 98.55 | 54.35 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.54 | 7.30 | 0.41 |
| 2| 788 | 25.31 | 8.74 | 0.45 |
| 3| 944 | 27.07 | 9.90 | 0.48 |
| 5| 1303 | 31.23 | 12.38 | 0.55 |
| 10| 1969 | 39.61 | 18.06 | 0.69 |
| 41| 6676 | 99.56 | 55.38 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 785 | 30.91 | 10.06 | 0.51 |
| 3| 941 | 30.94 | 10.75 | 0.52 |
| 5| 1168 | 33.66 | 12.83 | 0.57 |
| 10| 2042 | 47.93 | 20.20 | 0.77 |
| 34| 5783 | 94.04 | 49.17 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 818 | 35.81 | 11.37 | 0.56 |
| 3| 943 | 37.91 | 12.62 | 0.59 |
| 5| 1204 | 41.93 | 15.06 | 0.65 |
| 10| 2159 | 55.26 | 22.16 | 0.85 |
| 28| 4897 | 97.56 | 45.99 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5800 | 27.16 | 9.12 | 0.69 |
| 2| 6014 | 36.83 | 12.42 | 0.80 |
| 3| 6074 | 44.84 | 15.05 | 0.89 |
| 4| 6296 | 56.19 | 18.96 | 1.02 |
| 5| 6203 | 53.55 | 17.89 | 0.98 |
| 6| 6487 | 72.07 | 24.23 | 1.19 |
| 7| 6916 | 86.37 | 29.21 | 1.36 |
| 8| 6894 | 94.34 | 31.83 | 1.45 |
| 9| 6994 | 98.29 | 33.12 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1135 | 6510 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6856 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

