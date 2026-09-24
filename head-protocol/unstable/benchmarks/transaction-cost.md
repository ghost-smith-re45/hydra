--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-24 10:19:55.485827057 UTC |
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
| 1| 5836 | 10.78 | 3.43 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6243 | 14.50 | 4.58 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2165 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 747 | 41.08 | 11.87 | 0.60 |
| 4 | 225 | 858 | 49.88 | 14.44 | 0.70 |
| 5 | 281 | 969 | 59.49 | 17.12 | 0.80 |
| 6 | 336 | 1081 | 75.49 | 21.31 | 0.96 |
| 7 | 397 | 1192 | 78.15 | 22.33 | 1.00 |
| 8 | 448 | 1307 | 87.59 | 25.05 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.37 | 7.71 | 0.48 |
| 2| 1952 | 25.55 | 8.71 | 0.51 |
| 3| 2013 | 25.95 | 9.49 | 0.52 |
| 5| 2436 | 31.91 | 12.50 | 0.61 |
| 10| 3121 | 39.39 | 17.92 | 0.74 |
| 37| 7206 | 93.23 | 50.87 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 22.84 | 7.38 | 0.42 |
| 2| 826 | 25.57 | 8.80 | 0.46 |
| 3| 931 | 26.99 | 9.86 | 0.48 |
| 5| 1300 | 32.40 | 12.70 | 0.56 |
| 10| 2109 | 41.97 | 18.71 | 0.72 |
| 42| 6822 | 99.89 | 56.20 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 992 | 33.51 | 11.47 | 0.55 |
| 5| 1231 | 34.26 | 13.02 | 0.58 |
| 10| 1936 | 46.58 | 19.79 | 0.75 |
| 35| 5697 | 98.59 | 51.00 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.87 | 10.16 | 0.53 |
| 2| 824 | 35.89 | 11.39 | 0.56 |
| 3| 969 | 37.84 | 12.60 | 0.59 |
| 5| 1158 | 41.11 | 14.82 | 0.64 |
| 10| 2087 | 54.63 | 21.99 | 0.84 |
| 29| 5014 | 99.53 | 47.20 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5785 | 27.00 | 9.08 | 0.69 |
| 2| 5997 | 36.73 | 12.38 | 0.80 |
| 3| 6014 | 41.37 | 13.83 | 0.85 |
| 4| 6152 | 50.65 | 16.98 | 0.95 |
| 5| 6400 | 63.97 | 21.56 | 1.10 |
| 6| 6676 | 75.25 | 25.43 | 1.24 |
| 7| 6816 | 83.85 | 28.33 | 1.33 |
| 8| 6885 | 90.46 | 30.45 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2275 | 7192 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2165 | 7127 | 96.44 | 36.92 | 1.51 |

