# Pecan Impactor Geometry Study

Here is the data analyzed and reported on in the article: "The Effect of Impactor Geometry on End-to-End Pecan Cracking"
Authors: Mark W. Jackson, Cody M. Langston, Leah E. Madsen, & R. Benjamin Davis
Published: AgriEngineering, 2024

A short description of each file in the total dataset:

pecanDropHeights.xlsx -> Energy levels randomly generated and used to compute drop heights for each impactor. Each set of drop heights/energy levels used for all impactors for consistency. The first page is the energy level (J) of each drop height. The second page is the drop heights (mm) used for the primary mass in the study.

imagingData.mat -> Crack lengths reported as percentages of the pecan circumference. Measurements only provided for pecans that are analyzed with the Detection, Measurement, & Classification (DCM) software. Any pecans not measured are reported as uncracked, overcracked, or ideally cracked. One variable used for each respective impactor geometry tested.

crackingData.mat -> Results from classification of pecan cracks. Results reported as total number of pecans present in each of the four crack categories: undercrack, crack, ideal crack, over crack. Each impactor total is separated into variables indicating which impactor geometry is tested. Impactor 1 corresponds with the 30 degree impactor, impactor 2 corresponds with the 37.5 degree impactor, impactor 3 corresponds with the 45 degree impactor, and impactor 4 corresponds with the 52.5 degree impactor. Each file appended with "raw" indicates that the values are the total number of pecans reported in each bin for each impactor. Else, the pecans present in each bin are indicated by percentages. Results from the comparison of the different masses used are also provided in the variables, "totalMass." A vector is also provided that indicates the average energy level of each energy bin tested. The drop heigts that are used are in the first file mentioned.
