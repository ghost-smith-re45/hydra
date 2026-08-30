--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-30 11:04:24.255195914 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6042 | 12.25 | 3.87 | 0.54 |
| 3| 6242 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.09 | 9.17 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 41.20 | 11.90 | 0.60 |
| 4 | 226 | 858 | 47.89 | 13.89 | 0.68 |
| 5 | 281 | 969 | 62.88 | 17.99 | 0.83 |
| 6 | 336 | 1081 | 68.28 | 19.62 | 0.89 |
| 7 | 393 | 1192 | 80.08 | 22.80 | 1.01 |
| 8 | 450 | 1307 | 93.91 | 26.60 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1880 | 24.80 | 8.49 | 0.49 |
| 3| 2012 | 25.87 | 9.47 | 0.52 |
| 5| 2505 | 33.14 | 12.84 | 0.62 |
| 10| 3294 | 43.64 | 19.13 | 0.79 |
| 38| 7384 | 96.91 | 52.58 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.81 | 7.37 | 0.42 |
| 2| 805 | 25.43 | 8.78 | 0.45 |
| 3| 901 | 25.09 | 9.33 | 0.46 |
| 5| 1330 | 31.87 | 12.57 | 0.56 |
| 10| 2092 | 41.54 | 18.62 | 0.71 |
| 40| 6621 | 99.44 | 54.70 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.13 | 8.90 | 0.48 |
| 2| 803 | 30.98 | 10.08 | 0.51 |
| 3| 955 | 30.90 | 10.74 | 0.52 |
| 5| 1189 | 36.27 | 13.55 | 0.59 |
| 10| 2110 | 46.25 | 19.78 | 0.76 |
| 35| 5799 | 94.93 | 50.07 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 952 | 37.95 | 12.63 | 0.59 |
| 5| 1200 | 41.97 | 15.07 | 0.65 |
| 10| 1915 | 52.67 | 21.38 | 0.81 |
| 30| 4887 | 98.88 | 47.55 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 26.96 | 9.06 | 0.69 |
| 2| 5981 | 36.96 | 12.46 | 0.80 |
| 3| 6024 | 41.28 | 13.82 | 0.85 |
| 4| 6167 | 52.41 | 17.61 | 0.97 |
| 5| 6389 | 63.41 | 21.34 | 1.10 |
| 6| 6515 | 71.12 | 23.91 | 1.18 |
| 7| 6738 | 80.36 | 27.08 | 1.29 |
| 8| 6864 | 94.26 | 31.82 | 1.44 |
| 9| 6993 | 98.34 | 33.03 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6005 | 27.58 | 9.82 | 0.71 |
| 10 | 20 | 1138 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2281 | 7198 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

