--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-30 07:29:26.896755702 UTC |
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
| 1| 5837 | 10.35 | 3.28 | 0.51 |
| 2| 6038 | 12.70 | 4.03 | 0.55 |
| 3| 6238 | 14.86 | 4.71 | 0.58 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7651 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 33.33 | 9.64 | 0.52 |
| 3 | 170 | 751 | 40.28 | 11.74 | 0.59 |
| 4 | 226 | 858 | 53.79 | 15.33 | 0.73 |
| 5 | 283 | 969 | 62.57 | 17.82 | 0.83 |
| 6 | 338 | 1081 | 75.15 | 21.23 | 0.96 |
| 7 | 396 | 1196 | 80.25 | 22.80 | 1.02 |
| 8 | 450 | 1303 | 84.97 | 24.46 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.37 | 7.71 | 0.48 |
| 2| 1952 | 25.85 | 8.78 | 0.51 |
| 3| 2097 | 28.10 | 10.09 | 0.54 |
| 5| 2459 | 32.34 | 12.62 | 0.61 |
| 10| 3110 | 39.52 | 17.95 | 0.74 |
| 39| 7574 | 97.26 | 53.34 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.50 | 7.30 | 0.41 |
| 2| 700 | 22.62 | 7.97 | 0.42 |
| 3| 939 | 26.53 | 9.75 | 0.48 |
| 5| 1163 | 28.14 | 11.52 | 0.51 |
| 10| 1908 | 37.68 | 17.50 | 0.66 |
| 41| 6614 | 97.07 | 54.72 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 828 | 31.62 | 10.28 | 0.52 |
| 3| 944 | 30.82 | 10.73 | 0.52 |
| 5| 1296 | 34.89 | 13.21 | 0.58 |
| 10| 2074 | 49.19 | 20.58 | 0.79 |
| 34| 5595 | 96.51 | 49.78 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.16 | 0.53 |
| 2| 862 | 36.60 | 11.61 | 0.57 |
| 3| 966 | 37.91 | 12.62 | 0.59 |
| 5| 1212 | 41.82 | 15.03 | 0.65 |
| 10| 1962 | 53.50 | 21.63 | 0.82 |
| 30| 4785 | 96.83 | 46.96 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.13 | 9.10 | 0.69 |
| 2| 5959 | 37.16 | 12.52 | 0.80 |
| 3| 6035 | 42.88 | 14.42 | 0.87 |
| 4| 6231 | 53.47 | 18.03 | 0.99 |
| 5| 6221 | 55.78 | 18.66 | 1.01 |
| 6| 6561 | 72.75 | 24.50 | 1.20 |
| 7| 6721 | 79.83 | 26.77 | 1.28 |
| 8| 6677 | 85.36 | 28.74 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.93 | 37.88 | 1.54 |

