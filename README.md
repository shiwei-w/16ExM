# 20ExM

Nanocolumn code is from ExR Zenodo (https://doi.org/10.5281/zenodo.6383293) and on (GitHub at https://github.com/schroeme/ExR)

Distortion code is from ExCel (https://doi.org/10.7554/eLife.46249) 

## Environment

The code requires MATLAB (version R2020a). The code was ran on MacOS 12.6.3 Processor Intel(R) Core(TM) i7 CPU @ 2.6GHz

## Installation Guide

MATLAB was installed through official MATLAB website (usually takes ~1 hour). 

## Package Versions

MATLAB Toolboxes required are:

Parallel Computing Toolbox (version 7.2)
Image Processing Toolbox (version 11.1)
Curve Fitting Toolbox (version 3.5.11)

## Instructions

Distortion code is in Distortion folder. NonRigidReg_MasterScript_ver202008.m is the master file. JY_MeasData_Compiling_ver202107.m is used to compile analysis results from the master file script. 
Instructions are embedded within the code. Code is expected to output a figure showing non-rigidly registered images and a deformation field as well as a plot showing root mean square error as a function of measured distance, used for Figure 2h. Code could take several hours depending on computer system. 

Code for autocorrelation and protein enrichment analysis for synaptic nanocolumn is in Nanocolumn folder. Expansion_analysis_Annotated_final.m is the master file. Demo data is stored in raw_data folder. 
Instructions are embedded within the code. Code is expected to output csv files used for Figure 3c-f. Code usually takes several minutes to run. 

Code for microtubule peak-to-peak analysis is in Peak-to-Peak folder. P2P-gaussian.m is the master file. Demo data is P2P-2-b-norm.csv. 
Instructions are embedded within the code. Code is expected to output a plot used for Figure 2f. Code usually takes several minutes to run. 
