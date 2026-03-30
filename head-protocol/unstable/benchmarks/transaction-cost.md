--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-30 07:19:56.936163249 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 13.18 | 4.20 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6646 | 18.60 | 5.87 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 33.25 | 9.61 | 0.52 |
| 3 | 168 | 747 | 43.83 | 12.55 | 0.63 |
| 4 | 226 | 858 | 48.38 | 14.06 | 0.68 |
| 5 | 283 | 969 | 64.18 | 18.21 | 0.84 |
| 6 | 338 | 1081 | 64.05 | 18.60 | 0.85 |
| 7 | 394 | 1192 | 78.76 | 22.53 | 1.00 |
| 8 | 450 | 1303 | 85.39 | 24.52 | 1.07 |
| 9 | 506 | 1414 | 92.15 | 26.49 | 1.15 |
| 10 | 561 | 1525 | 99.83 | 28.83 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.00 | 7.62 | 0.48 |
| 2| 1880 | 24.40 | 8.39 | 0.49 |
| 3| 2053 | 26.95 | 9.77 | 0.53 |
| 5| 2456 | 32.56 | 12.66 | 0.61 |
| 10| 3186 | 41.35 | 18.45 | 0.76 |
| 37| 7182 | 90.92 | 50.21 | 1.56 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 22.50 | 7.30 | 0.41 |
| 2| 807 | 25.55 | 8.80 | 0.46 |
| 3| 941 | 27.10 | 9.91 | 0.48 |
| 5| 1192 | 29.14 | 11.78 | 0.52 |
| 10| 2119 | 42.70 | 18.94 | 0.73 |
| 42| 6635 | 98.82 | 55.86 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 28.42 | 8.68 | 0.47 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 992 | 31.61 | 10.96 | 0.53 |
| 5| 1353 | 35.72 | 13.46 | 0.60 |
| 10| 1980 | 47.24 | 19.99 | 0.76 |
| 37| 5917 | 96.06 | 51.68 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.79 | 10.15 | 0.53 |
| 2| 761 | 35.17 | 11.17 | 0.55 |
| 3| 943 | 37.84 | 12.60 | 0.59 |
| 5| 1233 | 41.82 | 15.03 | 0.65 |
| 10| 1967 | 53.57 | 21.65 | 0.83 |
| 29| 5009 | 99.67 | 47.20 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5800 | 27.09 | 9.10 | 0.69 |
| 2| 5957 | 35.80 | 12.03 | 0.79 |
| 3| 5968 | 40.47 | 13.49 | 0.84 |
| 4| 6374 | 57.10 | 19.33 | 1.03 |
| 5| 6404 | 63.59 | 21.44 | 1.10 |
| 6| 6631 | 74.56 | 25.13 | 1.23 |
| 7| 6570 | 74.51 | 25.07 | 1.22 |
| 8| 6900 | 92.68 | 31.22 | 1.43 |
| 9| 6955 | 95.48 | 32.08 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2279 | 7196 | 99.66 | 38.24 | 1.55 |

