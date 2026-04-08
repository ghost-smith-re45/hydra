--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-08 07:06:36.04916279 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6640 | 18.90 | 5.97 | 0.64 |
| 10| 7644 | 29.02 | 9.14 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.57 | 12.25 | 0.62 |
| 4 | 226 | 858 | 48.13 | 13.97 | 0.68 |
| 5 | 283 | 969 | 62.27 | 17.72 | 0.82 |
| 6 | 339 | 1081 | 67.54 | 19.40 | 0.88 |
| 7 | 392 | 1192 | 75.99 | 21.82 | 0.97 |
| 8 | 451 | 1307 | 83.09 | 24.02 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2125 | 28.39 | 10.16 | 0.55 |
| 5| 2359 | 31.44 | 12.35 | 0.60 |
| 10| 3244 | 43.04 | 18.92 | 0.78 |
| 41| 7749 | 98.96 | 55.16 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 22.77 | 7.37 | 0.42 |
| 2| 756 | 23.58 | 8.23 | 0.43 |
| 3| 895 | 25.10 | 9.32 | 0.46 |
| 5| 1266 | 32.51 | 12.73 | 0.56 |
| 10| 2048 | 40.55 | 18.33 | 0.70 |
| 46| 7052 | 99.94 | 58.83 | 1.69 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.09 | 8.89 | 0.48 |
| 2| 853 | 29.82 | 9.80 | 0.50 |
| 3| 992 | 31.65 | 10.97 | 0.53 |
| 5| 1164 | 33.51 | 12.79 | 0.56 |
| 10| 2005 | 44.79 | 19.34 | 0.74 |
| 37| 6040 | 99.22 | 52.57 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.79 | 10.15 | 0.53 |
| 2| 834 | 35.92 | 11.40 | 0.56 |
| 3| 1007 | 38.55 | 12.81 | 0.60 |
| 5| 1309 | 43.28 | 15.47 | 0.67 |
| 10| 1959 | 53.72 | 21.70 | 0.83 |
| 29| 4947 | 99.86 | 47.23 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 6017 | 36.92 | 12.46 | 0.80 |
| 3| 6162 | 46.06 | 15.54 | 0.91 |
| 4| 6092 | 49.12 | 16.42 | 0.93 |
| 5| 6329 | 60.18 | 20.21 | 1.06 |
| 6| 6598 | 71.42 | 24.09 | 1.19 |
| 7| 6641 | 79.45 | 26.72 | 1.28 |
| 8| 6829 | 89.24 | 30.08 | 1.39 |
| 9| 6971 | 98.15 | 33.03 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6855 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

