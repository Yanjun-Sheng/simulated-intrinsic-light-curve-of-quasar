# simulated-intrinsic-light-curve-of-quasar

I tried to imitate the method from a paper to simulate the intrinsic light curve of a quasar. In this work, It models quasar light curves as a continuous time ﬁrst order autoregressive process (CAR(1)). This model, first developed in economics, assumes that each point on the quasar's intrinsic time series (flux versus time) follows the normal distribution.
The expected value and the variance of the normal distribution for each point have certain correlation with former points (flux or time interval).
Since this is an intrinsic light curve, it doesn't have any effect caused by gravitational lensing or etc.
