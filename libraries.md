# Causal Inference Libraries

The following is a list of causal inference libraries, ordered by (open source) language.



## Python

- [Statsmodels](https://github.com/statsmodels/statsmodels)
![downloads](https://img.shields.io/pypi/dm/statsmodels)
![stars](https://img.shields.io/github/stars/statsmodels)
  - [regression](https://www.statsmodels.org/stable/regression.html) - Linear regression models
  - [tsa](https://www.statsmodels.org/stable/tsa.html) - Time series analysis
  - [duration](https://www.statsmodels.org/stable/duration.html) - Survival and duration models
  - [nonparametric](https://www.statsmodels.org/stable/nonparametric.html) - Nonparametric methods
  - [gmm](https://www.statsmodels.org/stable/gmm.html) - Generalized method of moments
  - [stats](https://www.statsmodels.org/stable/stats.html) - Statistical tests and tools
  
- [Linearmodels](https://github.com/bashtage/linearmodels/) (extension of Statsmodels)
![downloads](https://img.shields.io/pypi/dm/linearmodels)
![stars](https://img.shields.io/github/stars/bashtage/linearmodels)
  - [iv](https://bashtage.github.io/linearmodels/iv/index.html) - Instrumental variables
  - [panel](https://bashtage.github.io/linearmodels/panel/index.html) - Panel data models
  - [system](https://bashtage.github.io/linearmodels/system/index.html) - System regression models (e.g. seemingly unrelated regressions)

- [DoWhy](https://github.com/py-why/dowhy)
![downloads](https://img.shields.io/pypi/dm/dowhy)
![stars](https://img.shields.io/github/stars/py-why/dowhy)

- [EconML](https://github.com/py-why/EconML)
![downloads](https://img.shields.io/pypi/dm/econml)
![stars](https://img.shields.io/github/stars/py-why/econml)
  - [dml](https://econml.azurewebsites.net/spec/estimation/dml.html) - Double machine learning
  - [dr](https://econml.azurewebsites.net/spec/estimation/dr.html) - Doubly robust learning
  - [forest](https://econml.azurewebsites.net/spec/estimation/forest.html) - Causal forests
  - [metalearners](https://econml.azurewebsites.net/spec/estimation/metalearners.html) - S-, T-, X-learners [[Paper](https://arxiv.org/pdf/1706.03461.pdf)]
  - [iv.dml]() - Double machine learning with instrumental variables
  - [iv.nnet](https://econml.azurewebsites.net/spec/estimation/deepiv.html) - Deep instrumental variables
  - [dynamic_dml](https://econml.azurewebsites.net/spec/estimation/dynamic_dml.html) - Dynamic double machine learning

- [CausalML](https://github.com/uber/causalml)
![downloads](https://img.shields.io/pypi/dm/causalml)
![stars](https://img.shields.io/github/stars/uber/causalml)
  - [inference.tree](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.inference.tree) - Tree-based uplift models [[Docs](https://causalml.readthedocs.io/en/latest/methodology.html#tree-based-algorithms)]
  - [inference.meta](https://causalml.readthedocs.io/en/latest/methodology.html#meta-learner-algorithms) - S-, T-, X-, R-, DR-, TMLE-learners [[Docs](https://causalml.readthedocs.io/en/latest/methodology.html#meta-learner-algorithms)]
  - [inference.iv](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.inference.iv) - Doubly-robust instrumental variables [[Docs](https://causalml.readthedocs.io/en/latest/methodology.html#doubly-robust-instrumental-variable-driv-learner)]
  - [match](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.match) - Matching
  - [propensity](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.propensity) - Propensity score estimation

- [causal-learn](https://github.com/py-why/causal-learn) - Causal discovery

- [causal-tune](https://github.com/py-why/causaltune) - AutoML for causal inference

- [CausalNex](https://github.com/quantumblacklabs/causalnex/)

- [GLuM](https://github.com/Quantco/glum/) - Fast generalized linear models

- [pyhdfe](https://github.com/jeffgortmaker/pyhdfe) - Fast high-dimensional fixed effect orthogonalization algorithm

- [DoubleML](https://github.com/DoubleML/doubleml-for-py) - Double/debiased machine learning [[Paper](https://arxiv.org/pdf/1608.00060)] [[Video](https://www.youtube.com/watch?v=ErecsyKEq74)]

- [DeepIV](https://github.com/jhartford/DeepIV) - Deep learning for instrumental variables estimation [[Paper](https://proceedings.mlr.press/v70/hartford17a/hartford17a.pdf)]

- [ananke](https://ananke.readthedocs.io/en/latest/) - Causal inference with DAGs

- [scikit-uplift](https://github.com/maks-sh/scikit-uplift) - Basic meta-learner and uplift tools

- [CausalPy](https://github.com/pymc-labs/CausalPy) - Causal inference in quasi-experimental settings



## R

- [FixEst](https://github.com/lrberge/fixest) - Fast high-dimensional fixed effect regression

- [CausalImpact](https://github.com/google/CausalImpact)

- [GRF](https://github.com/grf-labs/grf/) - Generalized random forests 

- [alpaca](https://github.com/amrei-stammann/alpaca) - Generalized linear models with high-dimensional fixed effects

- [DAGitty](https://github.com/jtextor/dagitty) - [[Video](https://www.youtube.com/watch?v=LCC4BkLZo-g)]

- [synthdid](https://github.com/synth-inference/synthdid) - Synthetic difference in differences [[Paper](https://arxiv.org/pdf/2301.11859.pdf)]

- [ggdag](https://github.com/r-causal/ggdag) - Visualizing and analyzing causal DAGs

- [pcalg](https://cran.r-project.org/web/packages/pcalg/index.html) - Causal structure learning and causal inference using DAGs


## Julia

- [Causalinference](https://github.com/mschauer/CausalInference.jl) 

- [FixedEffectModels](https://github.com/FixedEffects/FixedEffectModels.jl) - Fast high-dimensional fixed effect regression
