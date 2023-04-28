# Indian-Startup-Funding-Analysis

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
    Replace empty rows with missing values and dropna values or fill with a mean or median
    Remove all non printable characters
    Delete those rows or fill with one value
    Rearrange values correctly
    Change column nam


