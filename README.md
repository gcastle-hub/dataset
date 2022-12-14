# dataset
The following are F1-scores  of some competitive causal discovery algorithms on the real-world alarm datasets used in PCIC Competition 2021.

![image](https://github.com/gcastle-hub/dataset/blob/master/metric_def.png)

where P is the set of all directed edges in the learned causal graph G and S is the set of ground-truth edges.

We believe the best performance in the following table is the SOTA , welcome to contact us to update this table if you have got the better performance using another public algorithms.  
|  Alogorithm  | 18V_55N_Wireless | 24V_439N_Microwave | 25V_474N_Microwave | paper                                                          |
|--------------| ---------------- | ------------------ | ------------------ | ------------------------------------------------------------------- |
| PC           | 0.4299           | 0.2270              | 0.1923             | [link](https://philarchive.org/archive/SPICPA-2)                            |
| DirectLiNGAM | 0.1609           | 0.0625             | 0.0761             | [link](https://www.jmlr.org/papers/volume12/shimizu11a/shimizu11a.pdf)      |
| ICALiNGAM    | 0.1915           | 0.0513             | 0.0442             | [link](https://www.jmlr.org/papers/volume12/shimizu11a/shimizu11a.pdf)      |
| GES          | 0.3393           | 0.3054             | 0.2008             | [link](https://www.jmlr.org/papers/volume3/chickering02b/chickering02b.pdf) |
| NOTEARS      | 0.1957           | 0.1435             | 0.1441             | [link](https://arxiv.org/abs/1803.01422)                                    |
| ADM4         | 0.4074           | 0.2620              | 0.2518             | [link](https://proceedings.mlr.press/v31/zhou13a.html)                      |
| MLE_SGL      | 0.3739           | 0.3252             | 0.3050              | [link](https://arxiv.org/abs/1602.04511)                                    |
| PCMCI        | 0.4226           | 0.3268             | 0.2919             | [link](https://www.science.org/doi/10.1126/sciadv.aau4996)                  |
| THP          | 0.5765           | 0.3719             | 0.3387             | [link](https://arxiv.org/pdf/2105.10884.pdf)                                |

