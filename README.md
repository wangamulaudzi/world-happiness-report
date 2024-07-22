# World Happiness Report Analysis

This project analyzes the [World Happiness Report dataset](https://kaggle.com/datasets/unsdsn/world-happiness) to uncover insights into global happiness trends and factors contributing to global well-being

## Interactive Visualizations

Due to GitHub's limited support for interactive plots, the dropdown visualizations may not display correctly in this repository. To view the interactive elements:

1. Clone this repository and run the notebook locally
2. View the notebook `world-happiness-report-analysis.ipynb` notebook
3. Check out the static versions of key visualizations in the 'images' folder

## Key Features

- Data visualization of happiness scores and contributing factors
- Correlation analysis between happiness and economic/social indicators
- Analysis of happiness trends over time
- K-means clustering to group countries based on happiness factors
- Predictive modeling using Random Forest Regressor

## Technologies Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for machine learning (K-means clustering, Random Forest)
- Jupyter Notebooks for interactive analysis

## Key Insights

- Identified strongest correlations between happiness and economic/social factors
- Discovered worldwide patterns in happiness scores
- Clustered countries into 6 groups based on happiness factors, revealing patterns based on geolocation
- Built a predictive model for happiness scores with feature importance analysis

## Runnning locally

- Clone repo and `cd` into that directory
- Create a virtual environment: `pyenv virtualenv 3.10.6 <environment-name>`
- Set the local environment: `pyenv local <environment-name>`
- Install necessary packages `pip install -r requirements.txt`
- Open the Jupyter Notebook using your preferred method and select your `<environment-name>` as the kernel.
