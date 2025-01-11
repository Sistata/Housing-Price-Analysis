This project involves the analysis of housing prices in King County, Washington, using linear regression. The dataset utilized for this analysis is sourced from Kaggle, providing comprehensive information on homes sold in the region between May 2014 and May 2015. The dataset encompasses 21 columns, each capturing distinct attributes related to the housing transactions. 
<br><br>
1. id : A notation for a house<br>
2. date : Date the house was sold<br>
3. price : Price of the house<br>
4. bedrooms : Number of bedrooms<br>
5. bathrooms : Number of bathrooms<br>
6. sqft_living : Square footage of the home<br>
7. sqft_lot : Square footage of the lot<br>
8. floors : Total floors in the house<br>
9. waterfront : House with the waterfront view<br>
10. view : Has been viewed<br>
11. condition : overall condition oh house<br>
12. grade : Grade given to the housing unit, based on King County grading system<br>
13. sqft_above :Square footage of house apart from basement<br>
14. sqft_basement : Square footage of the basement<br>
15. yr_built : Year when the house was built<br>
16. yr_renovated : Year when house was renovated<br>
17. zipcode : Zip code<br>
18. lat : Latitude coordinate<br>
19. long : Longitude coordinate<br>
20. sqft_living15 : Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area<br>
21. sqft_lot15 : LotSize area in 2015(implies-- some renovations)<br><br>


The workflow for this analysis comprises the following key steps:<br><br>

**Exploratory Data Analysis (EDA):**<br>
Gain insights into the dataset by exploring its features and distributions.<br> 

**Data Cleaning:**<br>
Address any inconsistencies or missing values in the dataset to ensure data integrity and prepare it for modeling.<br>

**Outlier Detection:**<br>
Identify and handle outliers within the dataset. <br>

**Build and train a linear regression model:**<br>
The goal is to establish a predictive model for housing prices.<br>

**Model Evaluation:**<br>
Assess the performance of the linear regression model through appropriate evaluation metrics. This step ensures that the model provides accurate predictions and generalizes well to new data.<br>

**Visualization of Results:**<br>
Present the findings and insights derived from the linear regression model in a visually comprehensible manner.

# Part 1: Import Data and Explore

Let's initiate Exploratory Data Analysis (EDA) by reading and summarizing the data. To facilitate this analysis, I will import and utilize relevant libraries.

```
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from IPython.display import display
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score 
from sklearn.metrics import mean_squared_error
```


