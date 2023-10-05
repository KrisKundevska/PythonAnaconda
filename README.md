# PythonAnaconda
This is a small project created as part of my training with Just IT. All the Python code was done in Anaconda and Jupitor Notebooks. Most parts are work compleated in class.

[Part 1](https://anaconda.cloud/api/nbserve/launch_notebook?nb_url=https%3A%2F%2Fanaconda.cloud%2Fapi%2Fprojects%2F465686ba-81d8-4a68-a413-61ee98b1f969%2Fversions%2F0889cd88-08d1-409b-acea-09df1b7e1daf%2Ffiles%2FPython%20Basics.ipynb)

In Part one we essentially covers a range of Python basics, including string manipulation, variable assignment, data types, arithmetic operations, input handling, and loop structures. It serves as a simple example to help beginners understand these fundamental concepts in Python programming.

[Part 2](https://anaconda.cloud/api/nbserve/launch_notebook?nb_url=https%3A%2F%2Fanaconda.cloud%2Fapi%2Fprojects%2F26872cce-6aa6-4114-a501-69b7b7116217%2Fversions%2F4c942396-c505-436f-b8e3-600fca7d1fbe%2Ffiles%2FHomework_KristinK.ipynb)

In Part two we have 3 sections
Section 1 - Calculate Hypotenuse:

In this section, the code sets up a while loop that repeatedly asks the user for input. The user can enter 'quit' to exit the loop or provide values for the lengths of two sides of a right triangle. The code then calculates and prints the hypotenuse of the triangle using the Pythagorean theorem.

Section 2 - Conversion between Miles and Kilometers:

This section involves another while loop that offers a menu for the user to choose between miles to kilometers conversion, kilometers to miles conversion, or to exit the loop by entering 'quit.' The code handles these options and performs the selected conversion accordingly, displaying the result.

Section 3 - Calculate Circle Area:

In the final section, the code calculates the area of a circle. It prompts the user to input the radius of the circle, then calculates and prints the area using the formula for the area of a circle (π * radius^2).

Overall, these sections provide examples of input validation, arithmetic calculations, and the use of the math library for mathematical operations in Python. It demonstrates how to create interactive programs that engage with users and perform calculations based on their input.

[Part 3](https://anaconda.cloud/api/nbserve/launch_notebook?nb_url=https%3A%2F%2Fanaconda.cloud%2Fapi%2Fprojects%2F4860d5eb-60dc-4b37-9c78-036e42addee8%2Fversions%2F2b1d5820-4eb4-45ea-9b0a-5d6e070ad314%2Ffiles%2FPandas%20Practice.ipynb)

In Part three we have 7 sections. This was an excersize we had to do in class to understand Pandas derectory. The sections we covered were
Importing Libraries: The code starts by importing the Pandas library. Pandas is commonly used for data manipulation and analysis.

Loading a Dataset: The code reads a dataset from a CSV file named 'data.csv' and assigns it to a DataFrame named 'ecom'. It specifies the encoding as 'unicode_escape' to handle any special characters.

Data Exploration:

ecom.head(): Displays the first few rows of the DataFrame to give an overview of the data.
ecom.tail(10): Shows the last 10 rows of the DataFrame.
ecom.info(): Provides information about the DataFrame's structure, including the number of rows, columns, data types, and the presence of missing values.
ecom.describe(): Displays statistical measurements like count, mean, standard deviation, minimum, and maximum for numeric columns.
Data Cleaning:

ecom.columns: Lists the column names in the DataFrame.
The code checks for missing values using ecom.isna().sum() and ecom.isnull().sum().
It calculates the percentage of null rows relative to the total number of rows.
Missing values are dropped using ecom.dropna(inplace=True) to clean the data.
Data Analysis:

The code explores different aspects of the data, including the highest and lowest unit prices.
It calculates the average unit price.
Creates a new 'Total' column, which represents the total amount spent by multiplying the 'Quantity' and 'UnitPrice' columns.
Data Visualization and Analysis:

The code analyzes spending based on countries and customers, identifying high spenders.
It finds the country with the least total spending and identifies people in Spain who spent more than the average total.
Optional Grouping and Aggregation:

It groups the data by country and calculates the mean spending using both aggregation and the apply function.
The code provides insights into data analysis and manipulation using Pandas, covering various operations such as data loading, cleaning, exploration, and visualization. It also demonstrates how to use groupby for more advanced data analysis and aggregation.

[Part 4](https://anaconda.cloud/api/nbserve/launch_notebook?nb_url=https%3A%2F%2Fanaconda.cloud%2Fapi%2Fprojects%2F5beb9a92-60ac-4337-8a3d-45770edb9fc9%2Fversions%2F0287bcfe-941f-4b36-b524-fb74287e508d%2Ffiles%2FPython%20Part%203%20DA%20using%20Python%20(1).ipynb>)

In Part four we demonstrate working with Pandas DataFrames and provided examples of various operations on a sample dataset. 

Importing Pandas: The code begins by importing the Pandas library, which is used for data manipulation and analysis.

Creating DataFrames:

Two DataFrames are created. The first one, df, is created from a dictionary data containing information about calories and duration.
The second one, also named df, is created from a list mylist, which contains mixed data types (integers and strings). It also demonstrates that DataFrames can be created from lists.
Reading Data from a CSV File:

It reads data from a CSV file named "student.csv" and creates a DataFrame named df. This DataFrame represents student information, including ID, name, class, marks, and gender.
Data Exploration:

The code displays the first 10 rows of the DataFrame using df.head(10).
It displays 12 random rows from the DataFrame using df.sample(12).
It displays the last 5 rows of the DataFrame using df.tail(5) and transposes them.
It demonstrates various ways to access and select specific columns of the DataFrame, such as df["name"], df[["id", "name"]], and df[["name", "class"]][:5].
Basic Statistics:

The code calculates basic statistics like the minimum, maximum, and median of the "Mark" column using df["Mark"].min(), df["Mark"].max(), and df["Mark"].median().
Data Filtering:

It demonstrates how to filter data based on specific conditions, such as filtering students with marks greater than or equal to 85 and filtering male students.
Value Counts:

The code counts the number of students per class using df["class"].value_counts().
It counts the total number of male and female students using df["gender"].value_counts().
Data Information and Description:

It shows how to obtain information about the DataFrame's structure using df.info() and summary statistics using df.describe().
The code provides practical examples of working with Pandas DataFrames, including creating them, reading data, exploring data, filtering, and obtaining summary statistics.
