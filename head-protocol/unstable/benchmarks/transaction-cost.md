--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-15 04:56:05.218910644 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 19.17 | 6.07 | 0.64 |
| 10| 7644 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 744 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 747 | 43.59 | 12.49 | 0.63 |
| 4 | 228 | 858 | 52.27 | 14.94 | 0.72 |
| 5 | 283 | 974 | 64.24 | 18.28 | 0.84 |
| 6 | 340 | 1081 | 75.22 | 21.21 | 0.96 |
| 7 | 393 | 1196 | 82.80 | 23.50 | 1.04 |
| 8 | 450 | 1307 | 87.45 | 25.01 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1936 | 25.47 | 8.70 | 0.50 |
| 3| 2084 | 27.39 | 9.88 | 0.53 |
| 5| 2371 | 31.49 | 12.36 | 0.60 |
| 10| 3327 | 43.88 | 19.17 | 0.79 |
| 41| 7709 | 98.35 | 54.97 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.50 | 7.30 | 0.41 |
| 2| 800 | 25.44 | 8.77 | 0.45 |
| 3| 927 | 25.03 | 9.30 | 0.46 |
| 5| 1217 | 29.67 | 11.95 | 0.53 |
| 10| 1992 | 38.77 | 17.81 | 0.68 |
| 40| 6604 | 99.24 | 54.64 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.51 | 8.47 | 0.46 |
| 2| 775 | 30.91 | 10.06 | 0.51 |
| 3| 952 | 33.51 | 11.46 | 0.55 |
| 5| 1264 | 34.93 | 13.22 | 0.58 |
| 10| 1994 | 44.86 | 19.36 | 0.74 |
| 36| 6091 | 98.16 | 51.68 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.16 | 0.53 |
| 2| 850 | 36.48 | 11.58 | 0.57 |
| 3| 941 | 37.91 | 12.62 | 0.59 |
| 5| 1258 | 42.68 | 15.29 | 0.66 |
| 10| 2025 | 53.90 | 21.77 | 0.83 |
| 29| 4868 | 98.62 | 46.88 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5797 | 27.04 | 9.08 | 0.69 |
| 2| 5822 | 31.48 | 10.47 | 0.74 |
| 3| 6158 | 45.84 | 15.46 | 0.90 |
| 4| 6293 | 55.87 | 18.88 | 1.01 |
| 5| 6511 | 66.98 | 22.75 | 1.14 |
| 6| 6504 | 72.00 | 24.13 | 1.19 |
| 7| 6685 | 82.25 | 27.68 | 1.31 |
| 8| 6882 | 93.34 | 31.37 | 1.43 |
| 9| 6985 | 98.23 | 33.10 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 40 | 2279 | 7195 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

