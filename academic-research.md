# Causal Inference Academic Research

The following is a list of academic research papers in Causal Inference, sorted by topic and date. 

- [Potential Outcomes](#potential-outcomes)
- [Dyrected Acyclic Graphs](#dyrected-acyclic-graphs)
- [Experimental Methods](#experimental-methods)
  - [Conditional Average Treatment Effects](#conditional-average-treatment-effects)
  - [Policy Learning](#policy-learning)
  - [Adaptive Experiments](#adaptive-experiments)
  - [Optimal Stopping](#optimal-stopping)
  - [Interference](#interference)
- [Quasi-Experimental Methods](#quasi-experimental-methods)
  - [Unconfoundedness](#unconfoundedness)
  - [Panel Methods](#panel-methods)
  - [Instrumental Variables](#instrumental-variables)
  - [Regression Discontinuity](#regression-discontinuity)

**Note for curators**: differently from most other sections, the aim of this list is *not* to be exhaustive, but to cover most of the *established* research. Occasionally, I might include working papers, if deemed particularly worth of attention. Also, my background is in econometrics and potential outcomes framework, therefore the literature on, among others, Directed Acyclic Graphs or Bandits is severily underrepresented.



## Potential Outcomes

- [Natural Experiments](https://arxiv.org/pdf/2002.00202.pdf) - Titiunik (2020)

- [Causal Inference Using Potential Outcomes](https://www.tandfonline.com/doi/abs/10.1198/016214504000001880) - Rubin (2005)

- [Estimating Causal Effects of Treatments in Randomized and Nonrandomized Studies](http://www.fsb.muohio.edu/lij14/420_paper_Rubin74.pdf) - Rubin (1974)



## Dyrected Acyclic Graphs

- [A Crash Course in Good and Bad Controls](https://journals.sagepub.com/doi/full/10.1177/00491241221099552) - Cinelli, Forney, Pearl (2022)

- [Causal Diagrams for Empirical Research](https://academic.oup.com/biomet/article/82/4/669/251647) - Pearl (1995)



## Experimental Methods



### Conditional Average Treatment Effects

- [Empirical Analysis of Model Selection for Heterogeneous Causal Effect Estimation](https://arxiv.org/pdf/2211.01939.pdf) - Mahajan, Mitliagkas, Neal, Syrgkanis (2022)

- [Towards Optimal Doubly Robust Estimation of Heterogeneous Causal Effects](https://arxiv.org/pdf/2004.14497.pdf) - Kennedy (2022) [[Video](https://www.youtube.com/watch?v=AUOnAfUjDVE)]

- [Machine Learning Estimation of Heterogeneous Causal Effects: Empirical Monte Carlo Evidence](https://arxiv.org/pdf/1810.13237.pdf) - Knaus, Lechner, Strittmatter (2021)

- [Quasi-Oracle Estimation of Heterogeneous Treatment Effects](https://arxiv.org/pdf/1712.04912.pdf) - Nie, Wager (2020)

- [Adapting Neural Networks for the Estimation of Treatment Effects](https://arxiv.org/pdf/1906.02120.pdf) - Shi, Blei, Veitch (2019)

- [Meta-learners for Estimating Heterogeneous Treatment Effects using Machine Learning](https://arxiv.org/pdf/1706.03461.pdf) - Künzel, Sekhon, Bickel, Yu (2017)

- [Double/Debiased Machine Learning for Treatment and Structural Parameters](https://arxiv.org/pdf/1608.00060.pdf) - Chernozhukov, Chetverikov, Demirer, Duflo, Hansen, Newey, Robins (2017)



### Policy Learning

- [Policy Learning with Observational Data](https://arxiv.org/pdf/1702.02896.pdf) - Athey, Wager (2020)



### Adaptive Experiments

- [Estimation Considerations in Contextual Bandits](https://arxiv.org/pdf/1711.07077.pdf) - Dimakopoulou, Zhou, Athey, Imbens (2018)

- [Causal Bandits: Learning Good Interventions via Causal Inference](https://arxiv.org/pdf/1606.03203.pdf) - Lattimore, Lattimore, Reid (2016)

- [Asymptotically Efficient Adaptive Allocation Rules](https://www.sciencedirect.com/science/article/pii/0196885885900028) - Lai, Robbins (1985)




### Optimal Stopping

- [Time-uniform, Nonparametric, Nonasymptotic Confidence Sequences](https://arxiv.org/abs/1810.08240.pdf) Howard, Ramdas, McAuliffe, Sekhon - (2020)

- [Discrete Sequential Boundaries for Clinical Trials](https://www.jstor.org/stable/2336502) - Lan, DeMets (1993)

- [Optimum Character of the Sequential Probability Ratio Test](https://www.jstor.org/stable/2235638) - Wald, Wolfowitz (1948)

- [Sequential Tests of Statistical Hypotheses](https://www.jstor.org/stable/2235829) - Wald (1945)



### Interference

- [Exact P-values for Network Interference](https://arxiv.org/pdf/1506.02084.pdf) - Athey, Eckles, Imbens (2018)

- [Estimating Average Causal Effects Under General Interference, with Application to a Social Network Experiment](https://arxiv.org/pdf/1305.6156.pdf) - Aronow, Samii (2018)

- [On causal Inference in the Presence of Interference](https://journals.sagepub.com/doi/pdf/10.1177/0962280210386779) - Tchetgen Tchetgen, VanderWeele (2012)

- [Toward Causal Inference With Interference](https://www.tandfonline.com/doi/abs/10.1198/016214508000000292) - Hudgens, Halloran (2012)

- [Identification of Endogenous Social Effects: The Reflection Problem](https://academic.oup.com/restud/article/60/3/531/1570385) - Manski (1996)





## Quasi-experimental Methods



### Unconfoundedness

- [Matching on the Estimated Propensity Score](https://onlinelibrary.wiley.com/doi/abs/10.3982/ECTA11293) - Abadie, Imbens (2016)

- [Genetic matching for estimating causal effects: A general multivariate matching method for achieving balance in observational studies](https://www.jstor.org/stable/43554804) - Diamond, Sekhon (2013)

- [Large Sample Properties of Matching Estimators for Average Treatment Effects](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1468-0262.2006.00655.x) - Abadie, Imbens (2006)

- [Nonparametric Estimation of Average Treatment Effects Under Exogeneity: A Review](https://direct.mit.edu/rest/article/86/1/4/57476/Nonparametric-Estimation-of-Average-Treatment) - Imbens (2004)

- [Efficient Estimation of Average Treatment Effects Using the Estimated Propensity Score](https://onlinelibrary.wiley.com/doi/abs/10.1111/1468-0262.00442) - Hirano, Imbens, Ridder (2003)

- [Reducing Bias in Observational Studies Using Subclassification on the Propensity Score](https://www.tandfonline.com/doi/abs/10.1080/01621459.1984.10478078) - Rosenbaum, Rubin (1984)

- [The Central Role of the Propensity Score in Observational Studies for Causal Effects](https://academic.oup.com/biomet/article/70/1/41/240879) - Rosenbaum, Rubin (1983)


### Panel Methods

- [What’s Trending in Difference-in-Differences? A Synthesis of the Recent Econometrics Literature](https://arxiv.org/pdf/2201.01194.pdf) - Roth, Sant'Anna, Bilinski, Poe (2023)

- [Synthetic Difference In Differences Estimation](https://arxiv.org/pdf/2301.11859.pdf) - Clarke, Pailañir, Athey, Imbens (2023) [[Video](https://www.youtube.com/watch?v=r2DzGAigTl4)]

- [Matrix Completion Methods for Causal Panel Data Models](https://arxiv.org/pdf/1710.10251.pdf) - Athey, Bayati, Doudchenko, Imbens, Khosravi (2022)

- [Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects](https://par.nsf.gov/servlets/purl/10331930) - Abadie (2021)

- [Panel Data Models With Interactive Fixed Effects](https://onlinelibrary.wiley.com/doi/abs/10.3982/ECTA6135) - Bai (2009)



### Instrumental Variables

- [Locally Robust Semiparametric Estimation](https://arxiv.org/pdf/1608.0003.pdf) - Chernozhukov, Escanciano, Ichimura, Newey, Robins (2022)

- [Identification and Estimation of Local Average Treatment Effects](https://www.jstor.org/stable/2951620) - Angrist, Imbens (1994) 

- [Identification of Causal Effects Using Instrumental Variables](https://www.tandfonline.com/doi/abs/10.1080/01621459.1996.10476902?journalCode=uasa20) - Angrist, Imbens, Rubin (1993)

- [Efficient Instrumental Variables Estimation of Nonlinear Models](https://www.jstor.org/stable/2938351) - Newey (1990)

- [The Nonlinear Two-stage Least-squares Estimator](https://www.sciencedirect.com/science/article/abs/pii/0304407674900335) - Amemiya (1974)

- [The Statistical Implications of a System of Simultaneous Equations](https://www.jstor.org/stable/1905714) - Haavelmo (1943)



### Regression Discontinuity

- [Inference in Regression Discontinuity Designs with a Discrete Running Variable](https://arxiv.org/pdf/1606.04086.pdf) - Kolesár, Rothe (2018)

- [Optimized Regression Discontinuity Designs](https://arxiv.org/pdf/1705.01677.pdf) - Imbens, Wager (2018)

- [Identification and Estimation of Treatment Effects with a Regression-Discontinuity Design](https://www.jstor.org/stable/pdf/2692190.pdf) - Hahn, Todd, Van der Klaauw (2001)



## Misc

- [Design and Analysis of Switchback Experiments](https://arxiv.org/pdf/2009.00148.pdf) - Bojinov, Simchi-Levi, Zhao (2022)

- [Targeted Maximum Likelihood Estimation for Causal Inference in Observational Studies](https://academic.oup.com/aje/article/185/1/65/2662306) - Schuler, Rose (2017)

- [Targeted Maximum Likelihood Learning](https://www.degruyter.com/document/doi/10.2202/1557-4679.1043/html) - van der Laan, Rubin (2006)

- [Identifiability and Exchangeability for Direct and Indirect Effects](https://journals.lww.com/epidem/abstract/1992/03000/identifiability_and_exchangeability_for_direct_and.13.aspx) - Robins, Greenland (1993)



