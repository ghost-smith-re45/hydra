--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-13 07:00:31.433075763 UTC |
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
| 1| 5836 | 10.67 | 3.39 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6240 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 19.26 | 6.10 | 0.64 |
| 10| 7646 | 29.30 | 9.24 | 0.79 |
| 43| 14285 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10078 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 747 | 40.35 | 11.74 | 0.59 |
| 4 | 225 | 858 | 49.65 | 14.34 | 0.69 |
| 5 | 283 | 969 | 59.56 | 17.10 | 0.80 |
| 6 | 337 | 1081 | 69.62 | 19.91 | 0.90 |
| 7 | 394 | 1192 | 74.37 | 21.44 | 0.96 |
| 8 | 450 | 1303 | 85.26 | 24.49 | 1.07 |
| 9 | 505 | 1414 | 88.71 | 25.65 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2068 | 27.27 | 9.85 | 0.53 |
| 5| 2427 | 32.36 | 12.61 | 0.61 |
| 10| 3171 | 42.46 | 18.75 | 0.77 |
| 41| 7566 | 96.33 | 54.42 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 599 | 22.84 | 7.37 | 0.41 |
| 2| 788 | 24.28 | 8.45 | 0.44 |
| 3| 1009 | 28.23 | 10.23 | 0.50 |
| 5| 1115 | 27.05 | 11.20 | 0.50 |
| 10| 2062 | 39.69 | 18.08 | 0.69 |
| 42| 6864 | 99.55 | 56.07 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 29.13 | 8.90 | 0.48 |
| 2| 787 | 30.94 | 10.07 | 0.51 |
| 3| 873 | 32.01 | 11.01 | 0.53 |
| 5| 1175 | 36.38 | 13.58 | 0.59 |
| 10| 1954 | 43.88 | 19.06 | 0.73 |
| 37| 6124 | 99.59 | 52.77 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 821 | 35.92 | 11.40 | 0.56 |
| 3| 1015 | 38.55 | 12.81 | 0.60 |
| 5| 1259 | 42.68 | 15.29 | 0.66 |
| 10| 2094 | 54.69 | 22.00 | 0.84 |
| 29| 4832 | 98.51 | 46.87 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.05 | 9.07 | 0.69 |
| 2| 5916 | 34.87 | 11.67 | 0.78 |
| 3| 6039 | 44.01 | 14.74 | 0.88 |
| 4| 6243 | 54.80 | 18.47 | 1.00 |
| 5| 6461 | 65.31 | 22.00 | 1.12 |
| 6| 6356 | 65.21 | 21.79 | 1.11 |
| 7| 6643 | 76.01 | 25.53 | 1.24 |
| 8| 6931 | 92.29 | 31.12 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1710 | 6856 | 81.81 | 31.06 | 1.34 |
| 10 | 38 | 2163 | 7125 | 97.33 | 37.23 | 1.52 |

