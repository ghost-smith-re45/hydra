--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-01 05:38:30.706993273 UTC |
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
| 1| 5841 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 42.34 | 12.17 | 0.61 |
| 4 | 227 | 862 | 53.38 | 15.23 | 0.73 |
| 5 | 283 | 969 | 62.14 | 17.68 | 0.82 |
| 6 | 339 | 1081 | 66.47 | 19.19 | 0.87 |
| 7 | 394 | 1196 | 81.58 | 23.15 | 1.03 |
| 8 | 449 | 1303 | 85.70 | 24.64 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.00 | 7.62 | 0.48 |
| 2| 1973 | 26.55 | 9.00 | 0.52 |
| 3| 2162 | 29.47 | 10.46 | 0.56 |
| 5| 2424 | 32.48 | 12.64 | 0.61 |
| 10| 3125 | 40.45 | 18.20 | 0.75 |
| 38| 7628 | 98.61 | 53.05 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.57 | 7.31 | 0.41 |
| 2| 699 | 22.58 | 7.96 | 0.42 |
| 3| 970 | 26.68 | 9.79 | 0.48 |
| 5| 1309 | 30.04 | 12.04 | 0.54 |
| 10| 2135 | 43.68 | 19.17 | 0.74 |
| 41| 6706 | 98.80 | 55.15 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.50 | 8.46 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 954 | 33.39 | 11.43 | 0.54 |
| 5| 1293 | 35.80 | 13.48 | 0.59 |
| 10| 2182 | 50.56 | 20.99 | 0.81 |
| 34| 5511 | 90.66 | 48.19 | 1.47 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 33.15 | 9.95 | 0.52 |
| 2| 819 | 35.88 | 11.39 | 0.56 |
| 3| 1004 | 38.55 | 12.81 | 0.60 |
| 5| 1242 | 42.64 | 15.28 | 0.66 |
| 10| 2129 | 55.71 | 22.30 | 0.85 |
| 29| 4703 | 96.53 | 46.23 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 26.97 | 9.06 | 0.69 |
| 2| 5917 | 34.83 | 11.66 | 0.78 |
| 3| 6135 | 45.93 | 15.49 | 0.90 |
| 4| 6403 | 56.91 | 19.29 | 1.03 |
| 5| 6307 | 60.25 | 20.21 | 1.06 |
| 6| 6524 | 73.19 | 24.63 | 1.21 |
| 7| 6757 | 81.07 | 27.26 | 1.30 |
| 8| 6797 | 86.40 | 29.12 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 10 | 569 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1140 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2223 | 7163 | 98.05 | 37.58 | 1.53 |

