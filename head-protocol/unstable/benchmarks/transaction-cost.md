--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-02 07:49:27.583286616 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6038 | 12.82 | 4.07 | 0.55 |
| 3| 6238 | 14.98 | 4.75 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14285 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 41.20 | 11.90 | 0.60 |
| 4 | 227 | 858 | 51.18 | 14.73 | 0.71 |
| 5 | 281 | 969 | 62.53 | 17.81 | 0.83 |
| 6 | 339 | 1081 | 71.24 | 20.29 | 0.92 |
| 7 | 394 | 1192 | 78.82 | 22.55 | 1.00 |
| 8 | 449 | 1303 | 98.58 | 27.67 | 1.20 |
| 9 | 506 | 1414 | 98.72 | 28.11 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.00 | 7.62 | 0.48 |
| 2| 1936 | 25.43 | 8.68 | 0.50 |
| 3| 2012 | 26.24 | 9.56 | 0.52 |
| 5| 2342 | 30.12 | 11.99 | 0.58 |
| 10| 3255 | 42.65 | 18.83 | 0.77 |
| 42| 7837 | 99.70 | 55.98 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.77 | 7.36 | 0.42 |
| 2| 745 | 23.66 | 8.26 | 0.43 |
| 3| 950 | 26.06 | 9.59 | 0.47 |
| 5| 1321 | 32.25 | 12.68 | 0.56 |
| 10| 2038 | 40.28 | 18.26 | 0.70 |
| 41| 6559 | 97.02 | 54.68 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 29.13 | 8.90 | 0.48 |
| 2| 778 | 30.94 | 10.07 | 0.51 |
| 3| 962 | 33.51 | 11.47 | 0.55 |
| 5| 1228 | 36.98 | 13.77 | 0.60 |
| 10| 2134 | 46.47 | 19.85 | 0.76 |
| 36| 5932 | 97.16 | 51.38 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.79 | 10.15 | 0.53 |
| 2| 807 | 35.89 | 11.39 | 0.56 |
| 3| 1018 | 38.62 | 12.83 | 0.60 |
| 5| 1249 | 42.72 | 15.30 | 0.66 |
| 10| 1981 | 53.99 | 21.79 | 0.83 |
| 28| 4549 | 94.19 | 44.92 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.05 | 9.07 | 0.69 |
| 2| 5889 | 32.64 | 10.90 | 0.75 |
| 3| 6090 | 44.84 | 15.08 | 0.89 |
| 4| 6187 | 54.15 | 18.18 | 0.99 |
| 5| 6466 | 64.34 | 21.62 | 1.11 |
| 6| 6529 | 69.51 | 23.33 | 1.17 |
| 7| 6603 | 76.31 | 25.64 | 1.24 |
| 8| 6845 | 90.22 | 30.37 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 567 | 6172 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 38 | 2160 | 7123 | 98.65 | 37.68 | 1.53 |

