# Wine Quality Analysis in R

- This project analyzes the quality of red wine using various statistical and visualization techniques in R
- It includes data exploration, feature transformation, univariate and multivariate analysis, correlation matrices, and regression modeling

## 📂 Project Structure:

- wineQualityReds.csv - The dataset used for analysis
- wine_analysis.R - The R script containing data processing, visualization, and modeling
- README.md - Documentation for the project

## 📦 Dependencies:

Ensure you have the following R packages installed:

- install.packages('abdiv')
- install.packages("GGally")
- install.packages("memisc")
- install.packages("pander")
- install.packages("corrplot")
- install.packages("gridExtra")

## 🚀 Getting Started:
## Clone this repository:
- git clone https://github.com/your-username/wine-quality-analysis.git
- cd wine-quality-analysis

## Load the dataset into R:
- wine <- read.csv('path/to/wineQualityReds.csv')
- Run the wine_analysis.R script in an R environment (RStudio or Jupyter Notebook with R kernel)

## 📊 Data Processing:
- Transforming Quality: Converted wine quality ratings from integers to factors
- Creating a New Variable: Defined a categorical variable rating (bad, average, good)
- Data Exploration: Summary statistics and structure of the dataset

## 📈 Visualizations:
- Univariate Analysis: Histograms, boxplots, and bar charts for each feature
- Multivariate Analysis: Scatter plots, correlation matrices, and regression analysis

## Example Visualizations:
- Distribution of wine quality
- Relationship between acidity levels and pH
- Correlation between alcohol content and quality

## 🔬 Key Findings:
- Alcohol Content: Strongly correlated with wine quality
- Acidity Levels: Influence the perception of quality
- Sulfur Dioxide Levels: Affect wine preservation and taste

## 📌 Next Steps:
- Implement machine learning models to predict wine quality
- Explore additional statistical methods for feature selection
- Perform hypothesis testing for deeper insights

## 🤝 Contributing:
Feel free to fork this repository and submit pull requests with improvements or new analyses

## 🚀 Happy Analyzing !! 🍷
Let me know if you need any modifications !! 🚀






