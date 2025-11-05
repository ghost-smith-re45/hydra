--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-05 04:37:37.927107853 UTC |
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
| 1| 5841 | 10.47 | 3.32 | 0.52 |
| 2| 6035 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 15.05 | 4.78 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 43.68 | 12.51 | 0.63 |
| 4 | 226 | 858 | 53.53 | 15.24 | 0.73 |
| 5 | 281 | 969 | 64.31 | 18.27 | 0.84 |
| 6 | 340 | 1081 | 71.20 | 20.24 | 0.92 |
| 7 | 396 | 1192 | 78.57 | 22.48 | 1.00 |
| 8 | 450 | 1307 | 86.98 | 24.80 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 2013 | 26.39 | 8.96 | 0.52 |
| 3| 2066 | 26.95 | 9.77 | 0.53 |
| 5| 2488 | 33.26 | 12.87 | 0.62 |
| 10| 3016 | 38.17 | 17.58 | 0.72 |
| 40| 7588 | 97.23 | 53.96 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.77 | 7.36 | 0.42 |
| 2| 765 | 23.63 | 8.24 | 0.43 |
| 3| 928 | 25.83 | 9.55 | 0.47 |
| 5| 1260 | 30.64 | 12.23 | 0.54 |
| 10| 2034 | 40.77 | 18.38 | 0.70 |
| 42| 6478 | 96.93 | 55.27 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 928 | 32.75 | 11.24 | 0.54 |
| 5| 1396 | 36.44 | 13.67 | 0.60 |
| 10| 2152 | 49.53 | 20.68 | 0.79 |
| 35| 5646 | 92.59 | 49.37 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 709 | 33.83 | 10.16 | 0.53 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1272 | 42.61 | 15.27 | 0.66 |
| 10| 1920 | 52.79 | 21.41 | 0.82 |
| 28| 4678 | 94.94 | 45.15 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5799 | 27.09 | 9.08 | 0.69 |
| 2| 5895 | 32.61 | 10.89 | 0.75 |
| 3| 6062 | 44.73 | 15.06 | 0.89 |
| 4| 6351 | 55.96 | 18.87 | 1.02 |
| 5| 6464 | 65.12 | 21.98 | 1.12 |
| 6| 6567 | 70.13 | 23.62 | 1.18 |
| 7| 6722 | 82.73 | 27.81 | 1.31 |
| 8| 6747 | 84.77 | 28.43 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 10 | 569 | 6173 | 39.88 | 14.58 | 0.85 |
| 10 | 20 | 1140 | 6515 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7161 | 98.93 | 37.88 | 1.54 |

