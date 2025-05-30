## NGC analysis of the interaction between pitchers and batters in baseball
Tis repository contains code and datasets for a NGC analysis of the interaction between pitchers and batters in baseball[1]. 

The method was originally proposed by Tank et al[2], and this repository was also developed based on the original repository (https://github.com/iancovert/Neural-GC). 

## Installation
To install the code, please clone the repository. All you need is `Python 3`, `PyTorch (>= 0.4.0)`, `numpy` and `scipy`.

## Contents
- input_datasets: pre-processed motion capture data of baseball pitcher and batter. The uploaded datasets contains motion capture data of 16 pairs of baseball pitcher and batter. The collecte motion capture data was transformed to the resultant velocity, and total of 27 joints data were included (13 pitcher's and 14 batter's joints). See original article[1] for more detailed information

- models: machine learning model for NGC analysis imported from the original repository.

- NGC_analysis.ipynb: sample code for the NGC analysis with input_datasets. You can run this code in Google Colaboratory or other applications.

## How to run
Add the file path for "models" and "input_datasets" floders in the NGC_analysis notebook. Then you can run and check how it works. 
For setting the hyper parameters, please also see the supporting information file.

## Corresponding author
- Ryota Takamido (<takamido@race.t.u-tokyo.ac.jp>)

## Reference
[1] Ryota Takamido, Chiharu Suzuki, Jun Ota, Hiroki Nakamoto, "Understanding whole-body inter-personal dynamics between two players using neural granger causality as the explainable AI (XAI)", Human Movement Science, vol.101, 2025

  [2] Alex Tank, Ian Covert, Nicholas Foti, Ali Shojaie, Emily Fox. "Neural Granger Causality." *Transactions on Pattern Analysis and Machine Intelligence*, 2021.
