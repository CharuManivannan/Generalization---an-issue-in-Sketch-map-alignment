# Generalization - an issue in Sketch map alignment

This repository contains the data and code required for reproducing the results of the paper "Generalization - an issue in sketch map alignment". 

## About the experiment

The experiment was conducted as a part of the research to analyse if participants agree among themselves in classifying generalized and non-generalized features of a sketch map. A total of 11 sketch maps were created and participants had to mark the features of sketch map in either green if non-generalized or yellow if generalized after comparing it with metric map data. They aslo had to mark features in metric map with orange if its not drawn in sketch map. A total of five participants classified the features of map. We found that there is a high agreement among the participants. The data and script used for arriving at this conclusion  can be found in this repository.

## Data

The AgreementData.xlsx has total of 10 columns. The column C,D,E,F,G is the color given by each participant - P1,P2,P3,P4,P5 for different features. 

## Script

The script calculates the Light's kappa statistic and Krippendarf's alpha for getting agreement score. The agreement score of whole data is 0.88. The script also produces agreement score for each set of sketch map.

