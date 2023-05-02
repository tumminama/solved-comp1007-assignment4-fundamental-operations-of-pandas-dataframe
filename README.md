Download Link: https://assignmentchef.com/product/solved-comp1007-assignment4-fundamental-operations-of-pandas-dataframe
<br>
This assignment helps you review the fundamental operations of Pandas DataFrame. Please download the data file <strong>automobile_data.csv</strong> from Moodle, and develop a Python program that performs the following tasks:

<ol>

 <li>Create a Pandas DataFrame by loading the file <strong>csv</strong>.</li>

 <li>Show the shape of the DataFrame.</li>

 <li>Show the first 8 rows and the last 8 rows of your DataFrame.</li>

 <li>Show the data types of every column of your DataFrame.</li>

 <li>There are some rows with missing data. Please drop these rows from the DataFrame.</li>

 <li>Show the shape of the DataFrame again.</li>

 <li>Create a new DataFrame that consists of all the rows of Toyota cars. You can first use <strong>groupby()</strong> function to generate a GroupBy object, and then use <strong>GroupBy.get_group()</strong> function to generate the DataFrame object. You can learn from the <strong>Grouping </strong>example at</li>

</ol>

<u>https://pandas.pydata.org/pandas‐docs/stable/user_guide/cookbook.html</u> ([114], [115], [117], [118]).

<ol start="8">

 <li>Find the average mileage of each car company. You can make use the GroupBy object created in Step 7.</li>

 <li>Sort all cars by the <strong>price</strong> column in descending order, and save the sorted table in a new CSV file automobile_data_new.csv. You can use the <strong>to_csv()</strong> function.</li>

 <li>Show the statistics information (such as mean, std, min, max, and 25/50/75% percentiles) of the final DataFrame.</li>

</ol>