# brand-analysis
Automobile brand analysis


1. **Data Import and Initial Exploration:**
   - The code begins by importing the necessary libraries, including Pandas, and loads a CSV file named 'Car_dataset.csv' into a DataFrame named 'data'.
   - The first 5 rows of the dataset are displayed using `data.head()`, and the last 5 rows are displayed using `data.tail()`.

2. **Data Cleaning and Preprocessing:**
   - Task 2: It replaces the misspelled 'toyoda' with 'toyota' in the 'company' column and saves the updated DataFrame to a new CSV file named 'car_data_updated.csv'.
   - Task 3: It identifies the company with the highest price and displays the company and its corresponding price.

3. **Data Filtering:**
   - Task 4: It filters the DataFrame to show only the rows where the 'company' is 'toyota'.

4. **Data Analysis:**
   - Task 5: It counts the occurrences of each unique 'company' in the dataset.

5. **Grouping and Aggregation:**
   - Task 6: It groups the data by 'company' and finds the maximum 'price' for each company.
   - Task 7: It groups the data by 'company' and calculates the mean 'average-mileage' for each company.

6. **Sorting:**
   - Task 8: It sorts the DataFrame by 'price' in descending order and displays the top 5 rows.

7. **Data Concatenation:**
   - Task 9: It creates two DataFrames, one for German car companies and another for Japanese car companies, and then concatenates them with keys 'Germany' and 'Japan'.

8. **Data Merging:**
   - Task 10: It merges two DataFrames, one containing car prices and the other containing horsepower, based on the 'Company' column.

9. **Notebook Conversion:**
   - Finally, the code uses Jupyter Notebook's `!jupyter nbconvert` command to convert the notebook into an HTML file named 'Project_1_Harshith_Srinivas.html'.

Overall, this code demonstrates data manipulation and analysis techniques using Pandas in Python. It covers tasks like data cleaning, filtering, aggregation, sorting, and merging, making it a comprehensive example of data analysis for your professor.
