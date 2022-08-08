# WEB3-PANDAS :panda_face:
open the :point_right: .ipynb file to see the content and explanation
# QUIZ ANSWERS :zap:

- Question 1 of 25:
What is a correct syntax to create a Pandas Series from a Python list?

pd.Series(mylist)  

- Question 2:
What is a correct syntax to return the first value of a Pandas Series?

myseries[0]  

- Question 3:
What is a correct syntax to add the lables "x", "y", and "z" to a Pandas Series?

pd.Series(mylist, index = ["x", "y", "z"])  

- Question 4:
What is a correct syntax to create a Pandas DataFrame?

pd.DataFrame(data)  

- Question 5:
What is a correct syntax to return the first row in a Pandas DataFrame?

df.loc[0]  

- Question 6:
What is a correct syntax to return both the first row and the second row in a Pandas DataFrame?

df.loc[[0, 1]]  

- Question 7:
What is the correct Pandas function for loading CSV files into a DataFrame?

read_csv()  

- Question 8:
What is a correct syntax to return the first 20 rows of a DataFrame?

df.head(20)  

- Question 9:
What is a correct syntax to return the entire DataFrame

df.to_string()  

- Question 10:
What is the correct Pandas function for loading JSON files into a DataFrame?

read_json()  

- Question 11:
What is a correct syntax to load a Python Dictionary called "data" into a Pandas DataFrame?

pd.DataFrame(data)  

- Question 12:
What does the Pandas head() method do?

Returns the headers and the specified number of rows, starting from the top  

- Question 13:
For the Pandas head() method, how many rows are returned by default, if you do not specify it?

5  

- Question 14:
What is a correct Pandas method for returning the last rows?

tail()  

- Question 15:
What is a correct Pandas method for removing rows that contains empty cells?

dropna()  

- Question 16:
True or false: by default, the Pandas dropna() method returns a new DataFrame, and will not change the original.

True  

- Question 17:
What is a correct method to fill empty cells with a new value?

fillna()  

- Question 18:
When using the Pandas dropna() method, what argument allowes you to change the original DataFrame instead of returning a new one?

dropna(inplace = True)  

- Question 19:
Mean, Median, Mode. Which one returns the value in the middle?

median()  

- Question 20:
Mean, Median, Mode. Which one returns the value that appears most frequently?

mode()  

- Question 21:
Mean, Median, Mode. Which one returns the average value?

mean()  

- Question 22:
What is a correct method to remove duplicates from a Pandas DataFrame?

df.drop_duplicates()

- Question 23:
What is a correct method to discover if a row is a duplicate?

df.duplicated()  

- Question 24:
What is a correct method to find relationships between column in a DataFrame?

df.corr()  

- Question 25:
What is a correct method to plot (draw) diagrams from the data in a DataFrame?

df.plot()  



