--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-05 05:32:30.582700129 UTC |
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
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14285 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 40.35 | 11.74 | 0.59 |
| 4 | 225 | 858 | 49.59 | 14.32 | 0.69 |
| 5 | 284 | 969 | 57.59 | 16.63 | 0.78 |
| 6 | 337 | 1081 | 69.92 | 19.98 | 0.91 |
| 7 | 393 | 1192 | 81.19 | 23.16 | 1.03 |
| 8 | 449 | 1303 | 94.47 | 26.69 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1923 | 25.84 | 8.78 | 0.51 |
| 3| 2128 | 28.35 | 10.15 | 0.55 |
| 5| 2338 | 30.45 | 12.07 | 0.59 |
| 10| 3091 | 39.58 | 17.97 | 0.74 |
| 40| 7539 | 96.96 | 53.88 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.80 | 7.38 | 0.41 |
| 2| 831 | 25.49 | 8.78 | 0.46 |
| 3| 900 | 25.82 | 9.55 | 0.47 |
| 5| 1349 | 32.42 | 12.72 | 0.56 |
| 10| 2139 | 42.62 | 18.90 | 0.73 |
| 44| 6821 | 99.90 | 57.52 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.51 | 8.47 | 0.46 |
| 2| 879 | 31.62 | 10.27 | 0.52 |
| 3| 1014 | 31.54 | 10.94 | 0.53 |
| 5| 1293 | 34.90 | 13.21 | 0.58 |
| 10| 1998 | 47.17 | 19.98 | 0.76 |
| 37| 6004 | 96.96 | 51.93 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 891 | 36.56 | 11.60 | 0.57 |
| 3| 951 | 37.91 | 12.62 | 0.59 |
| 5| 1237 | 42.64 | 15.28 | 0.66 |
| 10| 2009 | 53.91 | 21.77 | 0.83 |
| 29| 4901 | 98.13 | 46.76 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5935 | 36.00 | 12.08 | 0.79 |
| 3| 6188 | 46.81 | 15.85 | 0.92 |
| 4| 6330 | 54.74 | 18.46 | 1.00 |
| 5| 6442 | 65.03 | 21.93 | 1.12 |
| 6| 6633 | 74.44 | 25.06 | 1.22 |
| 7| 6611 | 79.35 | 26.67 | 1.27 |
| 8| 6913 | 93.07 | 31.46 | 1.43 |
| 9| 6915 | 98.96 | 33.27 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1137 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1706 | 6853 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |

