# Movies Exploration Project




## Authors

- Github: [@camelliale1912](https://www.github.com/camelliale1912)
- Linkedin: www.linkedin.com/in/tra-le-nguyen-huong




## Summary of Project
In this project, I will analyze the correlation between movie budgets and gross income. By importing a dataset from Kaggle into Jupyter Notebook, I will investigate the relationship between these variables. Through statistical methods and consideration of various factors, I aim to gain insights into the financial dynamics of the movie industry. The findings will provide valuable information for filmmakers, producers, and investors, helping them make informed decisions and optimize their strategies.

## Datasets
`movies.csv` - Uncleaned dataset of 6820 movies (220 movies per year, 1986-2016).


## Technical Implementation: Python Code Summary
**Libraries imported:** pandas, numpy, seaborn, and matplotlib.pyplot 

**Matplotlib settings:** Style set to 'ggplot', figure size set to (12, 8)

**CSV file reading:** 'movies.csv' file is read using pd.read_csv()

**Data preprocessing:** 'budget' and 'gross' columns are converted to numeric values, filled NaN values with 0, and cast as integers

**Scatter plot:** Budget vs. gross earnings scatter plot is created using plt.scatter()

**Regression plot:** Regression line plot is created using sns.regplot()

**Correlation analysis:** Pearson and Kendall correlation matrices are computed, and a heatmap is visualized using sns.heatmap()

**Categorical encoding:** Object columns are converted to categorical type and encoded as numerical codes

**Updated correlation analysis:** Correlation matrix is computed for numerical features and visualized using sns.heatmap()

**Correlation pairs and factorization:** Correlation matrix is computed by factorizing the DataFrame columns, and correlation pairs are printed

**Strip plot:** Strip plot of rating vs. gross earnings is created using sns.stripplot()
## Licensing, Authors, Acknowledgements
Data is scarped from [IMDb](https://imdb.com/)
