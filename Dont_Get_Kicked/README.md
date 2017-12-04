# Don't_Get_Kicked

## [Description](https://www.kaggle.com/c/DontGetKicked#description)

One of the biggest challenges of an auto dealership purchasing a used car at an auto auction is the risk of that the vehicle might have serious issues that prevent it from being sold to customers. The auto community calls these unfortunate purchases "kicks".

Kicked cars often result when there are tampered odometers, mechanical issues the dealer is not able to address, issues with getting the vehicle title from the seller, or some other unforeseen problem. Kick cars can be very costly to dealers after transportation cost, throw-away repair work, and market losses in reselling the vehicle.

Modelers who can figure out which cars have a higher risk of being kick can provide real value to dealerships trying to provide the best inventory selection possible to their customers.

The challenge of this competition is to predict if the car purchased at the Auction is a Kick (bad buy).

## [Background](https://www.kaggle.com/c/DontGetKicked#background) 

Carvana is a start-up business that is being launch by a well-established American company. Its goal is to completely change the way people buy, finance, and trade their used vehicles by replacing physical infrastructure with technology and top of the line scientific models. It is an ambitious project that will require building new analytics and systems for which there are no precedent.

Carvana offers start-up company ambitions, attitudes, and atmosphere within established company stability. We are looking for extremely talented people with a passion for using technology in revolutionary ways with an eye toward flexibility and scalability.

## Take one look

<img src="https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/images/Dashboard%201.png" width="900">

Histgram of numerical features

<img src="https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/images/attribute_histogram_plots.png" width="700">

Covariance of numerical features

<img src="hhttps://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/images/covariance%20matrix%20heatmap.png" width="700">

[Statistical discription and preprocessing using label encoder](https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/Car%20Auction_encoder.ipynb)

[Another way for categorical variables using onehot dummy method](https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/Car%20Auction_onehot.ipynb)

## Best Modeling using XGBoost
[Rank 28 with Score 0.25205](https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/XGB_onehot.ipynb)

## Modeling: RandomForest, AdaBoost, DecisionTree and Ensembling 
[Modeling using encoder data](https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/Deep_Modeling_encoder.ipynb)

[Modeling using onehot data](https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/Deep_Modeling_onehot.ipynb)

## Oversample plus SVM
[Oversample plus SVW using onehot data](https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/SVM_SMOTE_Modeling_onehot.ipynb)

## Comparison between oversample methods from imblearn examples
[Plot over sampling benchmark](https://github.com/wangruinju/Kaggle-Project/blob/master/Dont_Get_Kicked/plot_over_sampling_benchmark.ipynb)
