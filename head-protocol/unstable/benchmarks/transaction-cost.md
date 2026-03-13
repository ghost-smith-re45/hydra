--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-13 06:34:01.20589377 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.69 | 4.65 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 169 | 747 | 42.53 | 12.22 | 0.61 |
| 4 | 227 | 858 | 54.04 | 15.41 | 0.74 |
| 5 | 281 | 969 | 64.55 | 18.36 | 0.85 |
| 6 | 340 | 1081 | 64.15 | 18.55 | 0.85 |
| 7 | 393 | 1192 | 76.88 | 22.08 | 0.98 |
| 8 | 450 | 1307 | 85.05 | 24.48 | 1.07 |
| 9 | 506 | 1414 | 90.29 | 26.26 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.00 | 7.62 | 0.48 |
| 2| 1923 | 25.39 | 8.68 | 0.50 |
| 3| 2056 | 26.86 | 9.75 | 0.53 |
| 5| 2328 | 30.04 | 11.97 | 0.58 |
| 10| 3233 | 42.84 | 18.88 | 0.77 |
| 39| 7416 | 96.55 | 53.10 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 22.77 | 7.37 | 0.42 |
| 2| 764 | 23.59 | 8.23 | 0.43 |
| 3| 875 | 25.58 | 9.50 | 0.46 |
| 5| 1268 | 30.56 | 12.21 | 0.54 |
| 10| 1955 | 38.43 | 17.72 | 0.67 |
| 42| 6438 | 94.32 | 54.60 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 29.13 | 8.90 | 0.48 |
| 2| 844 | 29.15 | 9.59 | 0.49 |
| 3| 1010 | 31.61 | 10.96 | 0.53 |
| 5| 1296 | 35.01 | 13.24 | 0.59 |
| 10| 2035 | 44.89 | 19.36 | 0.74 |
| 37| 6092 | 97.87 | 52.25 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 33.79 | 10.15 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1259 | 42.57 | 15.26 | 0.66 |
| 10| 2094 | 54.61 | 21.98 | 0.84 |
| 28| 4839 | 98.92 | 46.34 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 26.97 | 9.07 | 0.69 |
| 2| 6029 | 36.98 | 12.46 | 0.80 |
| 3| 6042 | 43.52 | 14.60 | 0.87 |
| 4| 6329 | 56.13 | 18.96 | 1.02 |
| 5| 6308 | 59.70 | 20.03 | 1.05 |
| 6| 6658 | 73.90 | 24.88 | 1.22 |
| 7| 6639 | 79.14 | 26.58 | 1.27 |
| 8| 6906 | 93.38 | 31.46 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.68 | 6.24 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 568 | 6172 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1706 | 6852 | 81.11 | 30.83 | 1.33 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

