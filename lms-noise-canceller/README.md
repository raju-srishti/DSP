# DSP
# LMS Noise canceller
Full LMS adaptive noise canceller with dual-mic setup (primary + reference), learning curve plot, and a step-size sensitivity sweep across 5 values of µ. That last plot shows you understand the convergence-vs-misadjustment tradeoff.
It guesses the noise, subtract it, check the error, get slightly better, repeat 8000 times
# Key DSP concepts
FFT · Adaptive filter · Passband filter
# How to run
Open in MATLAB and press Run. Requires Signal Processing Toolbox
