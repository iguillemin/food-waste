# Food-Waste-Project
The Food-Waste-Project produces optimized grocery lists of ingredients adjusted to number of people, length of time, purpose, and dietary restrictions, designed to minimize the amount of food-waste by the end of the time period. The food-waste optimizer uses datasets of consumer behavior and food spoilage statistics to classify common foods according to waste probability, then uses user preferences to produce a list of items that meets their requirements and maximizes food consumption. To accomplish this, we broke down the problem into three predictive components:

#Notebooks:

Reordering_Model_ML_Update_1.ipynb (estimates how likely a user is to actually use or repurchase an item)

waste_prediction_model(1).ipynb (identifies items historically associated with leftover quantities or low utilization)

Spoiler_Predictor_Update_1(1).ipynb (captures perishability and shelf‑life constraints)


#Notebooks for Other Features:

nutrition_food_update2(1).ipynb
Final_Grocery_model(1).ipynb

#Datasets:

FoodKeeper-Data.xls
aisles.csv
cleaned_nutrition.csv
cleaned_nutrition_engineered.csv
departments.csv
order_products__train.csv
products.csv

#Instructions


1.Download or clone this repository and keep all notebooks and datasets in the same folder.  

2. Open the notebooks in Jupyter Notebook or Google Colab. If using Colab, upload the dataset files first.  

3. Run the notebooks in this order:  

   - Reordering_Model_ML_Update_1.ipynb  
   - waste_prediction_model(1).ipynb  
   - Spoiler_Predictor_Update_1(1).ipynb  
   - nutrition_food_update2(1).ipynb  
   - Final_Grocery_model(1).ipynb  

4. The first three notebooks create predictions for reorder likelihood, waste risk, and spoilage risk.  

5. The final notebook combines those results with user inputs to generate an optimized grocery list.  

6. Update file paths if needed before running the notebooks.  
