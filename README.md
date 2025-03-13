# Car-price-prediction-model
# Introduction:
In this project, we aim to use machine learning to predict car prices by examining three different algorithms: decision tree, linear regression, and support vector machine (SVM). We'll analyze how well each algorithm performs using a dataset of real car prices. We'll also look into how different settings and selecting specific features affect the accuracy and complexity of the models. Ultimately, we hope to learn more about how machine learning can be used to solve problems like predicting car prices.

# Dataset Description:
The dataset includes various features of car-related details such as the year of manufacture, selling price, kilometers driven, fuel type, seller type, transmission type, number of previous owners, mileage, and engine specifications. These attributes provide valuable insights into the factors influencing car prices and can be used to develop predictive models for estimating the selling price of cars.

   This Dataset contains 12 features:
●	Name: Name of car
●	Year: Year of production
●	Selling price: Car price
●	Km driven: How much it was ridden
●	Fuel: The type of fuel the car uses
●	Seller type: Whom or where it was bought from
●	Transmission: What type of transmission it uses
●	Owner: How many hands changed before buying
●	Mileage(km/ltr/kg): How much it was driven
●	Engine: How many ccs it has

In summary, we explored four different machine-learning methods to forecast car prices based on various factors. We utilized decision tree, linear regression, and support vector machine (SVM) models for this purpose. Our data preparation steps involved handling missing values, converting categorical features into numerical ones using one-hot encoding, and standardizing the data with StandardScaler. It was essential to split the dataset into 70% for training and 30% for testing. Upon assessing the models, we found that both the Decision Tree and Linear Regression models performed exceptionally well, showing high accuracy without overfitting or underfitting issues. Although the SVM model performed decently, it didn't quite match the effectiveness of the Decision Tree and Linear Regression models.



