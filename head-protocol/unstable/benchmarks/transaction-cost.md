--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-24 15:27:34.547222136 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 747 | 43.84 | 12.55 | 0.63 |
| 4 | 226 | 858 | 49.73 | 14.35 | 0.69 |
| 5 | 281 | 969 | 59.44 | 17.10 | 0.80 |
| 6 | 338 | 1081 | 74.55 | 21.04 | 0.95 |
| 7 | 394 | 1192 | 72.55 | 21.00 | 0.94 |
| 8 | 450 | 1303 | 87.39 | 25.09 | 1.09 |
| 9 | 505 | 1414 | 89.68 | 26.06 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.00 | 7.62 | 0.48 |
| 2| 1937 | 25.84 | 8.78 | 0.51 |
| 3| 2138 | 28.31 | 10.14 | 0.55 |
| 5| 2343 | 30.37 | 12.05 | 0.59 |
| 10| 3306 | 43.08 | 18.94 | 0.78 |
| 42| 7712 | 97.83 | 55.46 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.84 | 7.38 | 0.42 |
| 2| 827 | 25.41 | 8.76 | 0.46 |
| 3| 910 | 25.72 | 9.52 | 0.47 |
| 5| 1157 | 27.93 | 11.45 | 0.51 |
| 10| 1929 | 38.38 | 17.72 | 0.67 |
| 39| 6456 | 97.30 | 53.43 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 29.13 | 8.90 | 0.48 |
| 2| 822 | 29.15 | 9.59 | 0.49 |
| 3| 992 | 31.69 | 10.98 | 0.53 |
| 5| 1207 | 34.26 | 13.01 | 0.57 |
| 10| 1924 | 46.68 | 19.82 | 0.75 |
| 35| 5689 | 99.44 | 51.23 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.87 | 10.16 | 0.53 |
| 2| 820 | 35.89 | 11.39 | 0.56 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1200 | 41.97 | 15.07 | 0.65 |
| 10| 2137 | 56.35 | 22.49 | 0.86 |
| 29| 5030 | 99.80 | 47.25 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5824 | 27.08 | 9.09 | 0.69 |
| 2| 5966 | 35.93 | 12.06 | 0.79 |
| 3| 6060 | 44.69 | 15.03 | 0.89 |
| 4| 6212 | 52.78 | 17.69 | 0.98 |
| 5| 6360 | 61.58 | 20.74 | 1.08 |
| 6| 6458 | 68.19 | 22.84 | 1.15 |
| 7| 6636 | 81.48 | 27.34 | 1.30 |
| 8| 6879 | 91.84 | 31.03 | 1.42 |
| 9| 6926 | 98.95 | 33.33 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2221 | 7160 | 98.24 | 37.65 | 1.53 |

