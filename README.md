# Viscosity_of_magmatic_melts
Melt geochemistry-based Viscosity model employed in the PhD thesis: `Post-caldera eruptions and pyroclastic density current hazards in the Main Ethiopian Rift'. By Ben Clarke (University of Edinburgh). 

The Jupyter Notebook provides a model to calculate the viscosity of magmatic liquids based on their major element oxide geochemistry. The model will automatically detect a peralkaline melt and apply the peralkaline rhyolite calibrations as defined by di Genova et al.'s 2013 paper. Otherwise, the standard coefficients defined in Giordano et al. (2008) will be used. 

To use the model for your own compositions:

1. Be sure that your composition and physical conditions lies within the ranges used to calibrate either Giordano's or di Genova's studies
2. Fill in the relevant oxide weight percentages for your melt
3. Assign the lower and upper temperatures between which you wish to investigate
4. Assign a list or range of water concentrations (in weight percent), you wish to investigate

The results are displayed as a plot, where each curve represents a distinct viscosity-temperature relationship for the specific water concentration.

-------------------------
Added by [Callum Rollo](https://github.com/callumrollo)

### Run from your browser

Click the button below to launch an interactive version of this notebook in your browser

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/callumrollo/Viscosity_of_magmatic_melts/master?filepath=magmatic_melt_viscosity_caluclator.ipynb)

May take a few minutes to load. Edits you make in the browser will not persist! Each click of the button launches a clean version of the notebook in a new tab.

### Download and run locally
 1. Clone/download a zip of the repo
 2. Install [Anaconda](https://www.anaconda.com/products/individual) for you OS
 3. Creat and activate the environment in the .yml file of this repo
 4. Launch jupyter notebooks
