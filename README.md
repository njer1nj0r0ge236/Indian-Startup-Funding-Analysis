# Indian-Startup-Funding-Analysis


.env :
 
    the environment that has the database details saved in it

database_connection_config :

    the 2021 and 2021 sql tables to csv files

Indian_startup_funding :

    the data is loaded, cleaned, and visualized

HYPOTHESIS

Null hypothesis-Investors interest in startups are directly correlated with the startup industry

Alternative hypotheses-Investors interest in startups are independent of startup industry

QUESTIONS

    Which startup industry/sector attracts more investors?
    Does investment amount correlate with the age of the startups?
    Does the location of the startup affects investors interest in investing?
    Which funding year saw investors investing more into startups?
    Which stage of funding receives the most funding?
    Is there a relationship between investor amount, location of startup and industry of startup?
    
# Problems with data
    MAJOR ISSUES

    Wrong datatypes
    Missing values
    Combination of non-printable characters with strings (2018 data)
    Amount column having two different amount in the same row
    Misplaced values (the stage column having amount information and amount column having stage information, 2019-2021)
    Inconsistent column names

SOLUTIONS

    Change to appropriate datatype
    Rename column names in df_2018 and df_2019
    Correct the datatypes in 'Amount' column for all the datasets
    Remove 'column10' in df_2020
    Fill missing values with median and mode
    Clean the HeadQuarter  column in df_2018 to only retain the first part
    Add missing columns in df_2018 and fill them with NAN
    Use the simpleImputer to replace NaN values


    


