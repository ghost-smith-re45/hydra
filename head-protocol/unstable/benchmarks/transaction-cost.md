--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-09 09:00:51.167016097 UTC |
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
| 1| 5837 | 10.66 | 3.39 | 0.52 |
| 2| 6042 | 12.41 | 3.92 | 0.54 |
| 3| 6239 | 14.81 | 4.69 | 0.58 |
| 5| 6641 | 18.71 | 5.91 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10079 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 169 | 747 | 39.94 | 11.60 | 0.59 |
| 4 | 226 | 858 | 49.70 | 14.35 | 0.69 |
| 5 | 283 | 969 | 63.83 | 18.09 | 0.84 |
| 6 | 339 | 1081 | 64.53 | 18.69 | 0.85 |
| 7 | 393 | 1192 | 74.93 | 21.66 | 0.96 |
| 8 | 449 | 1303 | 98.57 | 27.77 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 23.30 | 7.41 | 0.47 |
| 2| 1918 | 25.55 | 8.71 | 0.50 |
| 3| 2018 | 25.94 | 9.49 | 0.52 |
| 5| 2360 | 31.15 | 12.28 | 0.59 |
| 10| 3048 | 38.72 | 17.72 | 0.72 |
| 41| 7763 | 98.83 | 55.12 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.84 | 7.37 | 0.42 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 830 | 24.13 | 9.06 | 0.45 |
| 5| 1256 | 30.03 | 12.03 | 0.53 |
| 10| 2010 | 38.76 | 17.83 | 0.68 |
| 43| 6811 | 99.61 | 56.76 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.54 | 8.47 | 0.46 |
| 2| 782 | 30.87 | 10.05 | 0.51 |
| 3| 995 | 31.69 | 10.98 | 0.53 |
| 5| 1310 | 37.70 | 13.99 | 0.61 |
| 10| 1945 | 44.03 | 19.11 | 0.73 |
| 37| 6091 | 98.08 | 52.28 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 903 | 36.52 | 11.59 | 0.57 |
| 3| 984 | 38.66 | 12.84 | 0.60 |
| 5| 1213 | 41.97 | 15.07 | 0.65 |
| 10| 2005 | 54.13 | 21.83 | 0.83 |
| 29| 4863 | 97.58 | 46.58 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 27.09 | 9.08 | 0.69 |
| 2| 5917 | 34.91 | 11.68 | 0.78 |
| 3| 6124 | 45.90 | 15.46 | 0.90 |
| 4| 6260 | 54.98 | 18.49 | 1.00 |
| 5| 6287 | 59.30 | 19.86 | 1.05 |
| 6| 6673 | 75.20 | 25.40 | 1.23 |
| 7| 6765 | 81.58 | 27.49 | 1.31 |
| 8| 6834 | 88.98 | 30.05 | 1.39 |
| 9| 6812 | 92.66 | 31.03 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.05 | 6.02 | 0.60 |
| 10 | 5 | 283 | 6002 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6172 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

