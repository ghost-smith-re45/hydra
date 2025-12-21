--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-21 04:53:26.252472438 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.73 | 4.04 | 0.55 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7650 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 169 | 747 | 39.94 | 11.60 | 0.59 |
| 4 | 226 | 858 | 51.14 | 14.69 | 0.71 |
| 5 | 285 | 969 | 63.00 | 17.93 | 0.83 |
| 6 | 339 | 1081 | 71.92 | 20.49 | 0.93 |
| 7 | 394 | 1192 | 84.77 | 23.97 | 1.06 |
| 8 | 452 | 1307 | 92.98 | 26.33 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 23.92 | 7.60 | 0.48 |
| 2| 1881 | 24.40 | 8.39 | 0.49 |
| 3| 2086 | 27.02 | 9.79 | 0.53 |
| 5| 2429 | 32.28 | 12.59 | 0.61 |
| 10| 3032 | 39.00 | 17.80 | 0.73 |
| 40| 7578 | 97.29 | 54.01 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 698 | 22.58 | 7.94 | 0.42 |
| 3| 937 | 26.99 | 9.86 | 0.48 |
| 5| 1232 | 29.08 | 11.77 | 0.52 |
| 10| 2088 | 41.31 | 18.55 | 0.71 |
| 42| 6609 | 98.24 | 55.67 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 28.46 | 8.69 | 0.47 |
| 2| 795 | 30.95 | 10.07 | 0.51 |
| 3| 964 | 33.47 | 11.46 | 0.55 |
| 5| 1279 | 37.73 | 13.99 | 0.61 |
| 10| 1922 | 43.66 | 18.98 | 0.72 |
| 34| 5484 | 96.50 | 49.72 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 760 | 35.17 | 11.17 | 0.55 |
| 3| 984 | 38.51 | 12.80 | 0.60 |
| 5| 1201 | 42.01 | 15.08 | 0.65 |
| 10| 2129 | 55.99 | 22.41 | 0.86 |
| 29| 5016 | 99.71 | 47.23 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 26.96 | 9.06 | 0.69 |
| 2| 6035 | 37.00 | 12.47 | 0.80 |
| 3| 6045 | 41.29 | 13.81 | 0.85 |
| 4| 6319 | 52.30 | 17.63 | 0.98 |
| 5| 6476 | 64.61 | 21.84 | 1.11 |
| 6| 6527 | 73.54 | 24.74 | 1.21 |
| 7| 6823 | 84.60 | 28.57 | 1.34 |
| 8| 6965 | 95.27 | 32.14 | 1.46 |
| 10| 6967 | 98.29 | 33.07 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1137 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1706 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7159 | 99.12 | 37.95 | 1.54 |

