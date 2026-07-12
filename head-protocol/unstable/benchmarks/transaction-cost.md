--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-12 07:45:40.059082211 UTC |
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
| 1| 5836 | 10.48 | 3.33 | 0.52 |
| 2| 6038 | 12.99 | 4.13 | 0.55 |
| 3| 6242 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 99.40 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 41.51 | 12.02 | 0.61 |
| 4 | 226 | 858 | 48.09 | 13.97 | 0.68 |
| 5 | 283 | 969 | 61.07 | 17.52 | 0.81 |
| 6 | 339 | 1081 | 63.84 | 18.52 | 0.85 |
| 7 | 394 | 1192 | 87.17 | 24.63 | 1.08 |
| 8 | 449 | 1303 | 94.03 | 26.58 | 1.16 |
| 9 | 506 | 1414 | 90.72 | 26.19 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 24.29 | 7.69 | 0.48 |
| 2| 1928 | 25.51 | 8.70 | 0.50 |
| 3| 2057 | 27.06 | 9.80 | 0.53 |
| 5| 2368 | 31.25 | 12.30 | 0.60 |
| 10| 3144 | 41.16 | 18.41 | 0.75 |
| 42| 7703 | 96.20 | 55.04 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.81 | 7.38 | 0.42 |
| 2| 699 | 22.58 | 7.96 | 0.42 |
| 3| 899 | 25.03 | 9.30 | 0.46 |
| 5| 1183 | 29.07 | 11.77 | 0.52 |
| 10| 2131 | 41.97 | 18.71 | 0.72 |
| 39| 6232 | 94.13 | 52.52 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 28.46 | 8.69 | 0.47 |
| 2| 876 | 29.94 | 9.83 | 0.50 |
| 3| 978 | 30.86 | 10.73 | 0.52 |
| 5| 1298 | 37.58 | 13.96 | 0.61 |
| 10| 2057 | 48.12 | 20.25 | 0.78 |
| 34| 5531 | 97.26 | 49.93 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 875 | 36.52 | 11.59 | 0.57 |
| 3| 898 | 37.13 | 12.38 | 0.58 |
| 5| 1336 | 43.61 | 15.58 | 0.67 |
| 10| 2213 | 55.77 | 22.35 | 0.86 |
| 28| 4661 | 94.23 | 44.95 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.00 | 9.06 | 0.69 |
| 2| 5960 | 37.16 | 12.51 | 0.80 |
| 3| 6089 | 45.93 | 15.50 | 0.90 |
| 4| 6170 | 50.55 | 16.93 | 0.95 |
| 5| 6411 | 64.83 | 21.81 | 1.11 |
| 6| 6592 | 75.25 | 25.39 | 1.23 |
| 7| 6545 | 75.85 | 25.48 | 1.23 |
| 8| 6964 | 94.53 | 31.95 | 1.45 |
| 9| 6779 | 92.74 | 31.04 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 38 | 2162 | 7125 | 97.95 | 37.44 | 1.53 |

