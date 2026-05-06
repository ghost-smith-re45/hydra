--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-06 07:37:19.4721303 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.34 | 3.90 | 0.54 |
| 3| 6243 | 15.07 | 4.78 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.47 | 9.30 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 747 | 42.57 | 12.25 | 0.62 |
| 4 | 225 | 858 | 51.18 | 14.73 | 0.71 |
| 5 | 283 | 969 | 61.39 | 17.60 | 0.82 |
| 6 | 339 | 1081 | 64.55 | 18.76 | 0.85 |
| 7 | 392 | 1192 | 75.21 | 21.77 | 0.97 |
| 8 | 448 | 1303 | 84.75 | 24.31 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 23.30 | 7.41 | 0.47 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2111 | 28.13 | 10.10 | 0.54 |
| 5| 2457 | 32.49 | 12.64 | 0.61 |
| 10| 3215 | 42.89 | 18.89 | 0.77 |
| 41| 7659 | 97.80 | 54.80 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 603 | 22.84 | 7.39 | 0.41 |
| 2| 857 | 25.41 | 8.76 | 0.46 |
| 3| 899 | 25.82 | 9.55 | 0.47 |
| 5| 1369 | 32.51 | 12.73 | 0.57 |
| 10| 2044 | 39.49 | 18.02 | 0.69 |
| 40| 6425 | 94.87 | 53.43 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 29.17 | 8.91 | 0.48 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 1000 | 33.40 | 11.43 | 0.55 |
| 5| 1268 | 37.70 | 13.98 | 0.61 |
| 10| 2039 | 45.61 | 19.58 | 0.75 |
| 35| 5803 | 96.07 | 50.39 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 900 | 37.24 | 12.41 | 0.58 |
| 5| 1260 | 42.65 | 15.28 | 0.66 |
| 10| 1963 | 53.24 | 21.56 | 0.82 |
| 31| 5000 | 99.91 | 48.52 | 1.53 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 6022 | 36.81 | 12.41 | 0.80 |
| 3| 6084 | 44.92 | 15.08 | 0.89 |
| 4| 6381 | 55.97 | 18.92 | 1.02 |
| 5| 6398 | 61.73 | 20.82 | 1.08 |
| 6| 6715 | 75.68 | 25.59 | 1.24 |
| 7| 6866 | 87.75 | 29.69 | 1.38 |
| 8| 6845 | 91.45 | 30.86 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2222 | 7162 | 99.12 | 37.95 | 1.54 |

