# PandasAssignment

Q1. How do you load a CSV file into a Pandas DataFrame?
A- df.to_csv('friends.csv')

Q2. How do you check the data type of a column in a Pandas DataFrame?
A-  newdf.dtypes

Q3. How do you select rows from a Pandas DataFrame based on a condition?
A-  by using index number
    newdf[1,2]

Q4. How do you rename columns in a Pandas DataFrame?
A-  newdf.columns=list("ABCDE")

Q5. How do you drop columns in a Pandas DataFrame?
A-  newdf.drop(0, axis=1)

Q6. How do you find the unique values in a column of a Pandas DataFrame?
A-  df.B.unique()

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?

Q9. How do you concatenate two Pandas DataFrames?

Q10. How do you merge two Pandas DataFrames on a specific column?

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?

Q12. How do you pivot a Pandas DataFrame?

Q13. How do you change the data type of a column in a Pandas DataFrame?

Q14. How do you sort a Pandas DataFrame by a specific column?
A-  newdf.sort_index(axis=1, ascending=False)

Q15. How do you create a copy of a Pandas DataFrame?
A-   newdf2=newdf.copy()

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?
A-   newdf.loc[(newdf[1]<0.3)]

Q17. How do you calculate the mean of a column in a Pandas DataFrame?
A-   newdf[['weight']].mean(axis=1)

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?
A-   df['column_name'].std() 

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?
A-   print(data['column1'].corr(data['column2']))

Q20. How do you select specific columns in a DataFrame using their labels?

Q21. How do you select specific rows in a DataFrame using their indexes?
A-   df.iloc[[4]]
Q22. How do you sort a DataFrame by a specific column?

Q23. How do you create a new column in a DataFrame based on the values of another column?

Q24. How do you remove duplicates from a DataFrame?

Q25. What is the difference between .loc and .iloc in Pandas?
A-   by using loc we can access row & column by their index name not a number & by using iloc we can access row & column by their index number not a name
