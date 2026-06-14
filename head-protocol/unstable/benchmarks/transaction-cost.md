--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-14 09:33:08.634584093 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.88 | 9.10 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.39 | 9.43 | 0.51 |
| 3 | 170 | 747 | 40.09 | 11.66 | 0.59 |
| 4 | 228 | 858 | 48.34 | 14.05 | 0.68 |
| 5 | 283 | 969 | 58.22 | 16.81 | 0.78 |
| 6 | 339 | 1081 | 71.56 | 20.44 | 0.92 |
| 7 | 396 | 1196 | 72.40 | 20.96 | 0.94 |
| 8 | 452 | 1303 | 85.65 | 24.63 | 1.08 |
| 9 | 505 | 1414 | 91.54 | 26.44 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.00 | 7.62 | 0.48 |
| 2| 1955 | 25.81 | 8.80 | 0.51 |
| 3| 2084 | 27.27 | 9.85 | 0.53 |
| 5| 2332 | 30.00 | 11.96 | 0.58 |
| 10| 3141 | 40.85 | 18.31 | 0.75 |
| 39| 7551 | 97.13 | 53.29 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 704 | 22.55 | 7.94 | 0.42 |
| 3| 946 | 26.16 | 9.62 | 0.47 |
| 5| 1167 | 28.77 | 11.70 | 0.52 |
| 10| 2118 | 41.58 | 18.60 | 0.71 |
| 43| 6826 | 97.91 | 56.27 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 782 | 30.87 | 10.05 | 0.51 |
| 3| 966 | 30.82 | 10.73 | 0.52 |
| 5| 1219 | 37.02 | 13.77 | 0.60 |
| 10| 1966 | 47.51 | 20.06 | 0.77 |
| 36| 5856 | 95.92 | 50.97 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 938 | 37.87 | 12.61 | 0.59 |
| 5| 1328 | 42.98 | 15.38 | 0.67 |
| 10| 2263 | 56.98 | 22.69 | 0.87 |
| 29| 4755 | 96.33 | 46.18 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.08 | 0.69 |
| 2| 5972 | 36.03 | 12.11 | 0.79 |
| 3| 6041 | 43.84 | 14.69 | 0.88 |
| 4| 6203 | 50.31 | 16.88 | 0.95 |
| 5| 6331 | 64.28 | 21.66 | 1.10 |
| 6| 6530 | 69.58 | 23.44 | 1.17 |
| 7| 6756 | 79.95 | 27.00 | 1.29 |
| 8| 6717 | 84.78 | 28.45 | 1.34 |
| 9| 6835 | 94.25 | 31.61 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.09 | 10.34 | 0.72 |
| 10 | 38 | 2163 | 7126 | 95.11 | 36.47 | 1.50 |

