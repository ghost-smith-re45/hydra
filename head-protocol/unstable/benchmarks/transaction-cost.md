--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-30 05:24:39.506507185 UTC |
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
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.48 | 4.58 | 0.57 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 169 | 747 | 42.44 | 12.22 | 0.61 |
| 4 | 227 | 858 | 53.65 | 15.30 | 0.73 |
| 5 | 284 | 969 | 59.36 | 17.05 | 0.80 |
| 6 | 339 | 1081 | 64.27 | 18.66 | 0.85 |
| 7 | 393 | 1192 | 72.57 | 21.01 | 0.94 |
| 8 | 452 | 1303 | 81.26 | 23.58 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 23.92 | 7.60 | 0.48 |
| 2| 1924 | 25.76 | 8.76 | 0.51 |
| 3| 2109 | 28.47 | 10.18 | 0.55 |
| 5| 2364 | 31.11 | 12.27 | 0.59 |
| 10| 3270 | 43.81 | 19.15 | 0.79 |
| 42| 7885 | 99.48 | 56.00 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 607 | 22.84 | 7.37 | 0.41 |
| 2| 821 | 25.13 | 8.69 | 0.45 |
| 3| 995 | 28.19 | 10.20 | 0.50 |
| 5| 1204 | 29.03 | 11.76 | 0.52 |
| 10| 2028 | 39.51 | 18.02 | 0.69 |
| 40| 6496 | 97.80 | 54.23 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 29.17 | 8.91 | 0.48 |
| 2| 766 | 28.47 | 9.38 | 0.48 |
| 3| 940 | 30.87 | 10.74 | 0.52 |
| 5| 1288 | 34.85 | 13.20 | 0.58 |
| 10| 2008 | 47.95 | 20.21 | 0.77 |
| 38| 6085 | 98.61 | 53.05 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 761 | 35.21 | 11.18 | 0.55 |
| 3| 938 | 37.84 | 12.60 | 0.59 |
| 5| 1158 | 41.11 | 14.82 | 0.64 |
| 10| 2038 | 54.42 | 21.94 | 0.84 |
| 29| 4904 | 98.03 | 46.68 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5782 | 27.13 | 9.09 | 0.69 |
| 2| 5981 | 37.12 | 12.49 | 0.80 |
| 3| 6039 | 43.92 | 14.70 | 0.88 |
| 4| 6164 | 52.86 | 17.72 | 0.98 |
| 5| 6514 | 66.10 | 22.34 | 1.13 |
| 6| 6603 | 73.51 | 24.89 | 1.21 |
| 7| 6893 | 85.46 | 28.86 | 1.35 |
| 8| 6858 | 88.79 | 29.95 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 30 | 1709 | 6856 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2218 | 7158 | 99.38 | 38.04 | 1.54 |

