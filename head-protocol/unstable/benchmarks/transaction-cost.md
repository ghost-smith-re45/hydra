--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-14 07:55:38.491360529 UTC |
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
| 1| 5837 | 10.78 | 3.43 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.88 | 4.72 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7650 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 169 | 747 | 43.72 | 12.52 | 0.63 |
| 4 | 227 | 858 | 49.51 | 14.28 | 0.69 |
| 5 | 284 | 969 | 59.42 | 17.10 | 0.80 |
| 6 | 339 | 1081 | 70.35 | 20.16 | 0.91 |
| 7 | 396 | 1192 | 78.47 | 22.42 | 1.00 |
| 8 | 450 | 1307 | 85.61 | 24.62 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2013 | 26.36 | 9.59 | 0.52 |
| 5| 2378 | 30.96 | 12.23 | 0.59 |
| 10| 3190 | 42.35 | 18.74 | 0.77 |
| 40| 7553 | 96.57 | 53.80 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.77 | 7.36 | 0.41 |
| 2| 693 | 22.58 | 7.94 | 0.42 |
| 3| 886 | 25.05 | 9.30 | 0.46 |
| 5| 1299 | 30.07 | 12.05 | 0.54 |
| 10| 1862 | 36.54 | 17.20 | 0.65 |
| 38| 6431 | 99.54 | 53.33 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 790 | 30.94 | 10.07 | 0.51 |
| 3| 868 | 32.01 | 11.01 | 0.53 |
| 5| 1206 | 34.33 | 13.03 | 0.57 |
| 10| 2027 | 48.31 | 20.30 | 0.78 |
| 35| 5787 | 93.46 | 49.66 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.83 | 10.16 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 996 | 38.59 | 12.82 | 0.60 |
| 5| 1285 | 43.24 | 15.46 | 0.67 |
| 10| 2180 | 55.41 | 22.22 | 0.85 |
| 29| 4740 | 96.01 | 46.10 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.08 | 9.09 | 0.69 |
| 2| 5948 | 35.96 | 12.08 | 0.79 |
| 3| 6097 | 44.88 | 15.08 | 0.89 |
| 4| 6211 | 53.62 | 18.02 | 0.99 |
| 5| 6406 | 65.05 | 21.96 | 1.12 |
| 6| 6696 | 76.07 | 25.70 | 1.24 |
| 7| 6825 | 84.24 | 28.41 | 1.34 |
| 8| 6964 | 94.74 | 32.02 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2222 | 7161 | 98.93 | 37.88 | 1.54 |

