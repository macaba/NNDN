# NNDN
Investigating neural networks for denoising time series data

## Incentive

Cutting edge consumer MEMS accelerometers (ADXL355) have a noise density of around 25 μg/√Hz. By a combination of parallelising devices and applying neural network techniques, the objective is to reduce this to 5 μg/√Hz, thus allowing it to be used in metrology applications. Using NN will reduce the number of parallel devices required, from 25 devices (25 μg/√25) to some, currently unknown, smaller number, allowing for a smaller PCB and lower BOM cost.

Noise from a MEMS device tends to be white gaussian noise in the higher frequency region, so it is reasonable to conclude that a NN trained for this kind of noise would be suitable for use in a vast number of other applications.

## Literature

[1] https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6210601/pdf/sensors-18-03470.pdf [LSTM-RNN]

[2] https://arxiv.org/abs/1808.03867 [Pervasive Attention]

[3] https://arxiv.org/pdf/1810.11614.pdf [Deep Learning]

[4] https://towardsdatascience.com/the-fall-of-rnn-lstm-2d1594c74ce0 [Article]
