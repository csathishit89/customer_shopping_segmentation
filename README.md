# Customer Shopping Segmentation 🎯👥

An unsupervised machine learning project utilizing clustering algorithms to segment customers into distinct categories based on their shopping behavior and transaction history.

## 📁 Repository Structure

```
customer_shopping_segmentation/
│
├── Customer_Shopping_segmentation.ipynb  # Main Jupyter Notebook for clustering & EDA
├── Customer_Segmentation_Results.xlsx    # Output dataset with clustered customer segments
├── Data_Science.xlsx                     # Raw dataset containing customer transaction records
└── README.md                             # Project documentation
```

## 📌 Project Overview

This repository focuses on applying clustering techniques (such as K-Means, Hierarchical Clustering, or DBSCAN) to group customers based on purchasing behavior, frequency, and monetary value. This helps businesses tailor targeted marketing strategies and improve customer relationship management.

### Key Objectives:
* **Exploratory Data Analysis (EDA)**: Analyzing customer features, spending distributions, and purchasing patterns.
* **Feature Engineering & Scaling**: Normalizing data and preparing feature sets for unsupervised learning.
* **Clustering & Modeling**: Applying clustering algorithms to discover natural groupings within the customer base.
* **Results Export**: Saving segmented customer data into an Excel spreadsheet for business reporting (`Customer_Segmentation_Results.xlsx`).

## 🛠️ Requirements & Tech Stack

Ensure you have the following libraries installed:

* **Language**: Python 3.8+
* **Data Manipulation**: `pandas`, `numpy`, `openpyxl`
* **Machine Learning**: `scikit-learn`
* **Visualization**: `matplotlib`, `seaborn`

To install the dependencies, run:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
```

## 🚀 How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/csathishit89/customer_shopping_segmentation.git
   cd customer_shopping_segmentation
   ```

2. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook Customer_Shopping_segmentation.ipynb
   ```

3. **Execute the Pipeline**:
   Run the notebook cells sequentially to load `Data_Science.xlsx`, perform feature scaling, run the clustering algorithm, and output the results to `Customer_Segmentation_Results.xlsx`.

## 👤 Author

* **Sathish Chandrasekar**
  * GitHub: [@csathishit89](https://github.com/csathishit89)