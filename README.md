# Hydrogen-clinopyroxene-equilibration
This supplementary material contains all MATLAB© programs that have been written to model non-isothermal diffusion of hydrogen in clinopyroxene along geotherms (P-T-fO2 path). 

Note: This is a sequence of codes that should be used in the order shown below. The first code produces an .xlsx (EXCEL file) output file that is then read from the next code and so on. The last code in this sequence is the non-isothermal diffusion model that uses all the information contained in the single .xlsx file to calculate the diffusion process. 

•	Geotherm.m: This code was used to calculate P-T paths.\
•	COH_geotherm.m: This code was used to calculate fluid composition along the model P-T paths using following .mat files that contain fugacity coefficients:\
o	fugacity_coefficient_CH4.mat\
o	fugacity_coefficient_CO.mat\
o	fugacity_coefficient_CO2.mat\
o	fugacity_coefficient_H2.mat\
o	fugacity_coefficient_H2O.mat\
o	fugacity_coefficient_P_kbar.mat\
o	fugacity_coefficient_T_C.mat\
o	yCH4_extrapolated.mat\
o	yCO_extrapolated.mat\
o	yCO2_extrapolated.mat\
o	yH2_extrapolated.mat\
o	yH2O_extrapolated.mat\
o	interp2D.m\
•	H2Ocpx_sol.m: This code calculates the solubility concentration along the P-T path as a function of water fugacity, temperature, and pressure.\
•	non_isothermal_diffusion.m: This code is the actual non-isothermal model that reads the input data from the .xlsx file\
•	reeq_coolingrate.m: This code can be used to calculate figure 7 in this paper.\
