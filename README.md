# DisGNN_rebuttal


Table info: The training time, inference time, and GPU memory consumption of random batches of 32 molecules (16 molecules for GemNet) from the original MD17 dataset. The format is training time in ms, inference time in ms, and inference GPU memory consumption in MB.

|  | 2-F-DisGNN | DimeNet | DimeNet_dense | 3-E-DisGNN | GemNet | TorchMD | GNN-LF |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Aspirin | 232/56/3644 | 727/133/5790 | 378/101/3886 | OOM/OOM/OOM | 2823/612/15980 | 188/32/2065 | 65/10/2791 |
| Benzene | 125/26/2134 | 669/94/1831 | 370/98/1876 | 383/90/6124 | 2242/393/3761 | 478/33/918 | 29/8/95 |
| Ethanol | 114/18/1852 | 672/95/784 | 373/104/1568 | 192/41/3438 | 2256/344/1565 | 417/32/532 | 59/8/54 |
| Malonaldehyde | 88/16/1852 | 657/88/784 | 369/96/1568 | 194/41/3438 | 2237/355/1565 | 753/32/532 | 57/7/68 |
| Naphthalene | 185/42/3140 | 614/112/4470 | 388/105/3032 | OOM/312/17248 | 2613/498/11661 | 265/32/1694 | 61/9/175 |
| Salicylic Acid | 147/33/2640 | 619/92/3489 | 381/109/2384 | OOM/197/12488 | 2577/430/8182 | 239/34/1418 | 59/9/176 |
| Toluene | 134/30/2640 | 595/113/3148 | 372/99/2358 | OOM/164/10528 | 2495/423/7153 | 896/45/1322 | 62/8/176 |
| Uracil | 108/22/2134 | 595/107/1782 | 376/104/1876 | 383/90/6124 | 2165/354/3735 | 118/32/907 | 66/8/99 |
| Average | 142/30/2505 | 643/104/2760 | 376/102/2319 | - | 2426/426/670 | 419/34/1174 | 57/ 9/140 |