--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-11 05:07:58.802439358 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6239 | 14.88 | 4.72 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 169 | 747 | 43.95 | 12.60 | 0.63 |
| 4 | 225 | 858 | 49.52 | 14.31 | 0.69 |
| 5 | 281 | 969 | 61.72 | 17.69 | 0.82 |
| 6 | 338 | 1081 | 73.94 | 20.98 | 0.95 |
| 7 | 395 | 1196 | 80.69 | 22.99 | 1.02 |
| 8 | 449 | 1303 | 98.92 | 27.76 | 1.21 |
| 10 | 561 | 1525 | 96.98 | 28.15 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1926 | 25.85 | 8.78 | 0.51 |
| 3| 2123 | 27.94 | 10.05 | 0.54 |
| 5| 2343 | 30.08 | 11.98 | 0.58 |
| 10| 3256 | 42.39 | 18.75 | 0.77 |
| 39| 7620 | 96.61 | 53.16 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.53 | 7.30 | 0.41 |
| 2| 699 | 22.58 | 7.95 | 0.42 |
| 3| 988 | 26.76 | 9.82 | 0.48 |
| 5| 1174 | 28.85 | 11.72 | 0.52 |
| 10| 1946 | 37.52 | 17.46 | 0.66 |
| 41| 6560 | 95.42 | 54.26 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.51 | 8.47 | 0.46 |
| 2| 852 | 31.58 | 10.26 | 0.52 |
| 3| 947 | 30.87 | 10.74 | 0.52 |
| 5| 1307 | 35.57 | 13.42 | 0.59 |
| 10| 1997 | 47.37 | 20.03 | 0.77 |
| 34| 5660 | 98.98 | 50.49 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.83 | 10.16 | 0.53 |
| 2| 813 | 35.89 | 11.39 | 0.56 |
| 3| 988 | 38.47 | 12.79 | 0.60 |
| 5| 1200 | 41.97 | 15.07 | 0.65 |
| 10| 2067 | 54.58 | 21.98 | 0.84 |
| 29| 4888 | 97.86 | 46.69 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.16 | 9.11 | 0.69 |
| 2| 6027 | 37.08 | 12.49 | 0.81 |
| 3| 6060 | 42.60 | 14.32 | 0.86 |
| 4| 6188 | 50.44 | 16.89 | 0.95 |
| 5| 6344 | 60.87 | 20.45 | 1.07 |
| 6| 6427 | 69.91 | 23.47 | 1.17 |
| 7| 6770 | 83.56 | 28.21 | 1.33 |
| 8| 7084 | 95.33 | 32.16 | 1.46 |
| 9| 7003 | 98.34 | 33.18 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6002 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 566 | 6170 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 61.31 | 22.98 | 1.10 |
| 10 | 39 | 2222 | 7161 | 98.49 | 37.73 | 1.53 |

