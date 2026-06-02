--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-02 09:40:11.942158098 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 13.16 | 4.19 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 29.26 | 9.23 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 43.64 | 12.49 | 0.63 |
| 4 | 226 | 858 | 52.27 | 14.96 | 0.72 |
| 5 | 282 | 969 | 64.16 | 18.20 | 0.84 |
| 6 | 338 | 1081 | 65.85 | 19.00 | 0.87 |
| 7 | 397 | 1192 | 74.64 | 21.54 | 0.96 |
| 8 | 450 | 1303 | 93.95 | 26.52 | 1.16 |
| 9 | 506 | 1414 | 95.87 | 27.37 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1995 | 26.83 | 9.06 | 0.52 |
| 3| 2061 | 26.98 | 9.78 | 0.53 |
| 5| 2372 | 31.83 | 12.46 | 0.60 |
| 10| 3132 | 41.01 | 18.36 | 0.75 |
| 40| 7652 | 98.69 | 54.36 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 22.81 | 7.38 | 0.42 |
| 2| 814 | 25.37 | 8.75 | 0.45 |
| 3| 872 | 25.82 | 9.54 | 0.47 |
| 5| 1269 | 31.01 | 12.34 | 0.55 |
| 10| 1975 | 38.77 | 17.82 | 0.68 |
| 40| 6380 | 97.64 | 54.14 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 27.54 | 8.47 | 0.46 |
| 2| 814 | 29.19 | 9.60 | 0.49 |
| 3| 946 | 30.94 | 10.75 | 0.52 |
| 5| 1311 | 37.65 | 13.97 | 0.61 |
| 10| 2058 | 47.93 | 20.20 | 0.77 |
| 33| 5419 | 95.92 | 48.92 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 870 | 36.48 | 11.58 | 0.57 |
| 3| 938 | 37.84 | 12.60 | 0.59 |
| 5| 1288 | 43.28 | 15.47 | 0.67 |
| 10| 2154 | 56.27 | 22.48 | 0.86 |
| 28| 4648 | 95.42 | 45.31 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 26.92 | 9.05 | 0.69 |
| 2| 5893 | 34.87 | 11.66 | 0.78 |
| 3| 6074 | 44.70 | 15.03 | 0.89 |
| 4| 6321 | 55.83 | 18.86 | 1.02 |
| 5| 6466 | 65.47 | 22.03 | 1.12 |
| 6| 6621 | 75.45 | 25.44 | 1.23 |
| 7| 6741 | 80.53 | 27.20 | 1.29 |
| 8| 6937 | 93.08 | 31.42 | 1.43 |
| 9| 7008 | 99.19 | 33.51 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.31 | 6.45 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 566 | 6170 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.22 | 30.52 | 1.32 |
| 10 | 40 | 2276 | 7192 | 99.22 | 38.09 | 1.54 |

