--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-17 04:48:31.526899089 UTC |
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
| 1| 5836 | 11.02 | 3.52 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.79 | 4.69 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 169 | 747 | 44.10 | 12.66 | 0.63 |
| 4 | 227 | 858 | 53.92 | 15.36 | 0.73 |
| 5 | 283 | 969 | 64.74 | 18.41 | 0.85 |
| 6 | 336 | 1081 | 75.56 | 21.36 | 0.96 |
| 7 | 394 | 1192 | 76.44 | 22.01 | 0.98 |
| 8 | 449 | 1303 | 83.12 | 23.98 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1751 | 23.30 | 7.41 | 0.47 |
| 2| 1926 | 25.39 | 8.68 | 0.50 |
| 3| 2168 | 28.96 | 10.34 | 0.55 |
| 5| 2317 | 30.29 | 12.03 | 0.58 |
| 10| 3317 | 44.66 | 19.40 | 0.80 |
| 40| 7678 | 99.30 | 54.56 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.57 | 7.32 | 0.41 |
| 2| 842 | 25.10 | 8.69 | 0.45 |
| 3| 979 | 27.08 | 9.89 | 0.48 |
| 5| 1329 | 33.79 | 13.09 | 0.58 |
| 10| 2006 | 40.11 | 18.19 | 0.69 |
| 41| 6833 | 99.29 | 55.34 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 29.13 | 8.90 | 0.48 |
| 2| 793 | 30.98 | 10.08 | 0.51 |
| 3| 868 | 32.08 | 11.03 | 0.53 |
| 5| 1362 | 38.56 | 14.24 | 0.62 |
| 10| 2128 | 46.18 | 19.76 | 0.76 |
| 37| 6005 | 98.38 | 52.36 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.15 | 0.53 |
| 2| 864 | 36.56 | 11.60 | 0.57 |
| 3| 1023 | 38.63 | 12.83 | 0.60 |
| 5| 1218 | 41.93 | 15.06 | 0.65 |
| 10| 1934 | 52.82 | 21.42 | 0.82 |
| 30| 4812 | 98.02 | 47.31 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 26.97 | 9.06 | 0.69 |
| 2| 6015 | 37.00 | 12.47 | 0.80 |
| 3| 6060 | 45.25 | 15.22 | 0.89 |
| 4| 6302 | 52.18 | 17.59 | 0.98 |
| 5| 6442 | 65.61 | 22.14 | 1.12 |
| 6| 6586 | 74.50 | 25.10 | 1.22 |
| 7| 6635 | 76.56 | 25.74 | 1.25 |
| 8| 6832 | 93.50 | 31.58 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

