--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-28 05:00:32.838020292 UTC |
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
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6240 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 33.40 | 9.68 | 0.52 |
| 3 | 170 | 747 | 42.35 | 12.18 | 0.61 |
| 4 | 227 | 858 | 50.97 | 14.65 | 0.71 |
| 5 | 284 | 969 | 60.06 | 17.26 | 0.80 |
| 6 | 337 | 1081 | 70.29 | 20.14 | 0.91 |
| 7 | 394 | 1192 | 76.70 | 22.08 | 0.98 |
| 8 | 450 | 1303 | 98.04 | 27.49 | 1.20 |
| 9 | 505 | 1414 | 90.24 | 26.25 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 23.92 | 7.60 | 0.48 |
| 2| 1975 | 26.84 | 9.06 | 0.52 |
| 3| 2069 | 26.95 | 9.77 | 0.53 |
| 5| 2424 | 31.87 | 12.49 | 0.60 |
| 10| 3075 | 39.86 | 18.06 | 0.74 |
| 40| 7628 | 98.11 | 54.24 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.39 | 0.41 |
| 2| 739 | 23.62 | 8.23 | 0.43 |
| 3| 857 | 24.07 | 9.03 | 0.45 |
| 5| 1261 | 31.37 | 12.41 | 0.55 |
| 10| 2157 | 41.75 | 18.65 | 0.72 |
| 39| 6321 | 92.99 | 52.27 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.17 | 8.91 | 0.48 |
| 2| 771 | 28.51 | 9.39 | 0.48 |
| 3| 872 | 32.09 | 11.03 | 0.53 |
| 5| 1370 | 39.15 | 14.42 | 0.63 |
| 10| 1958 | 47.48 | 20.05 | 0.76 |
| 37| 6057 | 98.24 | 52.34 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 899 | 37.16 | 12.39 | 0.58 |
| 5| 1334 | 43.28 | 15.48 | 0.67 |
| 10| 2051 | 54.25 | 21.86 | 0.84 |
| 30| 4972 | 99.16 | 47.66 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 5917 | 34.94 | 11.70 | 0.78 |
| 3| 6061 | 44.74 | 15.02 | 0.89 |
| 4| 6225 | 53.77 | 18.09 | 0.99 |
| 5| 6218 | 58.77 | 19.64 | 1.04 |
| 6| 6649 | 74.04 | 25.02 | 1.22 |
| 7| 6682 | 81.21 | 27.34 | 1.30 |
| 8| 6978 | 91.04 | 30.67 | 1.41 |
| 9| 7048 | 99.84 | 33.73 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 82.44 | 31.28 | 1.34 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

