--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-16 10:42:42.64101913 UTC |
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
| 1| 5834 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6643 | 19.00 | 6.01 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2161 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 41.23 | 11.93 | 0.60 |
| 4 | 226 | 862 | 49.50 | 14.28 | 0.69 |
| 5 | 284 | 969 | 60.56 | 17.34 | 0.81 |
| 6 | 337 | 1081 | 68.22 | 19.61 | 0.89 |
| 7 | 395 | 1192 | 74.40 | 21.44 | 0.96 |
| 8 | 449 | 1303 | 93.54 | 26.41 | 1.15 |
| 9 | 506 | 1414 | 98.88 | 28.15 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1996 | 27.00 | 9.10 | 0.52 |
| 3| 2062 | 26.95 | 9.77 | 0.53 |
| 5| 2492 | 33.55 | 12.94 | 0.62 |
| 10| 3172 | 41.16 | 18.41 | 0.76 |
| 39| 7544 | 98.16 | 53.57 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.50 | 7.29 | 0.41 |
| 2| 827 | 25.56 | 8.81 | 0.46 |
| 3| 902 | 25.07 | 9.31 | 0.46 |
| 5| 1146 | 28.87 | 11.74 | 0.52 |
| 10| 1951 | 37.66 | 17.50 | 0.67 |
| 38| 6311 | 94.94 | 52.11 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.51 | 8.47 | 0.46 |
| 2| 775 | 30.98 | 10.08 | 0.51 |
| 3| 910 | 32.76 | 11.24 | 0.54 |
| 5| 1240 | 37.06 | 13.78 | 0.60 |
| 10| 1953 | 46.58 | 19.79 | 0.76 |
| 36| 6035 | 98.78 | 51.82 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.79 | 10.15 | 0.53 |
| 2| 813 | 35.88 | 11.39 | 0.56 |
| 3| 1010 | 38.63 | 12.83 | 0.60 |
| 5| 1304 | 43.20 | 15.45 | 0.67 |
| 10| 2061 | 54.81 | 22.03 | 0.84 |
| 29| 4837 | 98.33 | 46.83 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5993 | 35.79 | 12.03 | 0.79 |
| 3| 6017 | 43.76 | 14.68 | 0.87 |
| 4| 6140 | 50.32 | 16.87 | 0.95 |
| 5| 6372 | 61.75 | 20.79 | 1.08 |
| 6| 6575 | 71.64 | 24.16 | 1.19 |
| 7| 6902 | 85.17 | 28.78 | 1.35 |
| 8| 6849 | 92.24 | 31.05 | 1.42 |
| 9| 7005 | 97.72 | 32.94 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 40 | 2276 | 7193 | 99.66 | 38.24 | 1.55 |

