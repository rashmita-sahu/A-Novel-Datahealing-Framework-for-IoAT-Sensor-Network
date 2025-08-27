
Agricultural Data Healing using MAP-based Recovery
This repository contains the R scripts used to reproduce the results in Table 3 of our paper.
The code implements MAP-based missing value recovery on the Soil Moisture dataset.
________________________________________
Repository Structure
•	Novel_Datahealing_Framework.r → Main R script containing the algorithm.
•	data/Soil_Moisture_DS.csv → dataset.
•	README.md → Instructions for running the code.
________________________________________
 Requirements
Before running the script, install the required R packages:
install.packages("Matrix")
install.packages("GLDEX")
install.packages("bayestestR")
install.packages("writexl")
install.packages("FuzzyR")
________________________________________
How to Run
1.	Clone or download this repository.
2.	Open Novel_Datahealing_Framework.r in RStudio or run in R console.
3.	Update the dataset path in the script if needed:
4.	x <- read.csv("data/Soil_Moisture_DS.csv")
5.	Run the script.
6.	The output metrics (MSE, MAE, RMSE, MAPE, Accuracy) and recovered datasets will be generated in the results output window.
________________________________________
Output
Performance metrics (MSE, MAE, RMSE, MAPE, Accuracy).
________________________________________
 Link
The repository is available at:
https://github.com/rashmita-sahu/A-Novel-Datahealing-Framework-for-IoAT-Sensor-Network/upload/main
________________________________________
 