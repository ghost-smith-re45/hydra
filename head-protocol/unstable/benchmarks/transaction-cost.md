--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-21 07:20:37.451597056 UTC |
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
| 1| 5841 | 10.48 | 3.33 | 0.52 |
| 2| 6037 | 12.80 | 4.07 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 40.40 | 11.75 | 0.59 |
| 4 | 227 | 858 | 53.39 | 15.21 | 0.73 |
| 5 | 283 | 974 | 59.23 | 17.02 | 0.79 |
| 6 | 338 | 1081 | 64.05 | 18.53 | 0.85 |
| 7 | 395 | 1196 | 86.76 | 24.45 | 1.08 |
| 8 | 450 | 1307 | 84.90 | 24.35 | 1.07 |
| 9 | 505 | 1414 | 88.54 | 25.61 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1925 | 25.85 | 8.78 | 0.51 |
| 3| 2123 | 27.97 | 10.06 | 0.54 |
| 5| 2457 | 32.00 | 12.52 | 0.61 |
| 10| 3190 | 41.82 | 18.59 | 0.76 |
| 41| 7502 | 95.27 | 54.11 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.54 | 7.30 | 0.41 |
| 2| 763 | 24.32 | 8.46 | 0.44 |
| 3| 964 | 26.95 | 9.86 | 0.48 |
| 5| 1300 | 32.38 | 12.70 | 0.56 |
| 10| 2201 | 44.10 | 19.33 | 0.74 |
| 38| 6232 | 94.69 | 52.02 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 29.13 | 8.90 | 0.48 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 970 | 30.98 | 10.76 | 0.52 |
| 5| 1296 | 35.72 | 13.46 | 0.59 |
| 10| 2214 | 50.37 | 20.92 | 0.81 |
| 37| 6057 | 98.11 | 52.31 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 997 | 38.47 | 12.79 | 0.60 |
| 5| 1202 | 41.89 | 15.05 | 0.65 |
| 10| 1900 | 52.70 | 21.39 | 0.81 |
| 28| 4692 | 95.26 | 45.29 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.05 | 9.07 | 0.69 |
| 2| 5937 | 36.04 | 12.10 | 0.79 |
| 3| 6064 | 43.95 | 14.73 | 0.88 |
| 4| 6162 | 49.97 | 16.76 | 0.95 |
| 5| 6388 | 60.57 | 20.36 | 1.07 |
| 6| 6599 | 74.32 | 25.00 | 1.22 |
| 7| 6706 | 79.77 | 26.84 | 1.28 |
| 8| 6494 | 75.96 | 25.30 | 1.23 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6005 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 568 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 30 | 1706 | 6852 | 78.27 | 29.85 | 1.30 |
| 10 | 39 | 2221 | 7160 | 99.56 | 38.10 | 1.54 |

