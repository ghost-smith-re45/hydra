--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-14 05:25:13.628797796 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.81 | 4.69 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.30 | 9.24 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10040 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 747 | 43.48 | 12.44 | 0.62 |
| 4 | 226 | 858 | 48.04 | 13.92 | 0.68 |
| 5 | 283 | 969 | 56.04 | 16.26 | 0.76 |
| 6 | 339 | 1081 | 69.88 | 19.97 | 0.91 |
| 7 | 396 | 1192 | 87.11 | 24.58 | 1.08 |
| 8 | 451 | 1303 | 87.61 | 25.05 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2013 | 26.32 | 9.58 | 0.52 |
| 5| 2359 | 30.93 | 12.22 | 0.59 |
| 10| 3089 | 39.36 | 17.91 | 0.73 |
| 39| 7560 | 98.47 | 53.66 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.81 | 7.38 | 0.42 |
| 2| 749 | 24.04 | 8.39 | 0.44 |
| 3| 958 | 28.16 | 10.18 | 0.49 |
| 5| 1265 | 31.18 | 12.37 | 0.55 |
| 10| 1896 | 38.37 | 17.73 | 0.67 |
| 42| 6670 | 98.07 | 55.65 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 27.50 | 8.46 | 0.46 |
| 2| 822 | 29.22 | 9.61 | 0.49 |
| 3| 910 | 32.72 | 11.23 | 0.54 |
| 5| 1272 | 37.58 | 13.95 | 0.61 |
| 10| 2077 | 48.01 | 20.22 | 0.78 |
| 36| 5930 | 95.58 | 50.93 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 801 | 35.92 | 11.40 | 0.56 |
| 3| 1021 | 38.85 | 12.91 | 0.60 |
| 5| 1206 | 42.30 | 15.17 | 0.65 |
| 10| 1942 | 53.42 | 21.61 | 0.82 |
| 28| 4663 | 94.75 | 45.10 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5961 | 35.99 | 12.09 | 0.79 |
| 3| 6035 | 42.29 | 14.21 | 0.86 |
| 4| 6305 | 55.02 | 18.51 | 1.01 |
| 5| 6379 | 61.70 | 20.72 | 1.08 |
| 6| 6544 | 70.63 | 23.80 | 1.18 |
| 7| 6846 | 85.10 | 28.72 | 1.35 |
| 8| 6897 | 93.09 | 31.44 | 1.43 |
| 9| 6945 | 92.43 | 31.10 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1139 | 6514 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1706 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2277 | 7194 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2222 | 7162 | 98.93 | 37.88 | 1.54 |

