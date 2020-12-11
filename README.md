# BayesianPCA

Implementation of Bayesian PCA based on the original paper by Bishop [1].

This project was done as part of a course on Bayesian Learning, taught by [Remi Bardenet](http://rbardenet.github.io/) as part of the [Master Data Science](https://sciences-technologies.univ-lille.fr/mathematiques/formation/master-mention-sciences-des-donnees/) at the University of Lille.

## Install

To install simply clone the project  :
```bash
git clone https://github.com/MaxenceGiraud/BayesianPCA
cd BayesianPCA
```

## Usage

```python
import bayespca

## Original PCA
p = bayespca.PCA(n_components = 2)
p.fit_transform(X)
```

## TODO
- [x] Implement original PCA
- [ ] Probabilistic PCA
- [ ] Bayesian PCA
- [ ] Build Mixtures of Bayesian PCA

## References

[1] Bishop, C. M. (1999). Bayesian PCA. MIT Press.     
[2] Tipping, M. E . and C. M. Bishop (1997). Probabilistic principal component analysis. Journal of the Royal Statistical Society, B.