--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-10 06:31:13.250353787 UTC |
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
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.40 | 4.55 | 0.57 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7647 | 28.81 | 9.07 | 0.78 |
| 43| 14283 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.39 | 9.43 | 0.51 |
| 3 | 171 | 751 | 42.34 | 12.17 | 0.61 |
| 4 | 226 | 858 | 52.48 | 15.01 | 0.72 |
| 5 | 283 | 974 | 62.99 | 17.96 | 0.83 |
| 6 | 338 | 1081 | 69.85 | 19.96 | 0.91 |
| 7 | 395 | 1196 | 84.55 | 24.00 | 1.06 |
| 8 | 450 | 1303 | 92.46 | 26.26 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1753 | 23.30 | 7.41 | 0.47 |
| 2| 1916 | 25.47 | 8.70 | 0.50 |
| 3| 2063 | 26.98 | 9.78 | 0.53 |
| 5| 2445 | 32.31 | 12.60 | 0.61 |
| 10| 3098 | 40.04 | 18.08 | 0.74 |
| 38| 7273 | 92.86 | 51.42 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.81 | 7.37 | 0.42 |
| 2| 762 | 24.35 | 8.47 | 0.44 |
| 3| 1034 | 28.01 | 10.16 | 0.50 |
| 5| 1157 | 28.12 | 11.50 | 0.51 |
| 10| 1921 | 38.60 | 17.77 | 0.67 |
| 41| 6670 | 99.35 | 55.36 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.50 | 8.46 | 0.46 |
| 2| 838 | 29.26 | 9.62 | 0.49 |
| 3| 1023 | 34.15 | 11.66 | 0.56 |
| 5| 1290 | 35.68 | 13.45 | 0.59 |
| 10| 1983 | 44.33 | 19.21 | 0.73 |
| 36| 6002 | 96.39 | 51.18 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.87 | 10.16 | 0.53 |
| 2| 815 | 35.89 | 11.39 | 0.56 |
| 3| 938 | 37.88 | 12.61 | 0.59 |
| 5| 1244 | 42.72 | 15.30 | 0.66 |
| 10| 2030 | 53.98 | 21.79 | 0.83 |
| 31| 4898 | 98.96 | 48.19 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.09 | 9.10 | 0.69 |
| 2| 5932 | 36.15 | 12.13 | 0.79 |
| 3| 6158 | 45.78 | 15.43 | 0.90 |
| 4| 6333 | 56.15 | 18.94 | 1.02 |
| 5| 6401 | 64.47 | 21.67 | 1.11 |
| 6| 6433 | 68.18 | 22.86 | 1.15 |
| 7| 6713 | 79.22 | 26.73 | 1.28 |
| 8| 6730 | 85.73 | 28.81 | 1.35 |
| 9| 6802 | 90.36 | 30.42 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 81.55 | 30.98 | 1.33 |
| 10 | 40 | 2280 | 7197 | 99.66 | 38.24 | 1.55 |

