# Approximate Bayesian Computation (ABC) for Modelling the COVID-19 Pandemic in the United States of America

**Abstract:** 
Approximate Bayesian Computation (ABC) allows for approximation of the posterior distribution under an intractable or computationally expensive likelihood function. This, along with the fact that ABC can be used even when available data is coarse or complex, makes application of the algorithm suited to infectious disease modelling. Even in other fields, ABC has successfully been applied where more traditional methods such as Markov chain Monte Carlo (MCMC) quickly become infeasible. In this work, the most basic ABC algorithm and a modified Sequential Monte Carlo (SMC) ABC algorithm are implemented for parameter estimation of COVID-19 data in three U.S. states under the stochastic spatial SEIR framework. By using the R package ABSEIR, such simulation studies are conducted and analysed, along with previous theoretical studies, to determine the ability of the algorithms and the SEIR models, to model the pandemic both in an accurate and computationally efficient manner.

* Files in the [extras/](extras) directory were used during initial stages of the project for exploratory analysis and familiarisation of the utilised R Package ([ABSEIR](https://github.com/grantbrown/ABSEIR))
* Files in the Florida (Non-Spatial Analysis) and Spatial Analysis directories contain the final R scripts 
* The complete dissertation can be found [here](https://github.com/2oe-g/dissertation/blob/d8c8e869a382214c32c98d082c0f1e94a16b6ccf/ZoeGaness_Dissertation.pdf)

Grade Awarded: 67% (Merit)
