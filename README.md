# Predicting the distances to galaxies with photometric redshift via regression

# Overview
Measuring the distances to galaxies are often a necessary measurement in various areas of astrophysics research, for example in gravitational lensing. One method, known as spectroscopic redshift, yields accurate results but are very time-consuming and costly, making it impractical to employ on large scales.

In this project, we make use of photometry data, and train various regression models to predict the distances of galaxies. The features are the brightness (or magnitude) of galaxies at five different colored filters, along with their corresponding uncertainties. With spectroscopy data, the distances to a small subset of galaxies were determined, which make up our labels. We can then proceed to train suitable regression models on our data to predict the distances to the remaining galaxies, without the need to employ spectroscopy across the entire set.


# Python and package versions
(.yml file included in repo)
  - python=3.7.8
  - numpy=1.18.5
  - pandas=1.0.5
  - scikit-learn=0.23.1
  - matplotlib=3.2.2
  - py-xgboost=1.1.1
  - shap=0.35.0
