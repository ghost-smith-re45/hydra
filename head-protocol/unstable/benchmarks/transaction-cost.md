--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-28 07:59:11.992939165 UTC |
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
| 1| 5837 | 10.48 | 3.33 | 0.52 |
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.91 | 5.98 | 0.64 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14283 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 43.76 | 12.53 | 0.63 |
| 4 | 225 | 862 | 51.00 | 14.66 | 0.71 |
| 5 | 283 | 969 | 55.95 | 16.20 | 0.76 |
| 6 | 338 | 1081 | 64.59 | 18.78 | 0.86 |
| 7 | 394 | 1192 | 74.47 | 21.46 | 0.96 |
| 8 | 449 | 1303 | 80.77 | 23.41 | 1.03 |
| 9 | 506 | 1418 | 98.34 | 27.96 | 1.21 |
| 10 | 560 | 1525 | 98.21 | 28.52 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.00 | 7.62 | 0.48 |
| 2| 1925 | 25.39 | 8.68 | 0.50 |
| 3| 2054 | 26.95 | 9.77 | 0.53 |
| 5| 2276 | 29.34 | 11.76 | 0.57 |
| 10| 3198 | 42.19 | 18.68 | 0.77 |
| 42| 7663 | 97.13 | 55.30 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.53 | 7.30 | 0.41 |
| 2| 741 | 23.61 | 8.24 | 0.43 |
| 3| 942 | 27.10 | 9.91 | 0.48 |
| 5| 1214 | 30.10 | 12.06 | 0.53 |
| 10| 1964 | 39.34 | 17.99 | 0.68 |
| 44| 6716 | 97.43 | 56.81 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.47 | 8.46 | 0.46 |
| 2| 854 | 29.90 | 9.82 | 0.50 |
| 3| 1005 | 31.61 | 10.96 | 0.53 |
| 5| 1295 | 37.77 | 14.00 | 0.61 |
| 10| 2023 | 47.55 | 20.07 | 0.77 |
| 34| 5826 | 99.64 | 50.70 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.83 | 10.16 | 0.53 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 1004 | 38.55 | 12.81 | 0.60 |
| 5| 1409 | 43.87 | 15.66 | 0.68 |
| 10| 1917 | 52.53 | 21.35 | 0.81 |
| 29| 4890 | 97.76 | 46.65 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.08 | 0.69 |
| 2| 5866 | 32.41 | 10.83 | 0.75 |
| 3| 6067 | 44.80 | 15.07 | 0.89 |
| 4| 6337 | 54.85 | 18.48 | 1.01 |
| 5| 6500 | 64.96 | 21.90 | 1.12 |
| 6| 6466 | 73.79 | 24.83 | 1.21 |
| 7| 6721 | 82.84 | 27.95 | 1.32 |
| 8| 6812 | 86.75 | 29.13 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7157 | 99.38 | 38.04 | 1.54 |

