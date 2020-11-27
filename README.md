# Datasets for practice
This Repository consists of sample datasets that can be used for practise and exercises.

To benefit the maximum out of this repo, we should leverage the reading csv from raw csv `URL` feature that is present in Pandas `0.19.2` and up, in other words we can direclty pass the `URL` to the raw csv file in `pandas.read_csv()` method.

*To import the dataset directly via URL*: 
1. Right click on hyperlink of desired dataset.
2. Select `Copy Link Location`.
3. Use this copied URL instead of mentioning file path in `read_csv()`.

<ins>Example :</ins>
```python
import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/iris.csv')
df.head()
```


|	|sepal_length	|sepal_width	|petal_length	|petal_width	|species	|
|---|-------------- | ------------- | ------------- | ------------- | --------- |
|0	|5.1	    	|3.5		    |1.4		    |0.2	    	|setosa	    |
|1	|4.9		    |3.0		    |1.4		    |0.2	    	|setosa 	|
|2	|4.7	    	|3.2		    |1.3		    |0.2	    	|setosa	    |
|3	|4.6	    	|3.1		    |1.5		    |0.2	    	|setosa	    |
|4 	|5.0	    	|3.6		    |1.4		    |0.2	    	|setosa	    |


## Data sets


### Regression
* [Salary data - Mini](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/salary_data.csv)
* [Petrol Consumption](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/petrol_consumption.csv)
* [Airline Passenger](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/airline_passengers.csv)
* [Automobile Prices - Mini](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Automobile_mini.csv) - *less features and records than `Automobile Prices`*
* [Automobile Prices](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Automobile.csv)
* [Boston House Prices](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/boston_housing.csv)
* [California Housing Data (1990)](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/cal_housing.csv)
* [Autompg](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/auto-mpg.csv)
* [Weather - Conditions in World War Two](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Weather.csv)




### Classification
* [Iris](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/iris.csv)
* [Balance Scale](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/balance.csv)
* [Diabetes mini](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/diabetes_mini.csv) - *glucose and bloodpressure only*
* [Diabetes](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/diabetes.csv)
* [Titanic-Mini](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Titanic_Smaller_Ver.csv) - *less records than `Titanic`*
* [Titanic](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/titanic.csv)
* [Breast Cancer](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/breast_cancer.csv)
* [Loan Status](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/loan_status.csv)
* [Petrol Consumption](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/petrol_consumption.csv)
* [Wine Type](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/wine_cultivar.csv) - *Classification Based on 'type of cultivar'*
* [Wine Quality](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/winequality-red.csv) - *Only Red Wine*
* [Wine Quality](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/winequality.csv) - *Red and White Wine*
* [IMDB movie rating](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/movie_metadata.csv)
* [Shopping Spending Score](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/shopping_data.csv)
* [Bill Authentication/Bank Note Authentication](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/bank_bill_authentication.csv)
* [Weather Status](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/weather_mini.csv)
* [SMS Spam Ham](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/sms_spam.csv)
* [Restaurant Customer Reviews](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/restaurant_review.tsv)
* [Spooky Author Identification](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/spooky_author_identification.csv) - *NLP Problem*


### Clustering 
* [Iris](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/iris.csv)
* [Credit Card usage behaviour](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/credit_card.csv)
* [Wholesale Customers](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Wholesale_customers.csv)
* [Sonar Rock Mines - EDA](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/sonar_mine.csv)
* [Store Optimization (Market Basket Optimization) - EDA](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Market_Basket_Optimisation.csv)

