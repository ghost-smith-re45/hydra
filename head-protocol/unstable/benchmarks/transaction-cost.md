--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-21 04:59:56.305615484 UTC |
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
| 2| 6042 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14279 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1272 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 751 | 43.83 | 12.55 | 0.63 |
| 4 | 228 | 858 | 50.54 | 14.52 | 0.70 |
| 5 | 283 | 974 | 62.81 | 17.91 | 0.83 |
| 6 | 337 | 1081 | 67.89 | 19.49 | 0.89 |
| 7 | 396 | 1196 | 71.87 | 20.83 | 0.93 |
| 8 | 450 | 1303 | 91.34 | 25.94 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1788 | 24.00 | 7.62 | 0.48 |
| 2| 1927 | 25.88 | 8.79 | 0.51 |
| 3| 2013 | 26.28 | 9.57 | 0.52 |
| 5| 2365 | 31.40 | 12.34 | 0.60 |
| 10| 3207 | 42.00 | 18.65 | 0.77 |
| 38| 7195 | 93.25 | 51.55 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 22.54 | 7.30 | 0.41 |
| 2| 727 | 22.56 | 7.94 | 0.42 |
| 3| 897 | 25.79 | 9.53 | 0.47 |
| 5| 1136 | 27.99 | 11.46 | 0.51 |
| 10| 1935 | 37.66 | 17.50 | 0.67 |
| 41| 6505 | 96.85 | 54.63 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 29.13 | 8.90 | 0.48 |
| 2| 828 | 29.26 | 9.62 | 0.49 |
| 3| 869 | 32.08 | 11.03 | 0.53 |
| 5| 1301 | 35.68 | 13.45 | 0.59 |
| 10| 1939 | 43.52 | 18.94 | 0.72 |
| 36| 5805 | 99.79 | 51.99 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.15 | 0.53 |
| 2| 832 | 35.89 | 11.39 | 0.56 |
| 3| 957 | 37.87 | 12.61 | 0.59 |
| 5| 1241 | 42.57 | 15.26 | 0.66 |
| 10| 2190 | 55.77 | 22.33 | 0.86 |
| 30| 4971 | 99.40 | 47.74 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 26.97 | 9.07 | 0.69 |
| 2| 5869 | 32.57 | 10.87 | 0.75 |
| 3| 6089 | 44.76 | 15.04 | 0.89 |
| 4| 6296 | 54.82 | 18.46 | 1.00 |
| 5| 6509 | 66.31 | 22.41 | 1.13 |
| 6| 6519 | 70.52 | 23.77 | 1.18 |
| 7| 6647 | 78.40 | 26.45 | 1.27 |
| 8| 6733 | 88.32 | 29.67 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6175 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2216 | 7155 | 99.38 | 38.03 | 1.54 |

