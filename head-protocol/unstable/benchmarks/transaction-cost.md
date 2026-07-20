--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-20 08:04:31.299526281 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.69 | 4.65 | 0.58 |
| 5| 6640 | 18.90 | 5.97 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 228 | 858 | 48.18 | 14.01 | 0.68 |
| 5 | 283 | 974 | 56.12 | 16.28 | 0.76 |
| 6 | 337 | 1081 | 73.13 | 20.74 | 0.94 |
| 7 | 394 | 1192 | 82.94 | 23.53 | 1.04 |
| 8 | 450 | 1303 | 98.64 | 27.79 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.00 | 7.62 | 0.48 |
| 2| 1930 | 25.76 | 8.76 | 0.51 |
| 3| 2133 | 28.13 | 10.10 | 0.54 |
| 5| 2488 | 32.91 | 12.78 | 0.62 |
| 10| 3213 | 42.86 | 18.88 | 0.77 |
| 41| 7485 | 94.95 | 54.02 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.84 | 7.39 | 0.41 |
| 2| 773 | 24.08 | 8.40 | 0.44 |
| 3| 980 | 27.99 | 10.14 | 0.49 |
| 5| 1288 | 32.16 | 12.64 | 0.56 |
| 10| 2067 | 39.38 | 17.99 | 0.69 |
| 42| 6714 | 97.73 | 55.58 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.54 | 8.47 | 0.46 |
| 2| 824 | 31.66 | 10.29 | 0.52 |
| 3| 996 | 31.87 | 11.04 | 0.53 |
| 5| 1269 | 37.66 | 13.98 | 0.61 |
| 10| 2144 | 48.52 | 20.39 | 0.78 |
| 37| 6192 | 99.47 | 52.71 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 840 | 36.60 | 11.61 | 0.57 |
| 3| 1029 | 38.51 | 12.80 | 0.60 |
| 5| 1264 | 42.61 | 15.27 | 0.66 |
| 10| 2058 | 54.76 | 22.02 | 0.84 |
| 30| 4819 | 97.99 | 47.31 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5950 | 35.84 | 12.06 | 0.79 |
| 3| 5994 | 41.44 | 13.86 | 0.85 |
| 4| 6338 | 55.88 | 18.91 | 1.02 |
| 5| 6396 | 64.39 | 21.65 | 1.11 |
| 6| 6626 | 73.88 | 24.92 | 1.22 |
| 7| 6788 | 85.27 | 28.85 | 1.35 |
| 8| 6924 | 90.22 | 30.45 | 1.40 |
| 9| 6844 | 93.90 | 31.63 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 56 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 78.71 | 30.00 | 1.30 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

