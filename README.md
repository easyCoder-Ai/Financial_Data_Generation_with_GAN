
# Paper: Innovative Pattern Extraction and Synthetic High-Frequency Data Generation in European Carbon Emmision Markets Using GAN Networks

# Authors: 

Seyed Ali Hosseini ==> seyedali1.hosseini@polimi.it

Alessandro NIccolai ==> alessandro.niccolai@polimi.it

Francesco Grimaccia ==> francesco.grimaccia@polimi.it


## Abstract ##

This study aims to identify specific price patterns analyzing high-frequency tick-by-tick data of the carbon emission allowances of companies participating in the European emissions trading system market (European Carbon Emission Allowance), resampling it into 5-minute intervals. We identified innovative patterns in the data and extracted key features from them in order to infer anticipatory knowledge in the data evolution. Based on the average frequency of detected patterns each month, we constructed a dataset consisting of sequences of patterns and their corresponding main features. Using a Generative Adversarial Network (GAN) model combined with Long Short-Term Memory (LSTM) and Self-Attention layers, we were able to generate synthetic sequences. These sequences were then used to produce specific artificial interval data. The quality of the generated dataset was evaluated using key financial time-series metrics, including linear unpredictability, heavy-tailed price return distribution, volatility clustering, leverage effects, coarse-fine volatility correlation, and gain-loss asymmetry. The final results demonstrate that our synthetic data successfully emulates the statistical characteristics of a real financial market. The findings of this study can be applied to various areas of financial analysis, such as risk management, algorithmic trading, market simulation, and stress testing under different market conditions.

