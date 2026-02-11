--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-11 05:43:25.938748787 UTC |
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
| 1| 5834 | 10.78 | 3.43 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6645 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 41.41 | 12.01 | 0.60 |
| 4 | 226 | 862 | 51.16 | 14.72 | 0.71 |
| 5 | 284 | 969 | 62.96 | 17.95 | 0.83 |
| 6 | 336 | 1085 | 73.65 | 20.94 | 0.94 |
| 7 | 395 | 1196 | 72.00 | 20.90 | 0.94 |
| 8 | 450 | 1303 | 82.95 | 23.93 | 1.05 |
| 10 | 560 | 1525 | 97.20 | 28.09 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.00 | 7.62 | 0.48 |
| 2| 1880 | 24.77 | 8.48 | 0.49 |
| 3| 2155 | 27.94 | 10.05 | 0.54 |
| 5| 2431 | 32.04 | 12.53 | 0.61 |
| 10| 3120 | 39.31 | 17.90 | 0.73 |
| 40| 7745 | 99.93 | 54.73 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 22.54 | 7.31 | 0.41 |
| 2| 837 | 25.41 | 8.76 | 0.46 |
| 3| 949 | 27.10 | 9.89 | 0.48 |
| 5| 1146 | 28.57 | 11.66 | 0.52 |
| 10| 1927 | 37.62 | 17.49 | 0.67 |
| 42| 6813 | 98.88 | 55.91 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.54 | 8.47 | 0.46 |
| 2| 829 | 29.22 | 9.61 | 0.49 |
| 3| 937 | 32.72 | 11.23 | 0.54 |
| 5| 1282 | 35.00 | 13.24 | 0.58 |
| 10| 2012 | 47.32 | 20.01 | 0.77 |
| 36| 6067 | 99.04 | 51.92 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 965 | 37.95 | 12.63 | 0.59 |
| 5| 1360 | 43.36 | 15.49 | 0.67 |
| 10| 2030 | 53.97 | 21.79 | 0.83 |
| 29| 4913 | 99.11 | 47.02 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.08 | 9.08 | 0.69 |
| 2| 5942 | 35.76 | 12.02 | 0.79 |
| 3| 6060 | 45.09 | 15.17 | 0.89 |
| 4| 6209 | 54.06 | 18.17 | 0.99 |
| 5| 6414 | 64.31 | 21.66 | 1.11 |
| 6| 6602 | 74.80 | 25.23 | 1.23 |
| 7| 6516 | 80.59 | 27.05 | 1.28 |
| 8| 6686 | 83.00 | 27.81 | 1.32 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 567 | 6171 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 81.55 | 30.98 | 1.33 |
| 10 | 39 | 2222 | 7162 | 98.49 | 37.73 | 1.53 |

