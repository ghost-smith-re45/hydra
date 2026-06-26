--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-26 09:12:04.484106712 UTC |
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
| 2| 6039 | 12.61 | 4.00 | 0.55 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 169 | 747 | 41.38 | 11.95 | 0.60 |
| 4 | 227 | 858 | 49.06 | 14.19 | 0.69 |
| 5 | 282 | 969 | 63.41 | 18.09 | 0.84 |
| 6 | 341 | 1081 | 64.56 | 18.77 | 0.85 |
| 7 | 392 | 1192 | 78.12 | 22.33 | 0.99 |
| 8 | 451 | 1303 | 89.56 | 25.51 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.00 | 7.62 | 0.48 |
| 2| 1993 | 26.55 | 9.00 | 0.52 |
| 3| 2159 | 29.09 | 10.37 | 0.56 |
| 5| 2404 | 32.44 | 12.63 | 0.61 |
| 10| 3306 | 43.20 | 18.98 | 0.78 |
| 41| 7671 | 98.65 | 55.06 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.57 | 7.33 | 0.41 |
| 2| 703 | 22.62 | 7.96 | 0.42 |
| 3| 945 | 26.08 | 9.59 | 0.47 |
| 5| 1287 | 30.04 | 12.04 | 0.54 |
| 10| 2052 | 39.92 | 18.17 | 0.69 |
| 39| 6415 | 97.25 | 53.35 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 29.17 | 8.91 | 0.48 |
| 2| 827 | 29.15 | 9.59 | 0.49 |
| 3| 1015 | 33.65 | 11.52 | 0.55 |
| 5| 1263 | 37.70 | 13.98 | 0.61 |
| 10| 2059 | 44.83 | 19.35 | 0.74 |
| 39| 6025 | 97.74 | 53.43 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.88 | 11.39 | 0.56 |
| 3| 990 | 38.51 | 12.80 | 0.60 |
| 5| 1325 | 43.32 | 15.48 | 0.67 |
| 10| 1973 | 53.31 | 21.58 | 0.82 |
| 29| 4888 | 97.86 | 46.65 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.09 | 9.10 | 0.69 |
| 2| 5943 | 35.92 | 12.06 | 0.79 |
| 3| 6165 | 46.54 | 15.74 | 0.91 |
| 4| 6182 | 54.05 | 18.12 | 0.99 |
| 5| 6264 | 59.99 | 20.12 | 1.06 |
| 6| 6715 | 75.91 | 25.64 | 1.24 |
| 7| 6758 | 81.85 | 27.55 | 1.31 |
| 8| 6908 | 93.39 | 31.53 | 1.44 |
| 9| 6988 | 98.90 | 33.24 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6002 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2164 | 7126 | 96.88 | 37.08 | 1.51 |

