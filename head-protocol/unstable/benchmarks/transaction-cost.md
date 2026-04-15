--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-15 07:18:00.358003406 UTC |
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
| 1| 5836 | 10.66 | 3.39 | 0.52 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6242 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 19.08 | 6.04 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 41.18 | 11.91 | 0.60 |
| 4 | 227 | 858 | 54.10 | 15.43 | 0.74 |
| 5 | 285 | 969 | 56.22 | 16.33 | 0.76 |
| 6 | 340 | 1081 | 68.27 | 19.62 | 0.89 |
| 7 | 393 | 1192 | 84.36 | 23.87 | 1.06 |
| 8 | 449 | 1303 | 88.88 | 25.30 | 1.11 |
| 9 | 505 | 1414 | 99.44 | 28.51 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 23.92 | 7.60 | 0.48 |
| 2| 2007 | 26.91 | 9.08 | 0.52 |
| 3| 2124 | 28.31 | 10.14 | 0.55 |
| 5| 2316 | 30.16 | 12.00 | 0.58 |
| 10| 3176 | 41.11 | 18.40 | 0.75 |
| 41| 7736 | 98.38 | 54.99 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.54 | 7.30 | 0.41 |
| 2| 700 | 22.58 | 7.96 | 0.42 |
| 3| 884 | 25.58 | 9.50 | 0.46 |
| 5| 1166 | 28.16 | 11.51 | 0.51 |
| 10| 2099 | 40.59 | 18.33 | 0.70 |
| 40| 6637 | 97.01 | 54.03 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.13 | 8.90 | 0.48 |
| 2| 815 | 29.22 | 9.61 | 0.49 |
| 3| 962 | 30.90 | 10.74 | 0.52 |
| 5| 1244 | 36.95 | 13.76 | 0.60 |
| 10| 2031 | 44.60 | 19.27 | 0.74 |
| 36| 5740 | 94.51 | 50.56 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.87 | 10.16 | 0.53 |
| 2| 874 | 36.56 | 11.60 | 0.57 |
| 3| 950 | 37.80 | 12.59 | 0.59 |
| 5| 1254 | 42.57 | 15.26 | 0.66 |
| 10| 1906 | 52.67 | 21.38 | 0.81 |
| 27| 4525 | 93.03 | 43.97 | 1.42 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 26.97 | 9.05 | 0.69 |
| 2| 5981 | 36.77 | 12.41 | 0.80 |
| 3| 6060 | 44.88 | 15.08 | 0.89 |
| 4| 6237 | 55.17 | 18.59 | 1.00 |
| 5| 6435 | 63.96 | 21.57 | 1.11 |
| 6| 6584 | 73.27 | 24.68 | 1.21 |
| 7| 6692 | 83.37 | 28.12 | 1.32 |
| 8| 7013 | 91.77 | 30.97 | 1.42 |
| 9| 6948 | 98.15 | 33.08 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 283 | 6003 | 28.21 | 10.04 | 0.71 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.68 | 37.80 | 1.54 |

