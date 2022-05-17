# EC-Benchmark-2-CSE370
This repository contains work done on the EC benchmark 2 announced at OMAE 2021. Specifically, this work concerns exercise 1, which is concerned with predicting exceedance probabilities and return values of extreme ocean waves from a provided 25 year data set. The included code is a modification of the MATLAB code provided in the original benchmark, and compares the results of different modeling approaches and extreme value distributions. The files provided in this repository are created by Jennings Ye with the help of [Taemin Heo](http://taeminheo.com) and [Dr. Lance Manuel](https://lancemanuel.netlify.app/) at The University of Texas at Austin.

## Modeling Approches
The original provided code from OMAE 2021 uses a annual maxima modeling approach with a gumbel distribution. In this work, a Peaks-over-Threshold approach is investigated instead. The differences between the two modeling approaches with the same distribution is shown below. 
