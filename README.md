# Datasets for practice
This Repository consists of sample datasets that can be used for practise and exercises.

To benefit the maximum out of this repo, we should leverage the reading csv from raw csv `URL` feature that is present in Pandas `0.19.2` and up, in other words we can direclty pass the `URL` to the raw csv file in `pandas.read_csv()` method.

*To import the dataset directly via URL*: 
1. Click on link besides the desired dataset.
    Taking `Iris` dataset for instance.
2. Copy the URL of the tab opened.
    For `Iris`,  https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/iris.csv
3. Use the link instead of mentioning file path in code use raw csv link, like in the code snippet below.
```sh
import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/iris.csv')
df.head()
```

<table class="dataframe" border="1">
  <thead>
    <tr>
      <th></th>
      <th>sepal_length</th>
      <th>sepal_width</th>
      <th>petal_length</th>
      <th>petal_width</th>
      <th>species</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>5.1</td>
      <td>3.5</td>
      <td>1.4</td>
      <td>0.2</td>
      <td>setosa</td>
    </tr>
    <tr>
      <th>1</th>
      <td>4.9</td>
      <td>3.0</td>
      <td>1.4</td>
      <td>0.2</td>
      <td>setosa</td>
    </tr>
    <tr>
      <th>2</th>
      <td>4.7</td>
      <td>3.2</td>
      <td>1.3</td>
      <td>0.2</td>
      <td>setosa</td>
    </tr>
    <tr>
      <th>3</th>
      <td>4.6</td>
      <td>3.1</td>
      <td>1.5</td>
      <td>0.2</td>
      <td>setosa</td>
    </tr>
    <tr>
      <th>4</th>
      <td>5.0</td>
      <td>3.6</td>
      <td>1.4</td>
      <td>0.2</td>
      <td>setosa</td>
    </tr>
  </tbody>
</table>



## Data sets


### Regression
* [Salary data - Mini](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/salary_data.csv)
* [Petrol Consumption](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/petrol_consumption.csv)
* [Airline Passenger](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/airline_passengers.csv)
* [Automobile Prices - Mini](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Automobile_mini.csv)
* [Boston House Prices](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/boston_housing.csv)
* [California Housing Data (1990)](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/cal_housing.csv)
* [Autompg](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/auto-mpg.csv)
* [Automobile Prices](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Automobile.csv)
* [Weather - Conditions in World War Two](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Weather.csv)




### Classification
* [Iris](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/iris.csv)
* [Balance Scale](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/balance.csv)
* [Diabetes](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/diabetes.csv)
* [Titanic-Mini](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Titanic_Smaller_Ver.csv)
* [Petrol Consumption](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/petrol_consumption.csv)
* [Titanic](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/titanic.csv)
* [Wine Quality](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/winequality-red.csv) - Only Red Wine
* [Wine Quality](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/winequality.csv) - Red and White Wine
* [IMDB movie rating](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/movie_metadata.csv)
* [Shopping Spending Score](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/shopping_data.csv)
* [Bill Authentication/Bank Note Authentication](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/bank_bill_authentication.csv)
* [Weather Status](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/weather_mini.csv)
* [Spooky Author Identification](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/spooky_author_identification.csv) - NLP Problem


### Clustering 
* [Iris](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/iris.csv)
* [Credit Card usage behaviour](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/credit_card.csv)
* [Wholesale Customers](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Wholesale_customers.csv)
* [Sonar Rock Mines - EDA](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/sonar_mine.csv)
* [Store Optimization (Market Basket Optimization) - EDA](https://raw.githubusercontent.com/rahul96rajan/sample_datasets/master/Market_Basket_Optimisation.csv)
