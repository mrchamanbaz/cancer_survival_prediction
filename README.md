# Cancer Survival Prediction


## Description of the Project:
we use Surveillance, Epidemiology, and End Results [(SEER) Incidence Data](https://seer.cancer.gov/data-software/documentation/seerstat/nov2019/) to predict the chance of survival given cancer diagnosis information obtained when the patient is diagnosed with cancer. We find answers to two questions:

**Question 1: Given the demographic and diagnosis information, can we predict if the patient will pass away due to complications caused by the diagnosed cancer?**

**Question 2: For patients who eventually pass away due to cancer, can we predict the number of months they expect to survive?**


## Project Structure 
The project is formulated in the Jupyter notebook `Cancer_survival_prediction.ipynb`. It has different sections to load, clean, and process data. The jupyter notebook is self-contained and includes detailed information about the project. 

## Data:

The data in this project comes from [Incidence - SEER Research Data, 18 Registries, Nov 2020 Sub (2000–2018)](https://seer.cancer.gov/data-software/documentation/seerstat/nov2019/). It is a public dataset that collects cancer incidence data from several registries across the U.S. The data (`.csv` files) are not included in the repository because one needs to request access to the data. If you need to access the dataset, you must submit a request. Also, the `.csv` files are very large (over 6GB).

 
## Required packages:

This project requires Python 3.x and the following Python libraries:

* Machine Learning Libraries: NumPy, Pandas, Sciki-Learn, tensorflow, xgboost


## Licensing, Authors, and Acknowledgements

Please feel free to use the code here as you would like. 
