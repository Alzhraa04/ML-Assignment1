# ML-Assignment1

## Dataset Information
- Dataset Name: FastFood Nutrition Dataset.
- Source / Link: Kaggle – https://www.kaggle.com/datasets/ulrikthygepedersen/fastfood-nutrition/data
- Number of Rows and Columns: 515 rows × 17 columns.

## Dataset Description
The dataset we used is the Fast Food Nutrition Dataset from Kaggle, which contains nutritional information for menu items across various
fast food restaurants. It has 515 rows and 17 columns, including features such as calories, total fat, saturated fat, trans fat,
cholesterol, sodium, carbohydrates, fiber, sugar, protein, vitamins, and calcium. This dataset allows us to explore differences in
nutritional content across restaurants and menu items, identify trends in calorie and nutrient distributions, and gain insights into which
items are higher or lower in certain nutrients.

## Column Descriptions
- restaurant:	Name of the fast food restaurant
- item:	Menu item name
- calories:	Energy content in calories
- cal_fat:	Calories from fat
- total_fat:	Total fat in grams
- sat_fat:	Saturated fat in grams
- trans_fat:	Trans fat in grams
- cholesterol:	Cholesterol in mg
- sodium:	Sodium in mg
- total_carb:	Total carbohydrates in grams
- fiber:	Dietary fiber in grams
- sugar:	Sugar in grams
- protein:	Protein in grams
- vit_a:	Vitamin A percentage 
- vit_c:	Vitamin C percentage 
- calcium:	Calcium percentage 
- salad:	Type or category of salad 

## Code / EDA Description
In the Jupyter Notebook, we performed an exploratory data analysis (EDA) on the dataset. First, we checked for missing values and
duplicates, then removed duplicates and filled missing numeric values with the column mean. We verified the data types and generated a
statistical summary to understand the distributions of different features. We also created several visualizations, including histograms,
scatter plots, boxplots, and correlation heatmaps, to analyze trends, patterns, and relationships between nutrients and restaurants. These
steps allowed us to clean the data and extract meaningful insights about fast food nutrition.

## Purpose of Using This Dataset
1. To perform Exploratory Data Analysis (EDA) on fast food nutritional information.
2. To understand trends, distributions, and relationships among nutritional values.
3. To learn how to clean data, handle missing values, and create meaningful visualizations.

## Data Cleaning Summary
- Duplicates removed: 2 rows removed
- Missing values handled: Numeric columns = replaced missing values with column mean (fiber, protein, vit_a, vit_c, calcium)
- Data types checked: numeric columns confirmed as numbers, text columns as strings

## Visualizations and Insights
1. Distribution plots: calories, total fat, sugar → identify skewed distributions and outliers
2. Comparison plots: average calories/protein by restaurant → detect differences between chains
3. Correlation plots: calories vs sodium, fat vs protein → find relationships between nutrients
4. Scatter plots: show how high-calorie items often have high sodium/fat content
5. Boxplots: detect extreme menu items in terms of calories/fat
6. Insights:
- High-calorie items often have high sodium and fat.
- Restaurants differ in nutritional content.
- Customers can use this analysis to make healthier choices.
