# Causal Inference Libraries

The following is a list of causal inference libraries, ordered by language and popularity (stars).

- <img width="18" src="img/icon/python.png"> [Python](#-python)
- <img width="18" src="img/icon/r.png"> [R](#-r)
- <img width="18" src="img/icon/julia.png"> [Julia](#-julia)

## <img width="24" src="img/icon/python.png"> Python

- [Statsmodels](https://github.com/statsmodels/statsmodels)
![stars](https://img.shields.io/github/stars/statsmodels)
  - [regression](https://www.statsmodels.org/stable/regression.html) - Linear regression models
  - [tsa](https://www.statsmodels.org/stable/tsa.html) - Time series analysis
  - [duration](https://www.statsmodels.org/stable/duration.html) - Survival and duration models
  - [nonparametric](https://www.statsmodels.org/stable/nonparametric.html) - Nonparametric methods
  - [gmm](https://www.statsmodels.org/stable/gmm.html) - Generalized method of moments
  - [stats](https://www.statsmodels.org/stable/stats.html) - Statistical tests and tools

- [Linearmodels](https://github.com/bashtage/linearmodels/) (extension of Statsmodels)
![stars](https://img.shields.io/github/stars/bashtage/linearmodels)
  - [iv](https://bashtage.github.io/linearmodels/iv/index.html) - Instrumental variables
  - [panel](https://bashtage.github.io/linearmodels/panel/index.html) - Panel data models
  - [system](https://bashtage.github.io/linearmodels/system/index.html) - System regression models (e.g. seemingly unrelated regressions)

- [DoWhy](https://github.com/py-why/dowhy)
![stars](https://img.shields.io/github/stars/py-why/dowhy)
  - [gcm](https://www.pywhy.org/dowhy/v0.9.1/user_guide/gcm_based_inference/index.html) - Graphical causal model-based inference

- [CausalML](https://github.com/uber/causalml)
![stars](https://img.shields.io/github/stars/uber/causalml)
  - [inference.tree](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.inference.tree) - Tree-based uplift models [[Docs](https://causalml.readthedocs.io/en/latest/methodology.html#tree-based-algorithms)]
  - [inference.meta](https://causalml.readthedocs.io/en/latest/methodology.html#meta-learner-algorithms) - S-, T-, X-, R-, DR-, TMLE-learners [[Docs](https://causalml.readthedocs.io/en/latest/methodology.html#meta-learner-algorithms)]
  - [inference.iv](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.inference.iv) - Doubly-robust instrumental variables [[Docs](https://causalml.readthedocs.io/en/latest/methodology.html#doubly-robust-instrumental-variable-driv-learner)]
  - [match](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.match) - Matching
  - [propensity](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.propensity) - Propensity score estimation

- [EconML](https://github.com/py-why/EconML)
![stars](https://img.shields.io/github/stars/py-why/econml)
  - [dml](https://econml.azurewebsites.net/spec/estimation/dml.html) - Double machine learning
  - [dr](https://econml.azurewebsites.net/spec/estimation/dr.html) - Doubly robust learning
  - [forest](https://econml.azurewebsites.net/spec/estimation/forest.html) - Causal forests
  - [metalearners](https://econml.azurewebsites.net/spec/estimation/metalearners.html) - S-, T-, X-learners [[Paper](https://arxiv.org/pdf/1706.03461.pdf)]
  - [iv.dml](https://econml.azurewebsites.net/spec/estimation/orthoiv.html) - Double machine learning with instrumental variables
  - [iv.nnet](https://econml.azurewebsites.net/spec/estimation/deepiv.html) - Deep instrumental variables
  - [dynamic_dml](https://econml.azurewebsites.net/spec/estimation/dynamic_dml.html) - Dynamic double machine learning

- [CausalNex](https://github.com/quantumblacklabs/causalnex/)
![stars](https://img.shields.io/github/stars/quantumblacklabs/causalnex)
  - [structure](https://causalnex.readthedocs.io/en/latest/03_tutorial/01_first_tutorial.html) - Directed acyclic graph structure learning
  - [network](https://causalnex.readthedocs.io/en/latest/03_tutorial/01_first_tutorial.html#Fitting-the-Conditional-Distribution-of-the-Bayesian-Network) - Bayesian network modeling
  - [evaluation](https://causalnex.readthedocs.io/en/latest/03_tutorial/01_first_tutorial.html#Model-Probability) - Model evaluation
  - [inference](https://causalnex.readthedocs.io/en/latest/03_tutorial/01_first_tutorial.html#Querying-Marginals) - Model inference

- [causal-learn](https://github.com/py-why/causal-learn)
![stars](https://img.shields.io/github/stars/py-why/causal-learn)
  - [search](https://causal-learn.readthedocs.io/en/latest/search_methods_index/index.html) - Search methods for causal discovery

- [CausalPy](https://github.com/pymc-labs/CausalPy)
![stars](https://img.shields.io/github/stars/pymc-labs/CausalPy)
  - [InterruptedTimeSeries](https://causalpy.readthedocs.io/en/latest/notebooks/its_pymc.html) - Interrupted time series
  - [SyntheticControl](https://causalpy.readthedocs.io/en/latest/notebooks/sc_pymc.html#) - Synthetic control methods
  - [DifferenceInDifferences](https://causalpy.readthedocs.io/en/latest/notebooks/did_pymc.html) - Difference-in-differences
  - [RegressionDiscontinuity](https://causalpy.readthedocs.io/en/latest/notebooks/rd_pymc.html#) - Regression discontinuity

- [GLuM](https://github.com/Quantco/glum/)
![stars](https://img.shields.io/github/stars/Quantco/glum)
  - Fast generalized linear models [[Docs](https://glum.readthedocs.io/en/latest/index.html)]

- [causal-tune](https://github.com/py-why/causaltune)
![stars](https://img.shields.io/github/stars/py-why/causaltune)
  - AutoML for causal inference

- [GeoLift](https://github.com/facebookincubator/GeoLift/)
![stars](https://img.shields.io/github/stars/facebookincubator/GeoLift)
  - Uplift modeling for geographical experiments [[Docs](https://facebookincubator.github.io/GeoLift/)]

- [pyhdfe](https://github.com/jeffgortmaker/pyhdfe)
![stars](https://img.shields.io/github/stars/jeffgortmaker/pyhdfe)
  - Fast high-dimensional fixed effect orthogonalization algorithm

- [trimmed_match](https://github.com/google/trimmed_match)
![stars](https://img.shields.io/github/stars/google/trimmed_match)
  - Trimmed match estimator for aggregate geographical experiments [[Paper](https://arxiv.org/abs/2105.07060)]

- [pyfixest](https://github.com/s3alfisc/pyfixest)
![stars](https://img.shields.io/github/stars/s3alfisc/pyfixest)
  - Fast high-dimensional fixed effect regression for , iv and poisson regression following [fixest syntax](https://github.com/lrberge/fixest)
  - Difference-in-Differences with Staggered Adaption: Gardner's 2-stage estimator ("did2s") and Dube et al's (2023) local projections approach [link](https://s3alfisc.github.io/pyfixest/difference-in-differences-estimation/)

- [DoubleML](https://github.com/DoubleML/doubleml-for-py) - Double/debiased machine learning [[Paper](https://arxiv.org/pdf/1608.00060)] [[Video](https://www.youtube.com/watch?v=ErecsyKEq74)]

- [DeepIV](https://github.com/jhartford/DeepIV) - Deep learning for instrumental variables estimation [[Paper](https://proceedings.mlr.press/v70/hartford17a/hartford17a.pdf)]

- [ananke](https://ananke.readthedocs.io/en/latest/) - Causal inference with DAGs

- [scikit-uplift](https://github.com/maks-sh/scikit-uplift) - Basic meta-learner and uplift tools



## <img width="24" src="img/icon/r.png"> R

- [CausalImpact](https://github.com/google/CausalImpact)
![stars](https://img.shields.io/github/stars/google/CausalImpact)
  - Bayesian structural time-series models [[Docs](https://google.github.io/CausalImpact/CausalImpact.html)]

- [Robyn](https://github.com/facebookexperimental/Robyn/)
![stars](https://img.shields.io/github/stars/facebookexperimental/Robyn)
  - Marketing mixed models [[Docs](https://facebookexperimental.github.io/Robyn/)]

- [grf](https://github.com/grf-labs/grf/)
![stars](https://img.shields.io/github/stars/grf-labs/grf)
  - Generalized random forests [[Docs](https://grf-labs.github.io/grf/index.html)]

- [FixEst](https://github.com/lrberge/fixest)
![stars](https://img.shields.io/github/stars/lrberge/fixest)
  - Fast high-dimensional fixed effect regression [[Docs](https://cran.r-project.org/web/packages/fixest/vignettes/fixest_walkthrough.html)]

- [tidyhte](https://github.com/ddimmery/tidyhte)
![stars](https://img.shields.io/github/stars/ddimmery/tidyhte)
  - Tidy-style heterogeneous treatment effect estimation [[Docs](https://ddimmery.github.io/tidyhte/index.html)]

- [alpaca](https://github.com/amrei-stammann/alpaca) - Generalized linear models with high-dimensional fixed effects

- [DAGitty](https://github.com/jtextor/dagitty) - [[Video](https://www.youtube.com/watch?v=LCC4BkLZo-g)]

- [synthdid](https://github.com/synth-inference/synthdid) - Synthetic difference in differences [[Paper](https://arxiv.org/pdf/2301.11859.pdf)]

- [ggdag](https://github.com/r-causal/ggdag) - Visualizing and analyzing causal DAGs

- [pcalg](https://cran.r-project.org/web/packages/pcalg/index.html) - Causal structure learning and causal inference using DAGs



## <img width="24" src="img/icon/julia.png"> Julia

- [Tidier](https://github.com/TidierOrg/Tidier.jl)
![stars](https://img.shields.io/github/stars/TidierOrg/Tidier.jl)
  - Tidyverse port to Julia

- [FixedEffectModels](https://github.com/FixedEffects/FixedEffectModels.jl)
![stars](https://img.shields.io/github/stars/FixedEffects/FixedEffectModels.jl)
  - Fast high-dimensional fixed effect regression

- [Causalinference](https://github.com/mschauer/CausalInference.jl)
![stars](https://img.shields.io/github/stars/mschauer/CausalInference.jl)
  - Causal inference with directed acyclic graphs
