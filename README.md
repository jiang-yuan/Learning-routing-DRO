# Learning to Solve Routing Problems via Distributionally Robust Optimization 

A Distributionally Robust Optimization framework to optimize the peformance on the worst-case groups for routing problems when the training set contains at least two types of distributions. 

## Paper

Yuan Jiang, Yaoxin Wu, Zhiguang Cao, Jie Zhang. [Learning to Solve Routing Problems via Distributionally Robust Optimization](https://arxiv.org/abs/2202.07241). 36th AAAI Conference on Artificial Intelligence (AAAI), 2022.

```
@inproceedings{jiang2022learning,
    author = {Yuan Jiang, Yaoxin Wu, Zhiguang Cao, Jie Zhang},
    booktitle = {36th AAAI Conference on Artificial Intelligence},
    title = {Learning to Solve Routing Problems via Distributionally Robust Optimization},
    year = {2022}
}
```

## Incorporate with deep model

Users are free to integerated with routing deep models like AM and POMO with our framework, then run the corresponding experiments. (Note: The DRO framework is not designed for the training process with only one distribution like Uniform. In this case, it will act the same as the original deep model. )

### Run
```
python3 run.py
```

