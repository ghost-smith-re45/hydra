--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-25 06:42:39.624593564 UTC |
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
| 1| 5836 | 10.69 | 3.40 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6646 | 18.62 | 5.87 | 0.64 |
| 10| 7650 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 41.49 | 11.99 | 0.60 |
| 4 | 227 | 858 | 50.68 | 14.58 | 0.70 |
| 5 | 283 | 969 | 59.37 | 17.08 | 0.80 |
| 6 | 339 | 1081 | 64.82 | 18.80 | 0.86 |
| 7 | 394 | 1196 | 80.54 | 22.91 | 1.02 |
| 8 | 451 | 1307 | 94.89 | 26.90 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.37 | 7.71 | 0.48 |
| 2| 1923 | 25.84 | 8.78 | 0.51 |
| 3| 2109 | 28.38 | 10.16 | 0.55 |
| 5| 2322 | 29.89 | 11.93 | 0.58 |
| 10| 3170 | 41.22 | 18.41 | 0.76 |
| 39| 7400 | 94.45 | 52.60 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 697 | 22.62 | 7.95 | 0.42 |
| 3| 894 | 25.12 | 9.34 | 0.46 |
| 5| 1194 | 30.08 | 12.07 | 0.53 |
| 10| 1838 | 35.45 | 16.88 | 0.64 |
| 42| 6653 | 98.69 | 55.80 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 972 | 30.82 | 10.73 | 0.52 |
| 5| 1386 | 38.29 | 14.17 | 0.62 |
| 10| 2066 | 45.34 | 19.52 | 0.75 |
| 34| 5614 | 98.00 | 50.21 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 814 | 35.89 | 11.39 | 0.56 |
| 3| 938 | 37.87 | 12.61 | 0.59 |
| 5| 1293 | 43.02 | 15.39 | 0.67 |
| 10| 1859 | 51.92 | 21.16 | 0.80 |
| 29| 4805 | 97.99 | 46.67 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.09 | 9.09 | 0.69 |
| 2| 5893 | 34.87 | 11.67 | 0.78 |
| 3| 6121 | 45.00 | 15.11 | 0.89 |
| 4| 6308 | 55.03 | 18.52 | 1.01 |
| 5| 6520 | 66.09 | 22.36 | 1.13 |
| 6| 6723 | 76.51 | 25.87 | 1.25 |
| 7| 6791 | 82.87 | 27.93 | 1.32 |
| 8| 6873 | 90.30 | 30.49 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1138 | 6512 | 58.40 | 21.99 | 1.07 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2280 | 7197 | 99.84 | 38.30 | 1.55 |
| 10 | 39 | 2221 | 7160 | 97.61 | 37.43 | 1.52 |

