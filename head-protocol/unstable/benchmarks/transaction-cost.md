--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-02 06:35:16.158274212 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6041 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6646 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 751 | 43.84 | 12.55 | 0.63 |
| 4 | 227 | 862 | 52.28 | 14.94 | 0.72 |
| 5 | 282 | 969 | 57.87 | 16.67 | 0.78 |
| 6 | 337 | 1081 | 64.98 | 18.87 | 0.86 |
| 7 | 395 | 1192 | 74.51 | 21.47 | 0.96 |
| 8 | 451 | 1303 | 80.98 | 23.51 | 1.03 |
| 9 | 504 | 1414 | 97.03 | 27.82 | 1.20 |
| 10 | 560 | 1525 | 98.47 | 28.58 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1985 | 26.92 | 9.08 | 0.52 |
| 3| 2072 | 27.36 | 9.87 | 0.53 |
| 5| 2326 | 30.00 | 11.96 | 0.58 |
| 10| 3193 | 41.86 | 18.60 | 0.76 |
| 43| 7829 | 98.99 | 56.45 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 22.54 | 7.31 | 0.41 |
| 2| 795 | 24.05 | 8.40 | 0.44 |
| 3| 946 | 26.57 | 9.76 | 0.48 |
| 5| 1300 | 30.69 | 12.26 | 0.54 |
| 10| 1936 | 38.50 | 17.74 | 0.67 |
| 42| 6498 | 95.17 | 54.83 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 782 | 30.95 | 10.07 | 0.51 |
| 3| 910 | 32.68 | 11.22 | 0.54 |
| 5| 1368 | 38.33 | 14.18 | 0.62 |
| 10| 2124 | 48.75 | 20.44 | 0.79 |
| 35| 5690 | 94.61 | 49.97 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 829 | 35.89 | 11.39 | 0.56 |
| 3| 941 | 37.91 | 12.62 | 0.59 |
| 5| 1351 | 43.40 | 15.50 | 0.67 |
| 10| 1981 | 53.61 | 21.67 | 0.83 |
| 29| 4872 | 98.81 | 46.93 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 27.05 | 9.08 | 0.69 |
| 2| 5922 | 36.04 | 12.11 | 0.79 |
| 3| 6152 | 46.04 | 15.50 | 0.90 |
| 4| 6215 | 53.91 | 18.11 | 0.99 |
| 5| 6172 | 54.78 | 18.24 | 1.00 |
| 6| 6482 | 72.43 | 24.36 | 1.20 |
| 7| 6895 | 85.08 | 28.74 | 1.35 |
| 8| 6819 | 88.96 | 29.99 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2217 | 7156 | 99.56 | 38.10 | 1.54 |

