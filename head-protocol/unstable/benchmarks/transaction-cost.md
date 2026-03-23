--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-23 06:45:43.16321354 UTC |
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
| 1| 5837 | 10.93 | 3.49 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 19.10 | 6.05 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 41.36 | 11.94 | 0.60 |
| 4 | 227 | 858 | 48.15 | 13.98 | 0.68 |
| 5 | 283 | 969 | 55.98 | 16.21 | 0.76 |
| 6 | 339 | 1081 | 64.58 | 18.77 | 0.85 |
| 7 | 395 | 1192 | 83.09 | 23.57 | 1.04 |
| 8 | 451 | 1303 | 91.57 | 25.95 | 1.13 |
| 9 | 505 | 1414 | 99.07 | 28.25 | 1.22 |
| 10 | 560 | 1525 | 97.65 | 28.20 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 23.92 | 7.60 | 0.48 |
| 2| 1918 | 25.84 | 8.78 | 0.51 |
| 3| 2061 | 26.98 | 9.78 | 0.53 |
| 5| 2451 | 32.16 | 12.56 | 0.61 |
| 10| 3251 | 43.20 | 18.96 | 0.78 |
| 38| 7467 | 96.99 | 52.60 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 630 | 22.84 | 7.40 | 0.42 |
| 2| 760 | 24.27 | 8.45 | 0.44 |
| 3| 950 | 26.93 | 9.85 | 0.48 |
| 5| 1221 | 29.67 | 11.96 | 0.53 |
| 10| 1935 | 37.65 | 17.51 | 0.67 |
| 43| 6761 | 98.01 | 56.31 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.98 | 10.08 | 0.51 |
| 3| 978 | 33.43 | 11.44 | 0.55 |
| 5| 1355 | 36.28 | 13.63 | 0.60 |
| 10| 2093 | 48.27 | 20.31 | 0.78 |
| 37| 5850 | 96.82 | 51.86 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.87 | 10.16 | 0.53 |
| 2| 800 | 35.85 | 11.38 | 0.56 |
| 3| 1064 | 39.30 | 13.04 | 0.61 |
| 5| 1253 | 42.57 | 15.26 | 0.66 |
| 10| 2038 | 54.25 | 21.85 | 0.84 |
| 29| 4761 | 97.43 | 46.49 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.12 | 9.10 | 0.69 |
| 2| 5917 | 36.00 | 12.08 | 0.79 |
| 3| 6102 | 44.61 | 15.01 | 0.89 |
| 4| 6191 | 53.96 | 18.13 | 0.99 |
| 5| 6401 | 63.60 | 21.41 | 1.10 |
| 6| 6464 | 68.79 | 23.09 | 1.16 |
| 7| 6730 | 81.84 | 27.58 | 1.31 |
| 8| 6804 | 87.33 | 29.33 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1140 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1705 | 6852 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.49 | 37.73 | 1.53 |

