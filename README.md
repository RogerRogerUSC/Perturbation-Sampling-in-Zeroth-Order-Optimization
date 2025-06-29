# Perturbation Sampling in Zeroth-Order Optimization

This repo collects academic materials about perturbation sampling/searching methods in zeroth-order optimization (ZOO). Generally, ZOO relies on a fixed Gaussian distribution $\mathcal{N}(0,I)$ to sample perturbations, and all model parameters are perturbed in each query. Based on that, we think about the following two questions and list related literatures as follows. 

## Important Questions & Related Work

### Can we only perturb a subset of parameters? 

- Sparse MeZO: Less Parameters for Better Performance in Zeroth-Order LLM Fine-Tuning [<a href="https://arxiv.org/abs/2402.15751" style="text-decoration: none;">**Arxiv**</a>]
- Zeroth-Order Fine-Tuning of LLMs with Transferable Static Sparsity [<a href="https://openreview.net/pdf?id=myYzr50xBh" style="text-decoration: none;">**ICLR'25**</a>]

### Can we use a distribution that is more efficient than Gaussian? 

The related work in this section primarily focuses on replacing Gaussian by other distributions or utilizing some methods (e.g., evolutionary strategies, reinforcement learning) to explore more efficient searching directions. 

#### Use different distributions or covariance matrices

- Natural Perturbations for Black-box Training of Neural Networks by Zeroth-Order Optimization [<a href="https://openreview.net/pdf?id=ULAQ9GmJlo" style="text-decoration: none;">**ICML'25**</a>]
- Generalizing Gaussian Smoothing for Random Search [<a href="https://arxiv.org/abs/2211.14721" style="text-decoration: none;">**ICML'22**</a>]
- Derivative-Free Optimization via Adaptive Sampling Strategies [<a href="https://arxiv.org/abs/2404.11893" style="text-decoration: none;">**Arxiv**</a>]

#### Use evolutionary strategies

- Adaptive Evolution Strategies for Stochastic Zeroth-Order Optimization [<a href="https://ieeexplore-ieee-org.ezproxy.rit.edu/abstract/document/9718120" style="text-decoration: none;">**IEEE Transactions on Emerging Topics in Computational Intelligence**</a>]
- Guided evolutionary strategies: augmenting random search with surrogate gradients [<a href="https://proceedings.mlr.press/v97/maheswaranathan19a/maheswaranathan19a.pdf" style="text-decoration: none;">**ICML'19**</a>]

#### RL-based methods
- Learning Sampling Policy to Achieve Fewer Queries for Zeroth-Order Optimization [<a href="https://proceedings.mlr.press/v238/zhai24a/zhai24a.pdf" style="text-decoration: none;">**AISTATS'24**</a>]

#### Model-based methods
- Learning to Learn by Zeroth-Order Oracle [<a href="https://arxiv.org/pdf/1910.09464" style="text-decoration: none;">**ICLR'20**</a>]
