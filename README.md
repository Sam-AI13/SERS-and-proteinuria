# SERS and Proteinuria
The goal of this project is to classify patients with high protein concentration in urine and the healthy group based on SERS (Surface Enchanced Raman Spectroscopy) spectral data and biomedical data, like chemical urine analysis.

Research output:

- S. Aitekenov et al., “SERS for Detection of Proteinuria: A Comparison of Gold, Silver, Al Tape, and Silicon Substrates for Identification of Elevated Protein Concentration in Urine”, Sensors, vol. 23, no. 3, Art. no. 3, Jan. 2023, doi: 10.3390/s23031605
- S. Aitekenov et al., “Surface-enhanced Raman spectroscopy (SERS) for protein determination in human urine”, Sensing and Bio-Sensing Research, vol. 38, p. 100535, Dec. 2022, doi: 10.1016/j.sbsr.2022.100535
- S. Aitekenov et al. “Raman, Infrared and Brillouin Spectroscopies of Biofluids for Medical Diagnostics and for Detection of Biomarkers”, Critical Reviews in Analytical Chemistry, Feb. 2022, doi: 10.1080/10408347.2022.2036941
- S. Aitekenov, A. Gaipov, and R. Bukasov, “Review: Detection and quantification of proteins in human urine”, Talanta, p. 121718, Oct. 2020, doi: 10.1016/j.talanta.2020.121718
- (Reviewer) H. Jin et al. ‘Raman Spectroscopy of Emulsions and Emulsion Chemistry’, Critical Reviews in Analytical Chemistry, vol. 0, no. 0, pp. 1–13, Jul. 2023, doi: 10.1080/10408347.2023.2228411 

The project is divided into several Jupyter notebooks with the following names:
- Import raw urine spectra (part 1) - imports spectra from thousands of txt files and organizes them
- Spectra processing (part 2) - spectra processing tasks, such fluorescence backround removal, noise removal etc.
- Classification of patients (part 3) - machine learning algorithms to classify patients
- Biomedical data (part 4) - analyzes urine samples from their chemical composition
- Comparison of nanoparticles (part 5) - compares performance of different nanoparticles 

Author of all codes: Sultan Aitekenov, sultanaitekenov@gmail.com

The scope of this work is better understood from the abstract of paper [2]: Excessive protein excretion in human urine is an early and sensitive marker of diabetic nephropathy, primary and secondary renal disease. Kidney problems, particularly chronic kidney disease, remain among the few growing causes of mortality in the world. Therefore, it is important to develop efficient, expressive, and low-cost method for protein determination. Surface-enhanced Raman spectroscopy (SERS) methods are potential candidates to achieve those criteria. In this paper, the SERS method was developed to distinguish patients with proteinuria and the healthy group. Two types of commercial gold nanoparticles with a diameter of 60 nm and 100 nm were employed to prepare substrates for the analysis of 78 samples of unique patients. Data analysis by the PCA-LDA algorithm, and the ROC curves, gave results for diagnostic figures of merits. Sensitivity, specificity, accuracy, and AUC were 0.79, 0.89, 0.85, and 0.90 for the set with 60 nm Au NPs, respectively. Sensitivity, specificity, accuracy, and AUC were 0.79, 0.98, 0.90, and 0.91 for the set with 100 nm Au NPs, respectively. The results show the potential of SERS spectroscopy in differentiating between patients with proteinuria and healthy individuals for clinical diagnostics.
