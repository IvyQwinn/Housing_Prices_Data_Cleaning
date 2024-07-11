# Housing Prices Data Cleaning and Preprocessing

## Overview
This project involves performing data cleaning and preprocessing on a housing prices dataset to prepare it for further analysis or modeling. The dataset used for this analysis includes various features related to housing properties and their sale prices.

## Dataset
The dataset used in this project is the Housing Prices dataset, which can be downloaded from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

### Features
- **Id**: Property ID
- **MSSubClass**: The building class
- **MSZoning**: The general zoning classification
- **LotFrontage**: Linear feet of street connected to the property
- **LotArea**: Lot size in square feet
- **Street**: Type of road access
- **Alley**: Type of alley access
- **LotShape**: General shape of property
- **LandContour**: Flatness of the property
- **Utilities**: Type of utilities available
- ... (and many more features)

## Project Structure
The repository contains the following files and directories:
- `data/`: Directory containing the dataset
  - `train.csv`: The dataset file
- `Housing_Prices_Data_Cleaning.ipynb`: Jupyter Notebook with the complete data cleaning and preprocessing process
- `README.md`: This file

## Steps and Analysis

### 1. Data Loading and Exploration
- Load the dataset and display the first few rows
- Summarize the dataset to understand the basic statistics
- Check for missing values in the dataset

### 2. Handling Missing Values
- Fill missing numerical values with the median
- Fill missing categorical values with the mode

### 3. Handling Outliers
- Plot boxplots to detect outliers in the SalePrice
- Remove outliers based on the IQR method

### 4. Feature Engineering
- Create new features from existing data (e.g., TotalSF)
- Convert categorical variables into dummy/indicator variables

### 5. Scaling and Normalization
- Standardize the dataset using `StandardScaler`

## How to Run the Notebook
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/Housing_Prices_Data_Cleaning.git
    cd Housing_Prices_Data_Cleaning
    ```

2. **Install Required Libraries**:
    Ensure you have the required Python libraries installed. You can install them using pip:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3. **Open the Jupyter Notebook**:
    Start Jupyter Notebook and open `Housing_Prices_Data_Cleaning.ipynb` to run the analysis step-by-step.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue to discuss.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- The dataset used in this project is available on [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## Author
- Ivy Qwinn
