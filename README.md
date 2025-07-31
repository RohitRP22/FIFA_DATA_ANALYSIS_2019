# FIFA Data Analysis 2019

This project analyzes factors shaping football player performance using the FIFA 2019 dataset and builds a predictive machine learning model for a player's overall rating.

## Dataset

- **FIFA-2019.csv**: Contains player attributes and statistics from FIFA 2019.

## Workflow

1. **Data Cleaning**:  
   - Removes unnecessary columns  
   - Cleans currency, date, height, and weight formats  
   - Handles missing values

2. **Exploratory Data Analysis (EDA)**:  
   - Visualizes relationships between player attributes and overall rating  
   - Uses seaborn and matplotlib for plotting

3. **Feature Engineering**:  
   - Converts categorical and string features to numerical values  
   - Fills missing values appropriately

4. **Modeling**:  
   - Builds regression models to predict player ratings  
   - Evaluates model performance using R², RMSE, and adjusted R²  
   - Uses feature importance analysis with ELI5

## Usage

Open and run the notebook [`FIFA_DATA_ANALYSIS_2019.ipynb`](FIFA_DATA_ANALYSIS_2019.ipynb) in Jupyter or VS Code.  
Ensure you have the required libraries installed:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels eli5
```

## Results

- Identifies key factors influencing player ratings
- Provides visualizations and model evaluation metrics

## License

This project is for