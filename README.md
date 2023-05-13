# Shear-Strain-Estimator
The MATLAB routines to estimate the shear strain profile in soil column models under earthquake excitations.
This file contains MATLAB routines accompanying the manuscript entitled 'Estimation of Soil Shear Strain Profile for Sampling Borehole Information in Site Response Analysis'.
The zip folder contains the following:
1. A script file 'Shear_Strain_Simulator_Main_Program.m' which is the interface for running functions.
2. A script file 'Strian_simulator.m' which is the function of the proposed method to estimate the shear strain profile in soil column models under earthquake excitations.
3. A script file 'SHAKE.m' which is the function to perform equivalent linear site response analysis (SHAKE analysis) to validate the proposed method.
4. Additional function files entitled 'EquivalentLinear.m', 'ResponseSpectra.m', 'TimeStepIntegrationLA.m', and 'TransferFunction.m' to support the above two functions.
5. Variable files 'Bedrock_Motion.mat', 'MaterialCurve.mat', and 'SoilProfile.mat'. The variable files contain site information and a ground motion accelerogram as a test-run of the program, as presented in Figure 1 in the manuscript. 
