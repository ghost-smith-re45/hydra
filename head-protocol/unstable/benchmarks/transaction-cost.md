--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-31 05:18:00.512647997 UTC |
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
| 1| 5840 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6243 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.64 | 9.36 | 0.79 |
| 43| 14281 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 169 | 747 | 41.38 | 11.95 | 0.60 |
| 4 | 227 | 858 | 50.85 | 14.62 | 0.70 |
| 5 | 280 | 969 | 64.27 | 18.26 | 0.84 |
| 6 | 337 | 1081 | 65.92 | 19.09 | 0.87 |
| 7 | 394 | 1192 | 72.66 | 21.15 | 0.94 |
| 8 | 448 | 1303 | 98.44 | 27.64 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.29 | 7.69 | 0.48 |
| 2| 1924 | 25.89 | 8.79 | 0.51 |
| 3| 2014 | 26.36 | 9.59 | 0.52 |
| 5| 2340 | 30.41 | 12.06 | 0.59 |
| 10| 3120 | 40.92 | 18.33 | 0.75 |
| 41| 7822 | 98.28 | 54.94 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.84 | 7.37 | 0.42 |
| 2| 765 | 24.31 | 8.46 | 0.44 |
| 3| 834 | 24.02 | 9.02 | 0.45 |
| 5| 1320 | 30.11 | 12.06 | 0.54 |
| 10| 1986 | 39.31 | 17.98 | 0.68 |
| 40| 6442 | 95.58 | 53.64 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.17 | 8.91 | 0.48 |
| 2| 851 | 31.65 | 10.28 | 0.52 |
| 3| 948 | 30.90 | 10.74 | 0.52 |
| 5| 1210 | 34.30 | 13.02 | 0.57 |
| 10| 2121 | 46.21 | 19.77 | 0.76 |
| 34| 5615 | 92.83 | 48.83 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 33.15 | 9.95 | 0.52 |
| 2| 849 | 36.56 | 11.60 | 0.57 |
| 3| 900 | 37.13 | 12.38 | 0.58 |
| 5| 1229 | 42.01 | 15.08 | 0.65 |
| 10| 1926 | 52.41 | 21.32 | 0.81 |
| 29| 4974 | 99.43 | 47.14 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 27.05 | 9.08 | 0.69 |
| 2| 5823 | 31.52 | 10.49 | 0.74 |
| 3| 6127 | 45.96 | 15.46 | 0.90 |
| 4| 6347 | 55.37 | 18.75 | 1.01 |
| 5| 6449 | 62.70 | 21.14 | 1.09 |
| 6| 6623 | 74.05 | 25.05 | 1.22 |
| 7| 6726 | 81.23 | 27.44 | 1.30 |
| 8| 7025 | 94.86 | 32.17 | 1.46 |
| 9| 6921 | 97.02 | 32.69 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 569 | 6173 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

