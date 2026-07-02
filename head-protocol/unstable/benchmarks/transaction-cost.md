--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-02 08:45:13.098521489 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 43.66 | 12.53 | 0.63 |
| 4 | 227 | 858 | 49.59 | 14.32 | 0.69 |
| 5 | 282 | 969 | 62.71 | 17.92 | 0.83 |
| 6 | 338 | 1081 | 69.73 | 19.93 | 0.90 |
| 7 | 394 | 1192 | 75.77 | 21.72 | 0.97 |
| 8 | 452 | 1303 | 87.45 | 25.01 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1924 | 25.76 | 8.76 | 0.51 |
| 3| 2055 | 27.02 | 9.79 | 0.53 |
| 5| 2482 | 32.83 | 12.76 | 0.62 |
| 10| 3115 | 39.63 | 17.98 | 0.74 |
| 39| 7538 | 97.64 | 53.47 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.54 | 7.30 | 0.41 |
| 2| 802 | 25.13 | 8.69 | 0.45 |
| 3| 872 | 25.01 | 9.31 | 0.46 |
| 5| 1141 | 28.80 | 11.72 | 0.52 |
| 10| 2106 | 43.41 | 19.10 | 0.73 |
| 40| 6430 | 94.45 | 53.32 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 29.13 | 8.90 | 0.48 |
| 2| 824 | 29.15 | 9.59 | 0.49 |
| 3| 945 | 30.94 | 10.75 | 0.52 |
| 5| 1247 | 37.06 | 13.79 | 0.60 |
| 10| 1900 | 46.24 | 19.68 | 0.75 |
| 37| 6016 | 97.94 | 52.23 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.87 | 10.16 | 0.53 |
| 2| 868 | 36.60 | 11.61 | 0.57 |
| 3| 984 | 38.58 | 12.82 | 0.60 |
| 5| 1214 | 41.86 | 15.04 | 0.65 |
| 10| 2155 | 56.05 | 22.42 | 0.86 |
| 30| 4965 | 98.66 | 47.53 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 26.96 | 9.05 | 0.69 |
| 2| 6002 | 37.05 | 12.51 | 0.80 |
| 3| 6030 | 41.44 | 13.88 | 0.85 |
| 4| 6343 | 54.91 | 18.50 | 1.01 |
| 5| 6318 | 60.42 | 20.38 | 1.06 |
| 6| 6446 | 65.63 | 22.01 | 1.12 |
| 7| 6570 | 77.61 | 25.97 | 1.25 |
| 8| 6973 | 93.36 | 31.51 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

