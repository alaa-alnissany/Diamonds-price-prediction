# Diamonds-price-prediction
Predict the price of Diamonds using regression models trained on the Diamonds Dataset: "https://www.kaggle.com/datasets/shivam2503/diamonds".

I used multi algorithms in Exploratory Data Analysis (EDA):
  1. Predict the sparse features.
  2. Adding new features.
  3. Feature selection using Kbest based on the Chi_square test, using some regression models, information Gain, correlation..etc.
  4. Analyse features' relation with the price columns.
  5. Remove all the outliers using the Interquartile range (IQR).
  
Then, the train/test sets were split using stratified sampling depending on the most important feature.

Then find the best combination of algorithms to achieve high performance.

and train models and choose the model with the lowest root mean square error to predict test values. 
