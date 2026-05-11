--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-11 08:49:34.542141397 UTC |
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
| 1| 5836 | 10.93 | 3.49 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6236 | 14.48 | 4.58 | 0.57 |
| 5| 6646 | 18.83 | 5.95 | 0.64 |
| 10| 7648 | 28.88 | 9.10 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 41.23 | 11.94 | 0.60 |
| 4 | 227 | 858 | 51.13 | 14.71 | 0.71 |
| 5 | 283 | 969 | 56.54 | 16.38 | 0.77 |
| 6 | 338 | 1081 | 75.74 | 21.41 | 0.96 |
| 7 | 396 | 1192 | 71.98 | 20.90 | 0.93 |
| 8 | 450 | 1303 | 99.41 | 27.97 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1938 | 25.39 | 8.68 | 0.50 |
| 3| 2123 | 28.42 | 10.17 | 0.55 |
| 5| 2498 | 33.57 | 12.94 | 0.62 |
| 10| 3177 | 41.23 | 18.44 | 0.76 |
| 41| 7660 | 99.35 | 55.21 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.84 | 7.37 | 0.42 |
| 2| 772 | 24.08 | 8.41 | 0.44 |
| 3| 881 | 25.09 | 9.33 | 0.46 |
| 5| 1309 | 31.72 | 12.54 | 0.55 |
| 10| 1917 | 37.40 | 17.43 | 0.66 |
| 41| 6533 | 96.67 | 54.59 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.54 | 8.47 | 0.46 |
| 2| 732 | 30.27 | 9.86 | 0.50 |
| 3| 940 | 30.90 | 10.74 | 0.52 |
| 5| 1292 | 37.70 | 13.99 | 0.61 |
| 10| 2188 | 46.76 | 19.95 | 0.77 |
| 33| 5469 | 90.85 | 47.60 | 1.47 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 759 | 35.21 | 11.18 | 0.55 |
| 3| 1010 | 38.84 | 12.91 | 0.60 |
| 5| 1329 | 43.36 | 15.49 | 0.67 |
| 10| 2114 | 55.56 | 22.26 | 0.85 |
| 29| 5038 | 99.62 | 47.21 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5831 | 27.05 | 9.08 | 0.69 |
| 2| 5929 | 35.84 | 12.04 | 0.79 |
| 3| 6201 | 47.20 | 15.97 | 0.92 |
| 4| 6212 | 53.96 | 18.15 | 0.99 |
| 5| 6291 | 59.36 | 19.90 | 1.05 |
| 6| 6353 | 65.27 | 21.84 | 1.11 |
| 7| 6730 | 80.56 | 27.19 | 1.29 |
| 8| 6958 | 94.19 | 31.82 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6175 | 40.83 | 14.90 | 0.86 |
| 10 | 39 | 2218 | 7157 | 98.49 | 37.73 | 1.53 |

