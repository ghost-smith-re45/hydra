--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-02 11:37:26.287242987 UTC |
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
| 1| 5834 | 10.66 | 3.39 | 0.52 |
| 2| 6037 | 13.16 | 4.19 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.30 | 9.40 | 0.51 |
| 3 | 169 | 751 | 40.17 | 11.66 | 0.59 |
| 4 | 225 | 858 | 47.48 | 13.79 | 0.67 |
| 5 | 282 | 969 | 59.41 | 17.06 | 0.80 |
| 6 | 337 | 1081 | 70.66 | 20.27 | 0.91 |
| 7 | 393 | 1192 | 83.68 | 23.61 | 1.05 |
| 8 | 449 | 1303 | 86.11 | 24.84 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.85 | 8.50 | 0.50 |
| 3| 2011 | 25.95 | 9.49 | 0.52 |
| 5| 2446 | 32.04 | 12.53 | 0.61 |
| 10| 3105 | 41.08 | 18.37 | 0.75 |
| 40| 7474 | 94.62 | 53.25 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.81 | 7.37 | 0.42 |
| 2| 797 | 25.16 | 8.69 | 0.45 |
| 3| 925 | 25.10 | 9.32 | 0.46 |
| 5| 1228 | 29.04 | 11.76 | 0.52 |
| 10| 2093 | 42.31 | 18.79 | 0.72 |
| 40| 6312 | 93.18 | 52.91 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 27.54 | 8.47 | 0.46 |
| 2| 884 | 29.93 | 9.83 | 0.50 |
| 3| 868 | 31.97 | 11.00 | 0.53 |
| 5| 1263 | 35.05 | 13.25 | 0.58 |
| 10| 2065 | 45.01 | 19.40 | 0.74 |
| 34| 5692 | 99.65 | 50.68 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.87 | 10.16 | 0.53 |
| 2| 803 | 35.88 | 11.39 | 0.56 |
| 3| 1021 | 39.26 | 13.03 | 0.61 |
| 5| 1295 | 43.40 | 15.50 | 0.67 |
| 10| 2117 | 55.24 | 22.18 | 0.85 |
| 30| 4983 | 99.30 | 47.70 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.96 | 9.05 | 0.69 |
| 2| 5870 | 34.99 | 11.71 | 0.78 |
| 3| 6085 | 44.91 | 15.08 | 0.89 |
| 4| 6283 | 54.17 | 18.28 | 1.00 |
| 5| 6382 | 62.97 | 21.16 | 1.09 |
| 6| 6576 | 71.53 | 24.08 | 1.19 |
| 7| 6739 | 79.61 | 26.72 | 1.28 |
| 8| 6862 | 92.61 | 31.19 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

