# Black Friday Dataset Feature Engineering and EDA

This repository contains the code for performing feature engineering and exploratory data analysis (EDA) on the Black Friday dataset. The dataset is sourced from Kaggle and can be found at [this link](https://www.kaggle.com/sdolezel/black-friday). The main focus of this project is to gain a basic understanding of the dataset, perform feature engineering, and conduct EDA to uncover insights.

## Dataset

The Black Friday dataset provides customer purchase details from a retail company during a Black Friday sale. It includes the following features:

- `User_ID`: Unique identifier for each customer
- `Product_ID`: Unique identifier for each product
- `Gender`: Gender of the customer (Male or Female)
- `Age`: Age group of the customer
- `Occupation`: Occupation code of the customer
- `City_Category`: Category of the city where the customer resides (A, B, or C)
- `Stay_In_Current_City_Years`: Number of years the customer has stayed in the current city
- `Marital_Status`: Marital status of the customer (0 - Unmarried, 1 - Married)
- `Product_Category_1`, `Product_Category_2`, `Product_Category_3`: Product category codes for the purchased products
- `Purchase`: Purchase amount in dollars

## Feature Engineering and EDA

The notebook `Untitled.ipynb` in this repository focuses on feature engineering and exploratory data analysis. The steps performed include:

1. Data Exploration:
   - Checking for missing values
   - Analyzing the distribution of variables
   - Understanding the relationships between variables

2. Feature Engineering:
   - Handling missing values
   - Encoding categorical variables
   - Scaling numerical variables
   - Creating new features based on domain knowledge

3. EDA (Exploratory Data Analysis):
   - Analyzing the distribution of purchase amounts
   - Investigating the relationship between purchase amounts and other variables
   - Extracting insights and patterns from the data

Please note that while the notebook covers feature engineering and EDA in detail, the selection of a specific modeling technique is not the focus of this project. The notebook serves as a foundation for further analysis and modeling.

## Dependencies

The following libraries are required to run the code in this repository:

- Pandas
- NumPy
- Matplotlib
- Seaborn

Install the dependencies using the following command:
 - pip install pandas numpy matplotlib seaborn


## Usage

To use this code, follow these steps:

1. Clone the repository: git clone https://github.com/joelsiby02/Black-Friday-Dataset-Feature-Engineering.git

2. Navigate to the project directory: cd Black-Friday-Dataset-Feature-Engineering

3. Run the Jupyter notebook `Untitled.ipynb` to perform feature engineering and exploratory data analysis on the dataset.

## License

This project is licensed under the [MIT License](LICENSE).

