# iphone_price_prediction
Now you can predict the next iphone price and it may be cost you and arm and a leg with just 6 lines of python code!!
I have done it by using Pycharm which is an python code editor.
In the first I have written **pip install pandas** in the terminal.
In the first of the codeI have imported pandas.
And then I have writte from sklearn.linear_model import LinearRegression.
Then I have created a variable called data and entered the value as pandas.read_csv('iphone_price.csv').
Then I have created another variable called model and enterted the value as Linear Regression().
Then I have written model.fit(data[['version']], data[['price']]).
Then to print the prediction of the iphone price I have written print(model.predict([[13]])).
And now you are ready for the prediction of the next iphone!!
