# Generalization - an issue in Sketch map alignment

This repository contains the data and code required for reproducing the results of the paper "Generalization - an issue in sketch map alignment". 

## About the experiment

The experiment was conducted as a part of the research to analyse if participants agree among themselves in classifying generalized and non-generalized features of a sketch map. A total of 11 sketch maps were created and participants had to mark the features of sketch map in either green if non-generalized or yellow if generalized after comparing it with metric map data. They aslo had to mark features in metric map with orange if its not drawn in sketch map. A total of five participants classified the features of map. We found that there is a high agreement among the participants. The data and script used for arriving at this conclusion  can be found in this repository.

## Data

The AgreementData-Copy.xlsx has total of 10 columns. The column C,D,E,F,G is the color given by each participant - P1,P2,P3,P4,P5 for different features. Sheet 1 corresponds to colorisation of sketch maps and sheet 2 --> metric maps.

## Script

The script calculates the Prevalance and Bias Adjusted Kappa (PABAK) for getting agreement score. 
## For running the script:

1. you can either directly click on [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CharuManivannan/Generalization---an-issue-in-Sketch-map-alignment/HEAD?urlpath=rstudio)

    On the right side, in the files tab, please select "Agreementanalysis.Rmd" and Click Run --> Run all.

2. If the binder does not work for you, you can also download the github repository. Unzip the folder.This method requires you to download R studio Version 1.4.1106. Open R studio --> Open install.R --> run. This will install all the required packages. Open "Agreementanalysis.Rmd" and either knit or run --> run all.


  [1]: https://github.com/CharuManivannan/Generalization---an-issue-in-Sketch-map-alignment
  
  
  
 On successful running of the script, you should be able to get two results . One is the pabak analysis for sketch map and the other is for metric map. Both of these values are found in Table 8 of the paper.
