# portfolio-project-1-hotel-bookings
1. **Importing Libraries**: This section imports necessary libraries and suppresses warnings.

2. **Loading Dataset**: It loads a dataset named `hotel_bookings 2.csv` using pandas.

3. **Exploratory Data Analysis and Data Cleaning**: This section examines the dataset, checks for null values, drops irrelevant columns, converts data types, and removes outliers.

4. **Analysis and Visualization**: This part includes various analyses and visualizations of the dataset. For example:
   - Calculating the percentage of canceled bookings.
   - Creating bar plots to show the count of reservations based on cancellation status and hotel type.
   - Grouping data by date to show the average daily rate (ADR) in city and resort hotels over time.
   - Analyzing the reservation status per month and ADR per month for canceled reservations.
   - Creating a pie chart to show the top 10 countries with the most canceled reservations.
   - Plotting the ADR over time for canceled and not canceled reservations.

5. **Explanation**: The last few lines of code plot the ADR over time for both canceled and not canceled reservations. It focuses on data between 2016 and 2017, excluding September 2017.

Overall, this code provides a comprehensive analysis of hotel booking data, including cancellation trends, ADR analysis, and country-specific insights.

