--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-31 04:54:11.189700721 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6041 | 12.44 | 3.94 | 0.54 |
| 3| 6242 | 14.69 | 4.65 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.90 | 9.10 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 39.81 | 11.57 | 0.59 |
| 4 | 226 | 858 | 53.76 | 15.32 | 0.73 |
| 5 | 283 | 969 | 62.21 | 17.70 | 0.82 |
| 6 | 339 | 1081 | 64.43 | 18.70 | 0.85 |
| 7 | 395 | 1192 | 84.82 | 23.98 | 1.06 |
| 8 | 450 | 1303 | 80.90 | 23.49 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.37 | 7.71 | 0.48 |
| 2| 2016 | 26.96 | 9.09 | 0.52 |
| 3| 2103 | 28.46 | 10.18 | 0.55 |
| 5| 2471 | 33.52 | 12.93 | 0.62 |
| 10| 3130 | 39.75 | 18.03 | 0.74 |
| 41| 7476 | 96.08 | 54.33 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.50 | 7.30 | 0.41 |
| 2| 726 | 22.52 | 7.93 | 0.42 |
| 3| 966 | 28.07 | 10.18 | 0.49 |
| 5| 1233 | 29.82 | 11.99 | 0.53 |
| 10| 1920 | 38.22 | 17.69 | 0.67 |
| 39| 6371 | 98.16 | 53.62 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.51 | 8.47 | 0.46 |
| 2| 740 | 30.20 | 9.84 | 0.50 |
| 3| 960 | 33.43 | 11.44 | 0.55 |
| 5| 1231 | 34.37 | 13.04 | 0.58 |
| 10| 1968 | 46.76 | 19.83 | 0.76 |
| 38| 6123 | 99.58 | 53.35 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.16 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 944 | 37.95 | 12.63 | 0.59 |
| 5| 1318 | 43.36 | 15.49 | 0.67 |
| 10| 2072 | 54.42 | 21.93 | 0.84 |
| 29| 4915 | 98.40 | 46.81 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 27.04 | 9.07 | 0.69 |
| 2| 5948 | 35.96 | 12.07 | 0.79 |
| 3| 6060 | 44.83 | 15.05 | 0.89 |
| 4| 6232 | 54.04 | 18.13 | 0.99 |
| 5| 6387 | 61.47 | 20.70 | 1.08 |
| 6| 6680 | 75.68 | 25.57 | 1.24 |
| 7| 6763 | 84.50 | 28.52 | 1.34 |
| 8| 6873 | 92.73 | 31.27 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

