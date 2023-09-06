## Predicting Median Housing Projects using Scikit-Learn and Linear Regression

The input is a Housing database containing district-wise information like latitude, longitude, median age, total rooms, total bedrooms, population, households, median income, median house value, and proximity to the ocean.

After preliminary data cleaning, EDA, and visualization, and by looking at the correlation matrix, I decided to keep only certain attributes that would contribute to housing prices. Also feature engineered three new attributes of interest - Rooms per household, Bedrooms per room, and Population per household.

The training-test ratio was set at 80%-20%. I used three machine learning models using Scikit-Learn - Linear Regression, Decision Trees and Random Forest. From the three, Random Forest had the most accurate results, but predictably, the worst performance. Meanwhile Linear Regresion was the fastest but had the poorest accuracy.

Please click on [Housing_Data_ML.ipynb](https://github.com/sephi-22/Housing_Data/blob/master/Housing_Data_ML.ipynb)
 to read the entire Jupyter Notebook.