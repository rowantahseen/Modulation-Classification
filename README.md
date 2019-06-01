# Modulation-Classification
DeepSig Dataset: RadioML 2016.04C
Modulation Classification on a synthetic dataset, generated with GNU Radio, consisting of 10 modulations. This is a variable-SNR dataset with moderate LO drift, light fading, and numerous different labeled SNR increments for use in measuring performance across different signal and noise power scenarios.

The 10 modulation Signals are : 8PSK, AM-DSC, BPSK, CPFSK, GFSK, PAM4, QAM16, QAM64, QPSK, WBFM

Every sample is presented using two vectors each of them has 128 elements. 

Features used:
1. Raw time series as given
2. First derivative in time
3. Integral in time 
4. Combinations of 1, 2 and 3.

Two Model Architecture:
- Fully Connected Neural Network
- Convolutional Neural Network implmeneted from this paper : https://arxiv.org/pdf/1602.04105.pdf

