# Log-Normal-Bias-Corr

The LogNormBias.Rmd file contains code to run simulations and parameter estimation of the Ricker stock-recruitement curve to explore the impacts of the log-normal bias correction. 

In the file "Functions.R", the function Sim_Ricker_SR_Data() simulates data from known Ricker parameters, and the function RunRicker() is a wrapper for the TMB file, Single_Stock_Ricker.cpp, that estimates parameters from data.

TMB is required to run the estimation. See https://github.com/kaskr/adcomp/wiki