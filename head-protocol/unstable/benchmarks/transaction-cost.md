--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-18 04:39:18.667733097 UTC |
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
| 1| 5834 | 11.04 | 3.52 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.48 | 4.58 | 0.57 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14286 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 640 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 747 | 41.22 | 11.94 | 0.60 |
| 4 | 225 | 858 | 51.27 | 14.75 | 0.71 |
| 5 | 281 | 969 | 62.78 | 17.87 | 0.83 |
| 6 | 340 | 1081 | 70.13 | 20.06 | 0.91 |
| 7 | 394 | 1192 | 74.40 | 21.53 | 0.96 |
| 8 | 450 | 1303 | 80.55 | 23.45 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.00 | 7.62 | 0.48 |
| 2| 1941 | 25.92 | 8.80 | 0.51 |
| 3| 2193 | 29.47 | 10.46 | 0.56 |
| 5| 2389 | 30.84 | 12.20 | 0.59 |
| 10| 3177 | 40.20 | 18.15 | 0.75 |
| 40| 7444 | 95.26 | 53.41 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 22.54 | 7.31 | 0.41 |
| 2| 824 | 25.13 | 8.69 | 0.45 |
| 3| 891 | 25.09 | 9.32 | 0.46 |
| 5| 1157 | 28.01 | 11.47 | 0.51 |
| 10| 2046 | 40.88 | 18.40 | 0.70 |
| 43| 6872 | 99.46 | 56.67 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 29.13 | 8.90 | 0.48 |
| 2| 822 | 29.22 | 9.61 | 0.49 |
| 3| 995 | 31.54 | 10.94 | 0.53 |
| 5| 1317 | 35.76 | 13.47 | 0.59 |
| 10| 2195 | 47.11 | 20.03 | 0.77 |
| 36| 5895 | 96.38 | 51.14 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1158 | 41.29 | 14.86 | 0.64 |
| 10| 2145 | 55.56 | 22.26 | 0.85 |
| 28| 4789 | 96.59 | 45.65 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5802 | 26.97 | 9.05 | 0.69 |
| 2| 5992 | 36.92 | 12.47 | 0.80 |
| 3| 6041 | 43.99 | 14.76 | 0.88 |
| 4| 6247 | 54.96 | 18.55 | 1.00 |
| 5| 6377 | 60.33 | 20.28 | 1.06 |
| 6| 6461 | 72.54 | 24.37 | 1.20 |
| 7| 6708 | 82.74 | 27.88 | 1.31 |
| 8| 6805 | 90.81 | 30.61 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.59 | 7.34 | 0.64 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 568 | 6172 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2216 | 7155 | 98.49 | 37.73 | 1.53 |

