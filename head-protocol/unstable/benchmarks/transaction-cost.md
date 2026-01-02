--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-02 04:56:45.097516846 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 19.00 | 6.01 | 0.64 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.38 | 9.43 | 0.51 |
| 3 | 171 | 747 | 43.88 | 12.56 | 0.63 |
| 4 | 228 | 858 | 49.96 | 14.46 | 0.70 |
| 5 | 283 | 969 | 55.98 | 16.24 | 0.76 |
| 6 | 337 | 1081 | 68.14 | 19.59 | 0.89 |
| 7 | 394 | 1192 | 79.06 | 22.65 | 1.00 |
| 8 | 450 | 1303 | 91.26 | 25.87 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 23.92 | 7.60 | 0.48 |
| 2| 1922 | 25.76 | 8.76 | 0.51 |
| 3| 2080 | 27.39 | 9.88 | 0.53 |
| 5| 2421 | 32.40 | 12.62 | 0.61 |
| 10| 3126 | 40.26 | 18.15 | 0.74 |
| 39| 7527 | 98.02 | 53.51 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.57 | 7.31 | 0.41 |
| 2| 743 | 24.35 | 8.47 | 0.44 |
| 3| 942 | 26.57 | 9.76 | 0.48 |
| 5| 1269 | 30.09 | 12.07 | 0.54 |
| 10| 2068 | 40.55 | 18.34 | 0.70 |
| 40| 6392 | 94.58 | 53.33 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 27.54 | 8.47 | 0.46 |
| 2| 812 | 29.26 | 9.62 | 0.49 |
| 3| 984 | 33.40 | 11.43 | 0.55 |
| 5| 1289 | 37.85 | 14.02 | 0.61 |
| 10| 2074 | 45.38 | 19.52 | 0.75 |
| 38| 6188 | 99.86 | 53.46 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.92 | 11.40 | 0.56 |
| 3| 896 | 37.16 | 12.39 | 0.58 |
| 5| 1299 | 42.65 | 15.28 | 0.66 |
| 10| 1864 | 51.96 | 21.17 | 0.80 |
| 29| 5069 | 99.12 | 47.06 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5796 | 27.09 | 9.09 | 0.69 |
| 2| 5940 | 36.07 | 12.11 | 0.79 |
| 3| 6109 | 44.70 | 15.03 | 0.89 |
| 4| 6306 | 55.36 | 18.67 | 1.01 |
| 5| 6532 | 66.16 | 22.35 | 1.13 |
| 6| 6505 | 69.81 | 23.45 | 1.17 |
| 7| 6648 | 82.64 | 27.83 | 1.31 |
| 8| 6804 | 85.99 | 28.91 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 56 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7157 | 99.12 | 37.95 | 1.54 |

