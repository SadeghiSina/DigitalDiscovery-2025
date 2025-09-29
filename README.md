# Lead_Free, SDFL(2025):
## Here is the the Closed-Loop Optimization Code built upon BoTorch; the real-time data processing was provided within the second cell.
## The developed Bayesian optimization framework was utilized in the the following papers:
### paper 1 (published in Digital Discovery):
#### https://pubs.rsc.org/en/content/articlehtml/2025/dd/d5dd00062a
### paper 2 (submitted to Analytical Chemistry):
#### https://chemrxiv.org/engage/chemrxiv/article-details/68d1c862f2aff16770062786
## While running the code, it asks for the directory path containing the .csv files; raw absorption and PL spectra as well as the light reference, wavelengths and dark references associated with the absorption and PL spectroscopy, and FR.
## User needs to copy and paste the directory path in the box provided by the code and press enter.
## FR is the file that includes experimental conditions; each row represents one condition as follows:
### column 1: reaction temperature
### column 2: CuI volumetric flowrate
### column 3: ZnI2 volumetric flowrate
### column 4: CsOA volumetric flowrate
### column 5: ODE volumetric flowrate
### column 6: PFO volumetric flowrate
### column 7: number of residence times to wait to initiate the in-situ characterization 
### column 8: always zero meaning no washing is required
