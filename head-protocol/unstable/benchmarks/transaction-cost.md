--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-12 04:38:58.284912863 UTC |
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
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.52 | 5.84 | 0.63 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10083 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 169 | 747 | 39.82 | 11.57 | 0.59 |
| 4 | 227 | 858 | 51.15 | 14.70 | 0.71 |
| 5 | 284 | 969 | 61.03 | 17.48 | 0.81 |
| 6 | 340 | 1081 | 66.07 | 19.02 | 0.87 |
| 7 | 394 | 1192 | 86.99 | 24.50 | 1.08 |
| 8 | 451 | 1303 | 85.05 | 24.38 | 1.07 |
| 9 | 506 | 1414 | 91.38 | 26.30 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.00 | 7.62 | 0.48 |
| 2| 1929 | 25.84 | 8.78 | 0.51 |
| 3| 2066 | 27.32 | 9.86 | 0.53 |
| 5| 2530 | 32.91 | 12.78 | 0.62 |
| 10| 3235 | 41.30 | 18.46 | 0.76 |
| 39| 7377 | 94.67 | 52.61 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.80 | 7.36 | 0.41 |
| 2| 815 | 25.49 | 8.78 | 0.46 |
| 3| 854 | 24.07 | 9.03 | 0.45 |
| 5| 1257 | 31.37 | 12.42 | 0.55 |
| 10| 1889 | 37.47 | 17.44 | 0.66 |
| 40| 6618 | 99.96 | 54.83 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.51 | 8.47 | 0.46 |
| 2| 874 | 29.86 | 9.81 | 0.50 |
| 3| 1006 | 31.69 | 10.98 | 0.53 |
| 5| 1281 | 37.69 | 13.98 | 0.61 |
| 10| 1927 | 46.54 | 19.78 | 0.75 |
| 36| 5784 | 96.59 | 51.16 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.79 | 10.15 | 0.53 |
| 2| 826 | 35.81 | 11.37 | 0.56 |
| 3| 940 | 37.95 | 12.63 | 0.59 |
| 5| 1200 | 41.90 | 15.05 | 0.65 |
| 10| 2082 | 54.84 | 22.04 | 0.84 |
| 30| 4829 | 97.91 | 47.29 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5894 | 34.87 | 11.66 | 0.78 |
| 3| 6109 | 44.43 | 14.95 | 0.89 |
| 4| 6321 | 55.98 | 18.90 | 1.02 |
| 5| 6574 | 66.27 | 22.40 | 1.14 |
| 6| 6721 | 75.04 | 25.30 | 1.23 |
| 7| 6693 | 83.65 | 28.16 | 1.32 |
| 8| 6817 | 86.50 | 29.06 | 1.36 |
| 9| 6834 | 94.11 | 31.60 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 20 | 1140 | 6515 | 59.98 | 22.53 | 1.08 |
| 10 | 37 | 2102 | 7087 | 93.95 | 35.96 | 1.48 |

