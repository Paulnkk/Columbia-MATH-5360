# Levy-PDF-and-parameter-estimation-of-futures
I generated probability density functions of price fluctuations from Futures (ES and FT) and associated alpha-parameters for stable non-gaussian distributions. The data contains prices (CLOH) per minute for several years.

The calculations for the estimation of the stability parameters were determined empirically by simulating probabilities for unchanged price fluctuations at a certain time-shift tau (delta_p = 0). The resulting regression and therefore the one dimensional coefficient beta is used to infer the Levy exponent alpha (1 / beta).
