# CarPrices_Dummy
<br> Here a Linear Regression Model has been made for the dataset of Cars to predict the Price of a Car given certain parameters. The model is trained against **Car Model, Mileage and Age** of the Car.
<br> In the Car dataset under **Car Model** column, different types of car names are mentioned. But as we know that the Linear Regression Model does not work for categoical variables it has to be converted to numerical values for the model to perfomly perfectly.
<br> The conversion from categorical to numerical values has been done using **.get_dummies()** method.
<br> Then the target column is droped and concatenated with the dummy values to get the final dataset.
<br> The Linear Regression Model is taken from the ***sklearn.linear-model*** package of Python.
<br> I have tested the model for various inputs and the overall score of the model is 94.17%.
