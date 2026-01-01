--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-01 05:04:32.750230031 UTC |
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
| 1| 5834 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.40 | 4.55 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1284 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 41.51 | 12.00 | 0.60 |
| 4 | 227 | 858 | 51.15 | 14.70 | 0.71 |
| 5 | 283 | 969 | 62.78 | 17.90 | 0.83 |
| 6 | 338 | 1081 | 64.05 | 18.53 | 0.85 |
| 7 | 397 | 1192 | 86.40 | 24.27 | 1.08 |
| 8 | 451 | 1307 | 87.50 | 25.12 | 1.10 |
| 9 | 506 | 1414 | 92.51 | 26.79 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1883 | 24.40 | 8.39 | 0.49 |
| 3| 2081 | 27.39 | 9.88 | 0.53 |
| 5| 2439 | 31.96 | 12.51 | 0.61 |
| 10| 3139 | 40.89 | 18.33 | 0.75 |
| 42| 7801 | 99.58 | 55.99 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.84 | 7.39 | 0.41 |
| 2| 769 | 24.31 | 8.47 | 0.44 |
| 3| 853 | 24.11 | 9.04 | 0.45 |
| 5| 1204 | 29.00 | 11.75 | 0.52 |
| 10| 1961 | 38.72 | 17.79 | 0.68 |
| 41| 6628 | 97.62 | 54.88 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 881 | 29.93 | 9.83 | 0.50 |
| 3| 906 | 32.80 | 11.25 | 0.54 |
| 5| 1355 | 36.40 | 13.66 | 0.60 |
| 10| 1947 | 46.65 | 19.81 | 0.76 |
| 37| 6124 | 99.57 | 52.73 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 825 | 35.89 | 11.39 | 0.56 |
| 3| 1004 | 38.58 | 12.82 | 0.60 |
| 5| 1261 | 42.61 | 15.27 | 0.66 |
| 10| 2194 | 56.01 | 22.41 | 0.86 |
| 29| 4829 | 98.06 | 46.70 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 26.97 | 9.07 | 0.69 |
| 2| 5965 | 37.13 | 12.50 | 0.80 |
| 3| 6092 | 46.02 | 15.51 | 0.90 |
| 4| 6235 | 53.91 | 18.12 | 0.99 |
| 5| 6449 | 63.66 | 21.49 | 1.10 |
| 6| 6510 | 70.01 | 23.59 | 1.17 |
| 7| 6858 | 85.34 | 28.83 | 1.35 |
| 8| 6889 | 90.28 | 30.51 | 1.40 |
| 9| 6848 | 99.87 | 33.61 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 40 | 2276 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2217 | 7157 | 98.24 | 37.65 | 1.53 |

