# Lactation PBPK
A generic PBPK workflow for full bottom-up prediction of human milk concentrations in a three-months postpartum population for physiochemically diverse medicines
## Background
Lactation PBPK models were built for 10 physiochemically diverse medicines. The selected medicines were amoxicillin, caffeine, cetirizine, levetiracetam, metformin, nevirapine, sertraline, valproic acid, tenofovir, and zidovudine. The lactation PBPK models resulted in reasonable predictions of maternal plasma and human milk concentration-time profiles for eight medicines, while overprediction of the concentration-time profiles in human milk was observed for nevirapine and tenofovir. From a safety perspective, it is important that none of the models resulted in an underprediction of the milk levels for the given maternal dosing regimen. Details about the ten lactation PBPK models were published previously [1]. The workflow for the PBPK model development and evaluation can be used to simulate the human milk concentration, and to calculate predicted infant doses for virtually any medicine. 
## Repository Files
This repository contains the PK-Sim® lactation PBPK models for amoxicillin, caffeine, cetirizine, levetiracetam, metformin, nevirapine, sertraline, valproic acid, tenofovir, and zidovudine.
Instructions: The PBPK model files have been compressed, and for Sertraline and Valproic Acid, the PBPK model has been divided into multiple files. To access these files, please navigate to the relevant medication on the GitHub platform, select "download raw file", and then proceed to extract the file using appropriate software such as WinZIP or WinRAR. For multipart models, it is necessary to download all parts and store them in the same directory. Subsequently, by selecting "Extract here" on Part 1, all parts will be automatically imported and merged into the final PK-Sim file. 
This repository also contains the MoBi® building blocks (spatial structure and passive transports) that are needed to apply this workflow to build a lactation PBPK model for other medicines. A step-by-step manual on how to apply this workflow is also available in the repository.
## Instructions
A step-by-step tutorial is available inside the “MoBi building block” file.
## Version Information
PK-Sim® Version 9.1 
MoBi® Version 9.1
## License
The model is distributed under the GPLv2 License.
## References
[1] Nauwelaerts, N.; Macente, J.; Deferm, N.; Bonan, R.H.; Huang, M.-C.; Van Neste, M.; Bibi, D.; Badee, J.; Martins, F.S.; Smits, A.; et al. Generic Workflow to Predict Medicine Concentrations in Human Milk Using Physiologically-Based Pharmacokinetic (PBPK) Modelling—A Contribution from the ConcePTION Project. Pharmaceutics 2023, 15, 1469. https://doi.org/10.3390/pharmaceutics15051469 
