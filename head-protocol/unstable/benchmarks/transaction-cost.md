--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-28 09:07:40.803969852 UTC |
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
| 1| 5836 | 10.76 | 3.42 | 0.52 |
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 747 | 43.84 | 12.55 | 0.63 |
| 4 | 226 | 858 | 47.98 | 13.96 | 0.68 |
| 5 | 284 | 969 | 64.28 | 18.23 | 0.84 |
| 6 | 338 | 1081 | 72.12 | 20.54 | 0.93 |
| 7 | 395 | 1192 | 76.27 | 21.89 | 0.98 |
| 8 | 449 | 1303 | 94.20 | 26.68 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1951 | 25.43 | 8.68 | 0.50 |
| 3| 2053 | 26.87 | 9.75 | 0.53 |
| 5| 2359 | 30.42 | 12.08 | 0.59 |
| 10| 3262 | 43.48 | 19.07 | 0.78 |
| 39| 7330 | 94.03 | 52.41 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 762 | 24.01 | 8.38 | 0.44 |
| 3| 960 | 26.80 | 9.82 | 0.48 |
| 5| 1160 | 28.57 | 11.66 | 0.52 |
| 10| 2096 | 42.25 | 18.77 | 0.72 |
| 41| 6597 | 98.06 | 54.98 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.54 | 8.47 | 0.46 |
| 2| 896 | 29.86 | 9.81 | 0.50 |
| 3| 998 | 31.65 | 10.97 | 0.53 |
| 5| 1263 | 37.06 | 13.79 | 0.60 |
| 10| 2083 | 45.84 | 19.64 | 0.75 |
| 36| 5649 | 98.35 | 51.56 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.83 | 10.15 | 0.53 |
| 2| 761 | 35.21 | 11.18 | 0.55 |
| 3| 1039 | 38.63 | 12.83 | 0.60 |
| 5| 1377 | 44.07 | 15.71 | 0.68 |
| 10| 2101 | 54.50 | 21.96 | 0.84 |
| 28| 4742 | 95.87 | 45.44 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 27.13 | 9.09 | 0.69 |
| 2| 5987 | 35.99 | 12.09 | 0.79 |
| 3| 6017 | 43.68 | 14.64 | 0.87 |
| 4| 6326 | 54.76 | 18.50 | 1.00 |
| 5| 6404 | 62.53 | 21.09 | 1.09 |
| 6| 6616 | 74.01 | 24.99 | 1.22 |
| 7| 6608 | 78.54 | 26.37 | 1.27 |
| 8| 6897 | 91.27 | 30.84 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 10 | 567 | 6171 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2163 | 7125 | 97.33 | 37.23 | 1.52 |

