--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-25 07:33:54.365856131 UTC |
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
| 2| 6041 | 12.41 | 3.92 | 0.54 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.09 | 9.17 | 0.79 |
| 43| 14285 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 40.12 | 11.65 | 0.59 |
| 4 | 227 | 862 | 49.44 | 14.26 | 0.69 |
| 5 | 283 | 974 | 62.44 | 17.79 | 0.83 |
| 6 | 338 | 1081 | 68.33 | 19.67 | 0.89 |
| 7 | 393 | 1192 | 73.24 | 21.30 | 0.95 |
| 8 | 450 | 1303 | 84.89 | 24.40 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2178 | 29.47 | 10.46 | 0.56 |
| 5| 2317 | 30.26 | 12.02 | 0.58 |
| 10| 3209 | 41.92 | 18.61 | 0.76 |
| 39| 7597 | 98.31 | 53.62 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.57 | 7.33 | 0.41 |
| 2| 795 | 25.16 | 8.70 | 0.45 |
| 3| 941 | 26.63 | 9.78 | 0.48 |
| 5| 1253 | 31.00 | 12.32 | 0.54 |
| 10| 2093 | 41.77 | 18.66 | 0.71 |
| 40| 6386 | 93.73 | 53.10 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 836 | 31.66 | 10.29 | 0.52 |
| 3| 869 | 32.04 | 11.02 | 0.53 |
| 5| 1268 | 37.74 | 13.99 | 0.61 |
| 10| 2231 | 50.05 | 20.84 | 0.80 |
| 35| 5826 | 95.75 | 50.31 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 862 | 36.60 | 11.61 | 0.57 |
| 3| 944 | 37.91 | 12.62 | 0.59 |
| 5| 1324 | 43.39 | 15.50 | 0.67 |
| 10| 1983 | 53.30 | 21.58 | 0.82 |
| 30| 4951 | 99.46 | 47.73 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5782 | 27.09 | 9.08 | 0.69 |
| 2| 5961 | 35.87 | 12.05 | 0.79 |
| 3| 6203 | 47.07 | 15.90 | 0.92 |
| 4| 6169 | 50.14 | 16.80 | 0.95 |
| 5| 6338 | 62.98 | 21.16 | 1.09 |
| 6| 6665 | 77.20 | 26.08 | 1.26 |
| 7| 6704 | 84.11 | 28.40 | 1.33 |
| 8| 6892 | 87.24 | 29.40 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 10 | 570 | 6174 | 40.13 | 14.67 | 0.85 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

