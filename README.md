
# Medical Expenses Prediction

Company wants to automate the medical expenses process (real time) based on customer detail provided while filling online application form. These details are age, sex, bmi, smoker and other.  

## 🛠 Programming language and packages

- Python
- NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn, Scipy.




  
## Project Description

- Required packages are imported. From kaggle dataset is readed. 

- **Univariate analysis** - Created Weight status column for easy visualization. Created age interval column for easy visualization. Visualized counts of categories in variables. Distribution of columns are visualized. Checked outliers by boxplot.

- **Bivariate Analysis** - Created expence range column for easy visualization. Relationship between two features are visualized by countplot.

- **Multivariate Analysis** - Visualized corr by heatmap. 

- **Feature Engineering** - 'age_', 'expence_range', 'weight_status' columns are removed from dataset.

- **Data Preprocessing** - Encoding,splitting data and data normalization is done on data.

- **Machine Learning Models** - LinearRegression, RandomForestRegressor and GradientBoostingRegressor model is created and performance are analysed. Best model is picked.

- **Model Improvement** - Transformation is done on expenses column and model created with transformation feature. Cross validation score is calculated. 




  
