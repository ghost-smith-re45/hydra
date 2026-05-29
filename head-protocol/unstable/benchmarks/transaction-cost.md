--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-29 09:07:34.791445887 UTC |
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
| 1| 5834 | 10.35 | 3.28 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 40.28 | 11.70 | 0.59 |
| 4 | 227 | 862 | 52.44 | 14.98 | 0.72 |
| 5 | 284 | 969 | 59.81 | 17.20 | 0.80 |
| 6 | 336 | 1081 | 71.47 | 20.31 | 0.92 |
| 7 | 394 | 1192 | 84.64 | 23.98 | 1.06 |
| 8 | 451 | 1303 | 99.02 | 27.78 | 1.21 |
| 9 | 507 | 1414 | 92.09 | 26.69 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.00 | 7.62 | 0.48 |
| 2| 1965 | 26.91 | 9.08 | 0.52 |
| 3| 2065 | 26.94 | 9.77 | 0.53 |
| 5| 2444 | 32.33 | 12.60 | 0.61 |
| 10| 3210 | 43.27 | 18.98 | 0.78 |
| 43| 7801 | 99.34 | 56.55 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.50 | 7.29 | 0.41 |
| 2| 811 | 25.52 | 8.80 | 0.46 |
| 3| 957 | 26.06 | 9.59 | 0.47 |
| 5| 1187 | 29.10 | 11.78 | 0.52 |
| 10| 2050 | 40.62 | 18.33 | 0.70 |
| 41| 6762 | 98.64 | 55.16 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.51 | 8.47 | 0.46 |
| 2| 888 | 29.89 | 9.82 | 0.50 |
| 3| 966 | 30.82 | 10.73 | 0.52 |
| 5| 1313 | 35.30 | 13.33 | 0.59 |
| 10| 1964 | 44.04 | 19.11 | 0.73 |
| 36| 5761 | 94.34 | 50.56 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.83 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 990 | 38.66 | 12.84 | 0.60 |
| 5| 1311 | 43.24 | 15.46 | 0.67 |
| 10| 1851 | 52.07 | 21.20 | 0.81 |
| 30| 4832 | 99.15 | 47.62 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 27.13 | 9.11 | 0.69 |
| 2| 5937 | 35.84 | 12.06 | 0.79 |
| 3| 5898 | 37.08 | 12.29 | 0.80 |
| 4| 6166 | 52.81 | 17.70 | 0.98 |
| 5| 6546 | 66.47 | 22.45 | 1.14 |
| 6| 6539 | 71.51 | 24.03 | 1.19 |
| 7| 6762 | 84.99 | 28.68 | 1.34 |
| 8| 6970 | 94.97 | 32.04 | 1.46 |
| 9| 6888 | 95.39 | 32.16 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 60.35 | 22.66 | 1.09 |
| 10 | 30 | 1709 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2220 | 7160 | 97.35 | 37.34 | 1.52 |

