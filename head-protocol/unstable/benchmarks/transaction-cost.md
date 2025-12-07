--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-07 04:46:27.965682896 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.72 | 4.03 | 0.55 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6646 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 42.72 | 12.29 | 0.62 |
| 4 | 228 | 858 | 48.17 | 13.96 | 0.68 |
| 5 | 282 | 969 | 64.49 | 18.26 | 0.85 |
| 6 | 338 | 1085 | 65.99 | 19.07 | 0.87 |
| 7 | 396 | 1192 | 72.31 | 20.98 | 0.94 |
| 8 | 449 | 1303 | 92.46 | 26.26 | 1.14 |
| 10 | 560 | 1525 | 97.03 | 28.22 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.00 | 7.62 | 0.48 |
| 2| 1926 | 25.84 | 8.78 | 0.51 |
| 3| 2089 | 27.39 | 9.88 | 0.53 |
| 5| 2416 | 32.23 | 12.58 | 0.61 |
| 10| 3200 | 40.98 | 18.37 | 0.75 |
| 41| 7573 | 96.33 | 54.40 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.57 | 7.32 | 0.41 |
| 2| 737 | 24.08 | 8.40 | 0.44 |
| 3| 829 | 24.09 | 9.03 | 0.45 |
| 5| 1174 | 27.97 | 11.46 | 0.51 |
| 10| 1885 | 38.36 | 17.72 | 0.67 |
| 40| 6269 | 96.03 | 53.69 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 29.17 | 8.91 | 0.48 |
| 2| 810 | 30.87 | 10.05 | 0.51 |
| 3| 898 | 30.23 | 10.54 | 0.51 |
| 5| 1278 | 38.06 | 14.09 | 0.62 |
| 10| 2165 | 49.69 | 20.72 | 0.80 |
| 37| 6137 | 99.34 | 52.67 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 997 | 38.55 | 12.81 | 0.60 |
| 5| 1369 | 43.54 | 15.56 | 0.67 |
| 10| 2043 | 53.90 | 21.77 | 0.83 |
| 30| 4922 | 98.73 | 47.55 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 27.08 | 9.08 | 0.69 |
| 2| 5966 | 37.01 | 12.47 | 0.80 |
| 3| 6118 | 46.01 | 15.50 | 0.90 |
| 4| 6307 | 54.58 | 18.39 | 1.00 |
| 5| 6469 | 65.85 | 22.29 | 1.13 |
| 6| 6481 | 72.63 | 24.38 | 1.20 |
| 7| 6715 | 81.56 | 27.44 | 1.30 |
| 8| 6879 | 90.57 | 30.52 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.72 | 10.56 | 0.73 |
| 10 | 20 | 1139 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6856 | 81.81 | 31.06 | 1.34 |
| 10 | 39 | 2220 | 7160 | 98.68 | 37.80 | 1.54 |

