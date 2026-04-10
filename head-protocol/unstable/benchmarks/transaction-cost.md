--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-10 07:18:11.09188813 UTC |
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
| 2| 6041 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 15.16 | 4.82 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 42.38 | 12.20 | 0.61 |
| 4 | 228 | 862 | 50.84 | 14.60 | 0.70 |
| 5 | 282 | 969 | 55.58 | 16.14 | 0.76 |
| 6 | 337 | 1081 | 67.84 | 19.51 | 0.89 |
| 7 | 394 | 1196 | 82.28 | 23.33 | 1.04 |
| 8 | 451 | 1303 | 81.63 | 23.72 | 1.04 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.51 | 8.70 | 0.50 |
| 3| 2013 | 26.28 | 9.57 | 0.52 |
| 5| 2382 | 31.03 | 12.25 | 0.59 |
| 10| 3219 | 41.60 | 18.54 | 0.76 |
| 38| 7526 | 97.20 | 52.68 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.54 | 7.30 | 0.41 |
| 2| 806 | 25.52 | 8.79 | 0.46 |
| 3| 897 | 25.83 | 9.54 | 0.47 |
| 5| 1254 | 31.07 | 12.34 | 0.55 |
| 10| 1986 | 39.54 | 18.05 | 0.69 |
| 40| 6462 | 95.76 | 53.66 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 830 | 29.19 | 9.60 | 0.49 |
| 3| 902 | 30.15 | 10.52 | 0.51 |
| 5| 1300 | 37.69 | 13.98 | 0.61 |
| 10| 1962 | 44.19 | 19.15 | 0.73 |
| 37| 6020 | 99.99 | 52.82 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.81 | 11.37 | 0.56 |
| 3| 943 | 37.91 | 12.62 | 0.59 |
| 5| 1310 | 43.24 | 15.47 | 0.67 |
| 10| 2061 | 54.74 | 22.01 | 0.84 |
| 29| 5030 | 99.63 | 47.23 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.13 | 9.09 | 0.69 |
| 2| 5871 | 32.61 | 10.88 | 0.75 |
| 3| 6127 | 45.59 | 15.38 | 0.90 |
| 4| 6192 | 51.18 | 17.21 | 0.96 |
| 5| 6335 | 62.86 | 21.13 | 1.09 |
| 6| 6572 | 74.63 | 25.14 | 1.22 |
| 7| 6514 | 71.38 | 23.88 | 1.19 |
| 8| 6796 | 92.31 | 31.08 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.28 | 10.41 | 0.73 |
| 10 | 30 | 1711 | 6858 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.05 | 37.58 | 1.53 |

