--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-04 11:39:02.559710347 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.76 | 4.67 | 0.58 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 99.51 | 31.12 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 169 | 747 | 41.34 | 11.97 | 0.60 |
| 4 | 226 | 862 | 49.42 | 14.28 | 0.69 |
| 5 | 282 | 969 | 61.31 | 17.55 | 0.81 |
| 6 | 339 | 1081 | 71.65 | 20.43 | 0.92 |
| 7 | 392 | 1192 | 72.08 | 20.88 | 0.94 |
| 8 | 448 | 1307 | 83.30 | 24.02 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.29 | 7.69 | 0.48 |
| 2| 1936 | 25.80 | 8.77 | 0.51 |
| 3| 2075 | 26.90 | 9.76 | 0.53 |
| 5| 2395 | 31.11 | 12.27 | 0.60 |
| 10| 3297 | 44.22 | 19.25 | 0.79 |
| 41| 7599 | 97.40 | 54.69 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.81 | 7.37 | 0.42 |
| 2| 826 | 25.13 | 8.69 | 0.45 |
| 3| 898 | 25.52 | 9.47 | 0.46 |
| 5| 1135 | 28.00 | 11.48 | 0.51 |
| 10| 2045 | 41.65 | 18.61 | 0.71 |
| 42| 6541 | 99.04 | 55.88 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.54 | 8.47 | 0.46 |
| 2| 820 | 31.66 | 10.29 | 0.52 |
| 3| 869 | 32.08 | 11.03 | 0.53 |
| 5| 1248 | 35.00 | 13.24 | 0.58 |
| 10| 2083 | 45.76 | 19.62 | 0.75 |
| 36| 6216 | 99.88 | 52.21 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 819 | 35.85 | 11.38 | 0.56 |
| 3| 939 | 37.87 | 12.61 | 0.59 |
| 5| 1262 | 42.68 | 15.29 | 0.66 |
| 10| 2131 | 55.40 | 22.22 | 0.85 |
| 29| 4853 | 98.10 | 46.71 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.05 | 9.07 | 0.69 |
| 2| 5917 | 34.86 | 11.67 | 0.78 |
| 3| 6132 | 45.93 | 15.49 | 0.90 |
| 4| 6338 | 56.14 | 18.96 | 1.02 |
| 5| 6312 | 61.95 | 20.79 | 1.08 |
| 6| 6553 | 73.83 | 24.98 | 1.22 |
| 7| 6695 | 80.68 | 27.16 | 1.29 |
| 8| 6997 | 91.91 | 31.06 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 571 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

