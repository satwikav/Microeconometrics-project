## Microeconometrics Project: Replication of High-Dimensional Methods and Inference on Structural and Treatment Effects
The [Jupyter notebook](https://github.com/HumanCapitalAnalysis/microeconometrics-course-project-satwikav/blob/master/replication_vysetty.ipynb) in this repository replicates results of the [article](https://www.aeaweb.org/articles?id=10.1257/jep.28.2.29): 
*Belloni, Alexandre and Chernozhukov, Victor and Hansen, Christian. 2014. "High-Dimensional Methods and Inference on Structural and Treatment Effects." Journal of Economic Perspectives, 28 (2): 29-50.*

Unfortunately, there is some issue in the way the notebook appears in this repository. The best way to view it is to download the repository or through </a> <a href="https://mybinder.org/v2/gh/HumanCapitalAnalysis/microeconometrics-course-project-satwikav/master?filepath=replication_vysetty.ipynb" target="_parent"> <img src="https://mybinder.org/badge_logo.svg" width="109" height="20"> </a> 

### **Article summary**
<p align="justify">
Belloni et al. (2014) in their paper explain the use of data mining techniques for high-quality inference. Machine learning techniques perform well for predictions but may lead to incorrect conclusions when it comes to inference. In cases of high-dimensionality, the researcher is faced with the problem of selecting controls or selecting instruments which could possibly lead to endogeneity if any relevant variables are excluded.  Given such a scenario, in their paper, they suggest using a model section technique called LASSO (Least Absolute Shrinkage and Selection Operator) for better inference of model parameters. The authors present three empirical examples that represent three different scenarios. In the first example, the scenario is a model selection where there are too many instruments. In the second example, the scenario is a model selection where there are too many controls. In the third example, the scenario is a model selection where there are too many controls in the case of an instrumental variable approach.
</p>

### **Replication summary**
<p align="justify">
The authors used STATA for their empirical analysis. The replication of this paper is done in Python using JupyterLab. As mentioned previously, the authors use three empirical examples where they implement their method (LASSO) and compare their results to the baseline regressions. I have replicated the results of baseline regressions as well as regressions that implement the authors' method and added some additional visualizations for each of the three examples discussed in the paper. In the first bit of my notebook, I explained what is high-dimensionality, why there is a need to regularise, and how to implement the authors' idea. The next bit of the notebook is divided into separate sections according to the empirical examples.
</p>

### **Reproducibility**
Reproducibility of the project is ensured via [Travis CI](https://travis-ci.org/github/HumanCapitalAnalysis/microeconometrics-course-project-satwikav)
[![Build Status](https://travis-ci.org/HumanCapitalAnalysis/microeconometrics-course-project-satwikav.svg?branch=master)](https://travis-ci.org/HumanCapitalAnalysis/microeconometrics-course-project-satwikav)     

### **References**
* [Acemoglu, Johnson and Robinson. 2001. "The Colonial Origins of Comparative Development: An Empirical Investigation." American Economic Review 91 (5): 1369–1401.](https://www.aeaweb.org/articles?id=10.1257/aer.91.5.1369)
* [Donohue and Levitt. 2001. "The Impact of Legalized Abortion on Crime." Quarterly Journal of Economics 116 (2): 379–420](https://academic.oup.com/qje/article-abstract/116/2/379/1904158?redirectedFrom=fulltext)
* [Chen and Yeh. 2012. "Growth under the Shadow of Expropriation? The Economic Impacts of Eminent Domain."](http://www.sole-jole.org/13463.pdf)
* Wooldridge. 2012. "Introductory Econometrics : a Modern Approach."
* James, Witten, Hastie and Tibshirani. 2013. "An Introduction to Statistical Learning with Applications in R."
* [Belloni, Chernozhukov and Hansen. 2014. "High-Dimensional Methods and Inference on Structural and Treatment Effects." Journal of Economic Perspectives, 28 (2): 29-50](https://www.aeaweb.org/articles?id=10.1257/jep.28.2.29)

---
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/HumanCapitalAnalysis/microeconometrics-course-project-satwikav/blob/master/LICENSE) 
</a> <a href="https://nbviewer.jupyter.org/github/HumanCapitalAnalysis/microeconometrics-course-project-satwikav/blob/master/replication_vysetty.ipynb" target="_parent"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.png" width="109" height="20"> </a>