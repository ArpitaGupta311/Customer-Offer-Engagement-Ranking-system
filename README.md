# Customer-Offer-Engagement-Ranking-system
Developed a predictive analytics pipeline to model the probability of customer engagement with promotional offers. The end objective of this is to show the most relevant offers on the top ranks to increase customer's clicks and hence overall engagement with the offers. So I integrated and engineered features from multiple datasets (user, offer, events). I firstly trained the dataset individually on all the models: XGBoost, LightGBM, CatBoost, and Adaboost. I obtained similar results with XGBoost, LightGBM, and CatBoost.And hence I trained an ensemble model of XGBoost and LightGBM with Lamdarank to optimize click-through rate prediction and evaluated using MAP@7.

More ways which can optimise the dataset(an idea, I have not tested): we can itegrate catboost as well. The reason I did not try this was because of the time it was taking. I highly recommend you to try this if you have a GPU integrated to your device, which can make this run a little faster. And do let me know the results :)

Edit: I am attaching the drive link for the dataset - https://drive.google.com/drive/folders/13j2Z1JMalNu0uaJoGt6ApU-7_PvipTwL?usp=sharing
