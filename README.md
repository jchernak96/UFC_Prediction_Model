# UFC_Prediction_Model
Using trees and XGBoost to predict UFC fights, XGBoost process is a product of a few tutorials (Ben Baldwin in particular).

1. Data

Fight data is sourced from the following Kaggle link: https://www.kaggle.com/rajeevw/ufcdata
Odds  data is sourced from the following Kaggle link: https://www.kaggle.com/mdabbert/ufc-fights-2010-2020-with-betting-odds

I joined these data sources together so the odds of a fighter would serve as a feature in the model.

2. Methods

I used 3 different approaches.  
      1. Pruned Trees
      2. Boosted Tree
      3. XGBoost

3. Results 

The XGBoost model performed best with a 35% test error rate. A plot is shown below displaying the results. 

![XGBoost](https://user-images.githubusercontent.com/53879645/117492370-8428d100-af3f-11eb-844d-323d9baca16a.png)
