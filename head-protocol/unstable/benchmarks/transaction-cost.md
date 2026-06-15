--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-15 11:43:02.498682703 UTC |
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
| 1| 5841 | 10.93 | 3.49 | 0.52 |
| 2| 6038 | 13.18 | 4.20 | 0.55 |
| 3| 6236 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1284 | 6.41 | 3.60 | 0.28 |
| 10| 2165 | 12.13 | 7.25 | 0.40 |
| 54| 10082 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 640 | 34.38 | 9.91 | 0.53 |
| 3 | 170 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 227 | 858 | 48.04 | 13.92 | 0.68 |
| 5 | 281 | 969 | 57.76 | 16.67 | 0.78 |
| 6 | 340 | 1081 | 67.57 | 19.44 | 0.88 |
| 7 | 396 | 1192 | 80.51 | 22.91 | 1.02 |
| 8 | 450 | 1307 | 89.58 | 25.47 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.37 | 7.71 | 0.48 |
| 2| 1956 | 25.43 | 8.68 | 0.50 |
| 3| 2105 | 27.94 | 10.05 | 0.54 |
| 5| 2341 | 30.04 | 11.97 | 0.58 |
| 10| 3100 | 39.45 | 17.93 | 0.73 |
| 40| 7460 | 94.67 | 53.28 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.54 | 7.30 | 0.41 |
| 2| 808 | 25.49 | 8.78 | 0.46 |
| 3| 888 | 25.01 | 9.31 | 0.46 |
| 5| 1206 | 29.01 | 11.75 | 0.52 |
| 10| 2013 | 39.63 | 18.07 | 0.69 |
| 40| 6525 | 96.42 | 53.87 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.54 | 8.47 | 0.46 |
| 2| 829 | 31.54 | 10.26 | 0.52 |
| 3| 902 | 30.15 | 10.52 | 0.51 |
| 5| 1227 | 34.30 | 13.02 | 0.58 |
| 10| 1977 | 44.22 | 19.16 | 0.73 |
| 38| 6031 | 98.33 | 52.98 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 710 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.81 | 11.37 | 0.56 |
| 3| 1011 | 38.59 | 12.82 | 0.60 |
| 5| 1314 | 43.17 | 15.45 | 0.67 |
| 10| 2017 | 53.90 | 21.77 | 0.83 |
| 29| 4744 | 97.06 | 46.41 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.08 | 9.09 | 0.69 |
| 2| 5868 | 35.07 | 11.74 | 0.78 |
| 3| 6019 | 43.79 | 14.67 | 0.87 |
| 4| 6326 | 55.91 | 18.84 | 1.02 |
| 5| 6433 | 65.01 | 21.94 | 1.12 |
| 6| 6622 | 71.30 | 24.09 | 1.19 |
| 7| 6441 | 70.49 | 23.53 | 1.17 |
| 8| 6954 | 93.70 | 31.55 | 1.44 |
| 9| 6804 | 91.65 | 30.74 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1137 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2161 | 7123 | 96.00 | 36.77 | 1.50 |

