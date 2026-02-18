--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-18 05:39:20.904417102 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.60 | 5.87 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 39.81 | 11.57 | 0.59 |
| 4 | 226 | 858 | 51.14 | 14.69 | 0.71 |
| 5 | 283 | 969 | 59.59 | 17.14 | 0.80 |
| 6 | 341 | 1081 | 71.46 | 20.38 | 0.92 |
| 7 | 394 | 1192 | 73.63 | 21.25 | 0.95 |
| 8 | 450 | 1303 | 86.74 | 24.84 | 1.09 |
| 10 | 561 | 1525 | 97.92 | 28.38 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 23.92 | 7.60 | 0.48 |
| 2| 1955 | 25.89 | 8.79 | 0.51 |
| 3| 2129 | 28.51 | 10.19 | 0.55 |
| 5| 2413 | 31.34 | 12.32 | 0.60 |
| 10| 3149 | 40.74 | 18.29 | 0.75 |
| 42| 7818 | 99.40 | 55.98 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 630 | 22.81 | 7.37 | 0.42 |
| 2| 769 | 24.28 | 8.45 | 0.44 |
| 3| 917 | 25.14 | 9.33 | 0.46 |
| 5| 1241 | 29.95 | 12.03 | 0.53 |
| 10| 2060 | 42.22 | 18.79 | 0.72 |
| 42| 6723 | 98.08 | 55.67 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 27.50 | 8.46 | 0.46 |
| 2| 874 | 29.97 | 9.84 | 0.50 |
| 3| 930 | 32.64 | 11.21 | 0.54 |
| 5| 1257 | 34.97 | 13.23 | 0.58 |
| 10| 2040 | 47.66 | 20.11 | 0.77 |
| 36| 5856 | 95.16 | 50.78 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.83 | 10.15 | 0.53 |
| 2| 865 | 36.56 | 11.60 | 0.57 |
| 3| 995 | 38.55 | 12.81 | 0.60 |
| 5| 1317 | 43.20 | 15.45 | 0.67 |
| 10| 1979 | 53.39 | 21.60 | 0.82 |
| 28| 4981 | 99.30 | 46.49 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.00 | 9.09 | 0.69 |
| 2| 5916 | 34.83 | 11.65 | 0.78 |
| 3| 6056 | 44.98 | 15.11 | 0.89 |
| 4| 6219 | 55.18 | 18.54 | 1.00 |
| 5| 6310 | 59.38 | 19.94 | 1.05 |
| 6| 6523 | 66.96 | 22.52 | 1.14 |
| 7| 6688 | 79.44 | 26.75 | 1.28 |
| 8| 6990 | 91.97 | 31.09 | 1.42 |
| 9| 6990 | 98.95 | 33.28 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2222 | 7162 | 98.05 | 37.58 | 1.53 |

