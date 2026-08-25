--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-25 05:59:51.081830801 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6041 | 12.44 | 3.94 | 0.54 |
| 3| 6243 | 15.14 | 4.81 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.38 | 9.27 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 171 | 747 | 41.39 | 11.97 | 0.60 |
| 4 | 226 | 858 | 51.91 | 14.87 | 0.71 |
| 5 | 284 | 969 | 64.61 | 18.34 | 0.85 |
| 6 | 337 | 1085 | 66.07 | 19.09 | 0.87 |
| 7 | 395 | 1192 | 87.25 | 24.65 | 1.09 |
| 8 | 451 | 1307 | 91.70 | 25.97 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 23.92 | 7.60 | 0.48 |
| 2| 1935 | 25.84 | 8.78 | 0.51 |
| 3| 2129 | 28.02 | 10.07 | 0.54 |
| 5| 2411 | 32.21 | 12.57 | 0.61 |
| 10| 3107 | 40.03 | 18.08 | 0.74 |
| 41| 7765 | 99.16 | 55.21 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.54 | 7.30 | 0.41 |
| 2| 793 | 25.47 | 8.77 | 0.45 |
| 3| 882 | 25.13 | 9.33 | 0.46 |
| 5| 1252 | 30.09 | 12.05 | 0.54 |
| 10| 1967 | 38.58 | 17.76 | 0.68 |
| 39| 6171 | 91.65 | 51.89 | 1.54 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 29.17 | 8.91 | 0.48 |
| 2| 875 | 29.89 | 9.82 | 0.50 |
| 3| 1017 | 31.69 | 10.98 | 0.53 |
| 5| 1347 | 38.40 | 14.20 | 0.62 |
| 10| 2082 | 45.80 | 19.63 | 0.75 |
| 35| 5864 | 96.14 | 50.45 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.17 | 11.17 | 0.55 |
| 3| 996 | 38.55 | 12.81 | 0.60 |
| 5| 1199 | 41.89 | 15.05 | 0.65 |
| 10| 2015 | 54.32 | 21.89 | 0.84 |
| 29| 4748 | 96.72 | 46.33 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 26.97 | 9.07 | 0.69 |
| 2| 5959 | 37.05 | 12.49 | 0.80 |
| 3| 6221 | 46.77 | 15.83 | 0.92 |
| 4| 6115 | 50.59 | 16.92 | 0.95 |
| 5| 6198 | 56.09 | 18.79 | 1.01 |
| 6| 6555 | 73.62 | 24.78 | 1.21 |
| 7| 6648 | 79.55 | 26.75 | 1.28 |
| 8| 6990 | 93.40 | 31.50 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 40.83 | 14.90 | 0.86 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |

