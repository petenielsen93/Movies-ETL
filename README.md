# Movies-ETL

The purpose of this project was to create an ETL function: an automated pipeline that takes in new data, performs the correct transformations, and loads the data into tables. In order to do this, we mainly refactored code from the module. In the module, we first imported our JSON and CSV files, and reformatted the data into DataFrames. 

After extraction, we analyzed our data and the columns that denote the information. We decided which columns were more pertinant than others, and which columns would need the most work transforming. We then created functions that merged the column names, combined alternate movie titles into one list, and used regex to create a format for movie budgets. 

After transforming the data, we then uploaded it into a Postgres database for storage, where more effective analysis could take place. This project was the accumulation of our newly learned skills over the past 2 months and provided a taste of what a real world project would be like.