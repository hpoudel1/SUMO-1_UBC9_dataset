# SUMO-1_UBC9_dataset
C(t) data of residue water hydrogen bonds for SUMO-1 and UBC9

The residue number, i.e., res#.dat, in each subfolder corresponds to the residue number listed in Table S1 (SUMO-1) and Table S2 (UBC9).

All computed C(t) curves for differing lengths of simulation time to evaluate the convergence of the exponential fits, including the full length C(t), are found in the residue_Ct_analysis folder. Within this folder you will find a jupyter notebook on 'Computing C(t) confidence.ipynb', within this is an analysis of C(t) for varying length of simulation time with the respective 95% coffidence interval as assessed from a t-distribution. Additionally, the 99% confidence interval is shown for the RSA vs. $\tau$ plots for SUMO-1 and UBC9 of the main text.  


Importantly, C(t) is listed at each time step, where the interval between time steps is 250 fs (0.25 ps). The first entry in each data file is C(0), the second is C(250 fs), the third is C(500 fs), etc.


Authors: Korey M. Reid, Humanath Poudel, and David M. Leitner

Institution: University of Nevada, Reno
