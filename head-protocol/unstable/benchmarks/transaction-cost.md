--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-20 05:00:06.945204471 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6041 | 12.72 | 4.03 | 0.55 |
| 3| 6240 | 14.48 | 4.58 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.57 | 9.34 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.73 | 12.51 | 0.63 |
| 4 | 227 | 858 | 52.10 | 14.92 | 0.72 |
| 5 | 283 | 969 | 57.53 | 16.58 | 0.78 |
| 6 | 337 | 1085 | 65.75 | 19.04 | 0.87 |
| 7 | 396 | 1192 | 72.26 | 20.89 | 0.94 |
| 8 | 450 | 1303 | 84.27 | 24.19 | 1.06 |
| 9 | 506 | 1414 | 88.29 | 25.61 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1989 | 26.47 | 8.98 | 0.52 |
| 3| 2056 | 26.94 | 9.77 | 0.53 |
| 5| 2332 | 30.20 | 12.01 | 0.58 |
| 10| 3057 | 40.11 | 18.10 | 0.74 |
| 40| 7587 | 98.68 | 54.38 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.80 | 7.36 | 0.41 |
| 2| 770 | 24.01 | 8.38 | 0.44 |
| 3| 945 | 26.61 | 9.77 | 0.48 |
| 5| 1252 | 30.25 | 12.11 | 0.54 |
| 10| 1915 | 36.78 | 17.26 | 0.66 |
| 43| 6657 | 96.23 | 55.81 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 711 | 27.51 | 8.47 | 0.46 |
| 2| 817 | 29.18 | 9.60 | 0.49 |
| 3| 978 | 30.94 | 10.75 | 0.52 |
| 5| 1168 | 36.35 | 13.57 | 0.59 |
| 10| 2010 | 48.06 | 20.23 | 0.77 |
| 36| 5956 | 96.19 | 51.10 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.83 | 10.16 | 0.53 |
| 2| 813 | 35.85 | 11.38 | 0.56 |
| 3| 944 | 37.95 | 12.63 | 0.59 |
| 5| 1199 | 41.89 | 15.05 | 0.65 |
| 10| 2303 | 57.47 | 22.85 | 0.88 |
| 30| 4953 | 98.72 | 47.53 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.09 | 9.08 | 0.69 |
| 2| 5904 | 36.01 | 12.08 | 0.79 |
| 3| 6093 | 44.89 | 15.08 | 0.89 |
| 4| 6359 | 55.38 | 18.74 | 1.01 |
| 5| 6508 | 65.53 | 22.19 | 1.13 |
| 6| 6431 | 69.23 | 23.22 | 1.16 |
| 7| 6536 | 74.51 | 24.95 | 1.22 |
| 8| 6859 | 88.22 | 29.68 | 1.38 |
| 9| 6975 | 97.07 | 32.62 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 567 | 6172 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2280 | 7196 | 99.22 | 38.09 | 1.54 |

