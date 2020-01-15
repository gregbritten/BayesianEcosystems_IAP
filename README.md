# BayesianEcosystems_IAP
Notes and code for Bayesian ecosystem modeling IAP course

## Schedule
**Session #1**: Jan 16
 * Installing PyStan
 * Introduce ecosystem equations
 * Simulate from the ecosystem model
 * Generate synthetic observations
 * First fit of the model to data in Stan
 
**Session #2**: Jan 23
 * How to plot and analyze output from a Bayesian analysis
 * How to make Bayesian predictions from a Bayesian model
 * Analyze how parameter and prediction uncertainty varies with size and dimension of observational dataset
 
**Session #3**: Jan 30
 * Extend the plankton ecosystem model to include a fish population
 * Fit the model to plankton + fish populations
 * Use the fitted model to make predictions (and quantify uncertainty!) about the amount of fishing the ecosystem can support

## Installing PyStan

If you are using Anaconda, it recommended that you first update conda by issuing

`conda update --all`

and then issue

`conda install pystan`

If you are not using Anaconda, issue

`pip install pystan`

## Installing Jupyter Notebooks

Jupyter notebooks should already be installed if you are using Anaconda. 
You should be able navigate to the directory containing your notebooks and issue

`jupyter notebook`

to launch the interactive notebooks in a browser window.

If you are using Python 3 without Anaconda, you can install jupyter notebooks via

`pip3 install jupyter`

If you are using Python 2 without Anaconda, you can install jupyter notebooks via

`pip install jupyter`

then you can navigate to the directory containing your notebooks and issue

`jupyter notebook`
