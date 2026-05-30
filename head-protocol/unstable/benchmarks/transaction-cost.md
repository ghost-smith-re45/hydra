--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-30 08:00:07.489033266 UTC |
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
| 1| 5836 | 10.66 | 3.39 | 0.52 |
| 2| 6041 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.69 | 4.65 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 41.39 | 11.95 | 0.60 |
| 4 | 226 | 858 | 52.46 | 15.01 | 0.72 |
| 5 | 282 | 969 | 56.61 | 16.40 | 0.77 |
| 6 | 339 | 1081 | 75.71 | 21.40 | 0.96 |
| 7 | 395 | 1192 | 80.40 | 22.88 | 1.02 |
| 8 | 448 | 1303 | 91.74 | 25.98 | 1.14 |
| 9 | 506 | 1414 | 91.62 | 26.47 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 1995 | 26.92 | 9.09 | 0.52 |
| 3| 2099 | 28.02 | 10.08 | 0.54 |
| 5| 2431 | 31.84 | 12.48 | 0.60 |
| 10| 3057 | 39.50 | 17.95 | 0.73 |
| 41| 7785 | 99.54 | 55.32 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.54 | 7.30 | 0.41 |
| 2| 703 | 22.55 | 7.95 | 0.42 |
| 3| 1020 | 28.29 | 10.22 | 0.50 |
| 5| 1207 | 29.03 | 11.76 | 0.52 |
| 10| 2000 | 39.47 | 18.02 | 0.69 |
| 43| 6832 | 99.54 | 56.76 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.50 | 8.46 | 0.46 |
| 2| 822 | 29.22 | 9.61 | 0.49 |
| 3| 960 | 33.40 | 11.44 | 0.54 |
| 5| 1330 | 35.80 | 13.48 | 0.60 |
| 10| 2163 | 46.01 | 19.72 | 0.76 |
| 36| 6035 | 97.38 | 51.45 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 829 | 35.92 | 11.40 | 0.56 |
| 3| 896 | 37.13 | 12.38 | 0.58 |
| 5| 1277 | 42.72 | 15.30 | 0.66 |
| 10| 2047 | 54.92 | 22.06 | 0.84 |
| 28| 4877 | 97.67 | 46.00 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5802 | 27.09 | 9.09 | 0.69 |
| 2| 5995 | 36.92 | 12.47 | 0.80 |
| 3| 6074 | 44.85 | 15.07 | 0.89 |
| 4| 6239 | 55.12 | 18.55 | 1.00 |
| 5| 6422 | 63.96 | 21.54 | 1.10 |
| 6| 6614 | 71.81 | 24.22 | 1.20 |
| 7| 6771 | 84.61 | 28.51 | 1.34 |
| 8| 6982 | 93.40 | 31.46 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.47 | 22.36 | 1.08 |
| 10 | 30 | 1705 | 6851 | 81.11 | 30.83 | 1.33 |
| 10 | 39 | 2221 | 7160 | 99.12 | 37.95 | 1.54 |

