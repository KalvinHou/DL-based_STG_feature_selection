# Tasks



### 1. To learn

- [x] Git and GitHub
- [x] Markdown



#### 2. Research Tasks

- [x] Feature selection: https://www.jmlr.org/papers/volume3/guyon03a/guyon03a.pdf

- [x] Find all papers related to feature selection (2019-2021)

  > feature selection, subset selection, variable selection, select, subset

  - [x] AAAI,  AAAI conference is to promote research in artificial intelligence
  - [x] ICML, International Conference on Machine Learning
  - [x] NeurIPS, Neural Information Processing Systems
  - [x] IJCAI, International Joint Conference on Artificial Intelligence
  - [x] ICLR, International Conference on Learning Representations 
  - [x] IJCNN, International Joint Conference on Neural Networks
  - [x] ICPR, International Conference on Pattern Recognition
  - [x] AISTATS, International Conference on Artificial Intelligence and Statistics
  - [x] IEEE Transactions on Neural Networks and Learning Systems
  - [x] IEEE Transactions on Pattern Analysis and Machine Intelligence
  - [x] Journal of Machine Learning Research

- [ ] Summarize popular benchmarking datasets for feature selection

  * Which are they?
  * How often have they been used in literature?
  * Datasets details
    * links?
    * feature dimension and dataset size
    * types, i.e. image? text? extracted features?

- [ ] Double check of reproduced feature selection methods

- [ ] Reproduce (at least) two other methods



#### Long Vision

open source library

```python
import fslearn

fm = fslearn.FM()
fm.fit(X, Y)
fm.show_selection()
```

