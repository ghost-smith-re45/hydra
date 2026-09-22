--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-22 10:17:04.232489069 UTC |
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
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2165 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 640 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 751 | 41.23 | 11.93 | 0.60 |
| 4 | 228 | 862 | 49.70 | 14.35 | 0.69 |
| 5 | 284 | 969 | 61.53 | 17.61 | 0.82 |
| 6 | 338 | 1081 | 74.54 | 21.04 | 0.95 |
| 7 | 394 | 1192 | 74.24 | 21.36 | 0.96 |
| 8 | 449 | 1303 | 83.87 | 24.25 | 1.06 |
| 9 | 504 | 1414 | 95.69 | 27.38 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1883 | 24.77 | 8.48 | 0.49 |
| 3| 2109 | 27.40 | 9.90 | 0.54 |
| 5| 2440 | 32.15 | 12.56 | 0.61 |
| 10| 3191 | 42.09 | 18.67 | 0.77 |
| 39| 7605 | 99.44 | 53.95 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.57 | 7.33 | 0.41 |
| 2| 761 | 23.58 | 8.23 | 0.43 |
| 3| 853 | 24.07 | 9.03 | 0.45 |
| 5| 1276 | 31.23 | 12.38 | 0.55 |
| 10| 2071 | 40.49 | 18.29 | 0.70 |
| 41| 6666 | 98.38 | 55.07 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 829 | 29.15 | 9.59 | 0.49 |
| 3| 923 | 32.72 | 11.23 | 0.54 |
| 5| 1269 | 36.98 | 13.76 | 0.60 |
| 10| 2122 | 49.65 | 20.71 | 0.79 |
| 34| 5504 | 95.81 | 49.57 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.87 | 10.16 | 0.53 |
| 2| 812 | 35.81 | 11.37 | 0.56 |
| 3| 964 | 37.87 | 12.61 | 0.59 |
| 5| 1339 | 43.16 | 15.45 | 0.67 |
| 10| 2016 | 54.09 | 21.82 | 0.83 |
| 30| 4847 | 98.26 | 47.38 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 27.04 | 9.07 | 0.69 |
| 2| 5871 | 34.99 | 11.72 | 0.78 |
| 3| 6147 | 45.85 | 15.47 | 0.90 |
| 4| 6094 | 49.24 | 16.46 | 0.93 |
| 5| 6426 | 63.79 | 21.55 | 1.10 |
| 6| 6723 | 74.85 | 25.27 | 1.23 |
| 7| 6498 | 71.28 | 23.80 | 1.18 |
| 8| 6797 | 91.65 | 30.91 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 20 | 1139 | 6514 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1709 | 6855 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2221 | 7161 | 98.05 | 37.58 | 1.53 |

