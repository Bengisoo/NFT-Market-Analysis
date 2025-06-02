# NFT Market Analysis (2019--2021)
This repository contains the project
proposal, progress report, final report, codebase, and visual outputs of
our project titled "Analysis of Trends in the NFT Market: Valuable NFTs,
Price Factors, and Wash Trading".

The study explores the evolution of the NFT ecosystem between 2019 and
2021, based on more than 5.25 million transaction records obtained from
the OpenSea platform. Using a multi-dimensional analytical framework, we
investigated:

- Temporal trends and seasonal cycles in NFT sales, -Statistical
relationships between NFT attributes and their prices
- Clustering of high-value NFTs and their common categorical traits, -Detection of
suspicious trading behaviors (e.g., wash trading)
- Volatility patterns and market dynamics

Our methodology integrates time series analysis, correlation and
regression modeling, unsupervised learning (K-Means), frequent pattern
mining (FP-Growth), and a custom-designed anomaly detection framework.
The findings provide insights into how NFT value is shaped, how the
market evolved, and how potential manipulation may occur.

## Project Members 
This project was completed as part of a university data
science assignment by the following team members:

- Aslı Ayaz -- Identifying Factors Affecting NFT Prices & Analyzing Seasonal and Periodic Changes 
- Zehra Bengisu Doğan -- Time Series Analysis & Wash Trading Detection 
- Zeynep Çalapkulu -- Clustering, High-Value NFT Mining & Examining NFT Price Volatility  



  
## 🔧 How to Run the Project
This project contains Python notebooks and datasets for analyzing the NFT market. Follow the steps below to set up and run the project on your machine.

### 1. Clone the Repository
First, clone the GitHub repository to your local machine:  
`git clone https://github.com/your-username/NFT-Market-Analysis.git`  
  
Then, navigate to the project directory:  
```cd NFT-Market-Analysis/ProgramCodes```  


### 2. Obtain the Datasets
You can obtain the required datasets in two ways:

- ✅ Option 1: Download from Kaggle
* Download the raw dataset from the following link:

  * [ OpenSea NFT Sales 2019 - 2021 Dataset Link ](https://www.kaggle.com/datasets/bryanw26/opensea-nft-sales-2019-2021/code)

  * Move the downloaded file into the ProgramCodes directory.

If necessary, rename the file to opensea_nft_sales (e.g., opensea_nft_sales.csv ) so that it matches the file name used in the Cleaning.ipynb notebook.

- ✅ Option 2: Download from DatasetLinks Folder
  * Inside the DatasetLinks folder, you’ll find [link for both raw and cleaned versions of the dataset:](https://drive.google.com/drive/folders/1aaVmxuCPDZZ4mNW7aZaPJjaUnjNz-Cbj?usp=sharing) 

  * opensea_nft_sales → Raw dataset

  * cleaned_dataset → Cleaned dataset (used in most notebooks)

  * Copy the necessary dataset(s) to the ProgramCodes folder before running the notebooks.


### 3. Data Cleaning (If Using the Raw Dataset)
If you downloaded the raw dataset from Kaggle:

Open and run the Cleaning.ipynb notebook to clean the data.

This will generate a cleaned file named cleaned_dataset which is used in the rest of the notebooks.


### 4. Running the Notebooks
All necessary Jupyter notebooks are located in the ProgramCodes folder. You can run them in any order, but keep in mind the following:

* By default, all notebooks are configured to use the cleaned_dataset.

* Only the following two notebooks use a different dataset: cleaned_dataset3.xls:

  * 5.AnalyzingPeriodicChanges.ipynb

  * 8.FactorsAffectingPrice.ipynb

⚠️ If you rename or use different datasets, make sure to update the corresponding file names inside the notebooks.  
  


