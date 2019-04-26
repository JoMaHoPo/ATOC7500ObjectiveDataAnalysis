January 29, 2019; last updated April 26, 2019
Jennifer Kay (Jennifer.E.Kay@colorado.edu)
Readme for github repo https://github.com/jenkayco/ATOC7500ObjectiveDataAnalysis

This github repo contains code used for ATOC7500 Objective Data Analysis in Spring 2019.

Files uploaded include:

#### test file ####
test_jupyternotebook.ipynb - test file

#### instructions for reproducing the python environment ####
culabenv_packagelist_final2019.txt - python package list

Note: to use python package list to recreate the python environment.
1) Install anaconda.
2) Recreate the environment including all python packages needed for the labs below by typing the following:

"conda create --name culabenv_final2019 --file culabenv_packagelist_final2019.txt"
"source activate culabenv_final2019"

earlier versions of the python environment from february and april are also still in this github.
there should be no reason to use them but they are kept here just in case.
culabenv_packagelist_feb152019.txt
culabenv_packagelist_april2019.txt

#### application labs! #####

ATOC7500_applicationlab1_guidance.docx -lab1 on bootstrapping/tz-tests guidance
ATOC7500_applicationlab1_bootstrapping.ipynb - application lab #1 on bootstrapping
snow_enso_data.csv - data needed for ATOC7500_applicationlab1_bootstrapping.ipynb
ATOC7500_applicationlabs1_ztest_ttest.ipynb - application lab #1 on ztest/test
TS_timeseries_cesmle_1850.nc - data needed for ATOC7500_applicationlabs1_ztest_ttest.ipynb 
TS_timeseries_cesmle_1920_2100.nc - data needed for ATOC7500_applicationlabs1_ztest_ttest.ipynb

ATOC7500_applicationlab2_guidance.docx - lab2 on regression/red noise/AR1 guidance
ATOC7500_applicationlab2_AR1_Nstar.ipynb - application lab on red noise, autocorrelation, and independent samples
christman_2016.csv - data needed for ATOC7500_applicationlab2_AR1_Nstar.ipynb
ATOC7500_applicationlab2_AR1_regression_AO.ipynb - application lab on red noise and regression using the Arctic Oscillation
monthly.ao.index.b50.current.ascii - data needed for ATOC7500_applicationlab2_AR1_regression_AO.ipynb

ATOC7500_applicationlab3_guidance.docx - lab3 on EOF/PCA analysis guidance
ATOC7500_applicationlab3_eof_analysis_cosineweighting_cartopy.ipynb - application lab on EOF/PCA of Sea Surface Temperatures
ATOC7500_applicationlab3_eigenfaces.ipynb - application lab on EOF/PCA of faces
att_faces.npy - data needed for ATOC7500_applicationlab3_eigenfaces.ipynb
culabenv_packagelist_feb152019.txt - python environment, see lab3 guidance for installing on Mac with Anaconda
***Note: The data needed for ATOC7500_applicationlab3_eof_analysis_cosineweighting_cartopy.ipynb are too big to upload to github***
***Please download yourself from http://www.metoffice.gov.uk/hadobs/hadisst/data/download.html

ATOC7500_applicationlab4_guidance - lab4 on spectral analysis guidance
ATOC7500_applicationlab4_fft_EPICA.ipynb - application lab on ice core spectral analysis
edc3deuttemp2007_nohead.txt - ice core data
ATOC7500_applicationlab4_fft_christman.ipynb - application lab on Fort Collins weather spectral analysis
Christman_data_nomissing.csv - Fort Collins weather data

ATOC7500_applicationlab5.docx - lab5 on filtering guidance
ATOC7500_applicationlab5_synthetic_data_with_filters.ipynb - application lab on filtering with recursive and non-recursive filters using synthetic dataset
ATOC7500_applicationlab5_ENSO_mrbutterworth.ipynb - application lab on butterworth filter using nino3.4 ENSO index data from CESM Large Ensemble
CESM_nino34.p - pickled data needed for ATOC7500_applicationlab5_ENSO_mrbutterworth.ipynb, beware issues with xarray updates (hopefully solved)

ATOC7500_applicationlab6_da_with_kalman_filter_static.ipynb - lab6 on data assimilation (author Luke Madaus)
GEFS_forecast.p - Global Ensemble Forecast System forecast for April 26, 2019 -- data needed for lab6
Note: Luke's version of this lab is available on github here: https://github.com/lmadaus/da_demo
