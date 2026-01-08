--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-08 04:52:56.599792725 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 171 | 747 | 42.60 | 12.24 | 0.62 |
| 4 | 226 | 858 | 48.38 | 14.06 | 0.68 |
| 5 | 283 | 969 | 64.23 | 18.22 | 0.84 |
| 6 | 337 | 1085 | 75.06 | 21.17 | 0.96 |
| 7 | 392 | 1192 | 75.26 | 21.74 | 0.97 |
| 8 | 450 | 1303 | 91.53 | 26.03 | 1.13 |
| 10 | 560 | 1525 | 97.46 | 28.27 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1950 | 25.88 | 8.79 | 0.51 |
| 3| 2074 | 27.27 | 9.85 | 0.53 |
| 5| 2429 | 31.95 | 12.51 | 0.61 |
| 10| 3159 | 40.60 | 18.25 | 0.75 |
| 39| 7544 | 99.46 | 53.94 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.54 | 7.30 | 0.41 |
| 2| 768 | 24.35 | 8.47 | 0.44 |
| 3| 946 | 26.94 | 9.85 | 0.48 |
| 5| 1134 | 28.07 | 11.50 | 0.51 |
| 10| 1966 | 38.54 | 17.75 | 0.68 |
| 41| 6649 | 97.70 | 54.87 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 29.17 | 8.91 | 0.48 |
| 2| 841 | 31.58 | 10.26 | 0.52 |
| 3| 868 | 32.08 | 11.03 | 0.53 |
| 5| 1188 | 36.43 | 13.59 | 0.59 |
| 10| 1969 | 47.55 | 20.07 | 0.77 |
| 35| 5645 | 93.15 | 49.53 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.83 | 10.15 | 0.53 |
| 2| 834 | 35.88 | 11.39 | 0.56 |
| 3| 1050 | 39.30 | 13.04 | 0.61 |
| 5| 1287 | 42.68 | 15.29 | 0.66 |
| 10| 2069 | 54.20 | 21.86 | 0.84 |
| 29| 4945 | 98.59 | 46.85 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 5937 | 35.88 | 12.06 | 0.79 |
| 3| 6111 | 45.79 | 15.44 | 0.90 |
| 4| 6270 | 51.40 | 17.29 | 0.97 |
| 5| 6328 | 56.85 | 19.05 | 1.03 |
| 6| 6410 | 68.65 | 22.96 | 1.15 |
| 7| 6734 | 84.95 | 28.70 | 1.34 |
| 8| 7061 | 95.01 | 32.10 | 1.46 |
| 9| 6848 | 96.79 | 32.46 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1709 | 6855 | 79.15 | 30.16 | 1.31 |
| 10 | 37 | 2107 | 7093 | 93.95 | 35.96 | 1.48 |

