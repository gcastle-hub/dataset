# Dataset
The following table contains F1-scores of some competitive causal discovery algorithms on the real-world alarm datasets used in the PCIC competition 2021.

We believe the THP algorithm (last line) is the current SOTA. You are welcome to contact us if you have another (public) algorithm that obtains good scores and we will add it to the table.

|  Algorithm   | 18V_55N_Wireless | 24V_439N_Microwave | 25V_474N_Microwave | Reference                                                                   |
|--------------| ---------------- | ------------------ | ------------------ | --------------------------------------------------------------------------- |
| PC           | 0.4299           | 0.2270             | 0.1923             | [link](https://philarchive.org/archive/SPICPA-2)                            |
| DirectLiNGAM | 0.1609           | 0.0625             | 0.0761             | [link](https://www.jmlr.org/papers/volume12/shimizu11a/shimizu11a.pdf)      |
| ICALiNGAM    | 0.1915           | 0.0513             | 0.0442             | [link](https://www.jmlr.org/papers/volume12/shimizu11a/shimizu11a.pdf)      |
| GES          | 0.3393           | 0.3054             | 0.2008             | [link](https://www.jmlr.org/papers/volume3/chickering02b/chickering02b.pdf) |
| NOTEARS      | 0.1957           | 0.1435             | 0.1441             | [link](https://arxiv.org/abs/1803.01422)                                    |
| ADM4         | 0.4074           | 0.2620             | 0.2518             | [link](https://proceedings.mlr.press/v31/zhou13a.html)                      |
| MLE_SGL      | 0.3739           | 0.3252             | 0.3050             | [link](https://arxiv.org/abs/1602.04511)                                    |
| PCMCI        | 0.4226           | 0.3268             | 0.2919             | [link](https://www.science.org/doi/10.1126/sciadv.aau4996)                  |
| THP          | <b>0.5765</b>    | <b>0.3719</b>      | <b>0.3387</b>      | [link](https://arxiv.org/pdf/2105.10884.pdf)                                |



The F1-score is defined as follows:

![image](https://github.com/gcastle-hub/dataset/blob/master/metric_def.png)  
where P is the set of all directed edges in the learned causal graph G and S is the set of ground-truth edges.
