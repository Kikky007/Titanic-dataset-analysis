# Titanic-dataset-analysis
This project analyzes the Titanic dataset to provide insights into different factors that might have influenced passenger survival. It uses Python for data cleaning, exploratory data analysis, and data visualization.
## Dataset Overview
The dataset contains information about Titanic passengers, including their demographics, travel class, fare, and survival status. The dataset was gotten from darey.io, the platform I am learning data analysis. [Download here](https://docs.google.com/spreadsheets/d/1QXdjcc2iUgmyBIJZwjxYST-um3FpON5X/edit?usp=sharing&ouid=109196982209842045191&rtpof=true&sd=true) . The given dataset has record of 891 passengers, with 15 columns.

### Dataset columns

**'survived':** Survival status (0 = No, 1 = Yes) 

**'pclass':** Passenger class (1st, 2nd, 3rd) 

**'sex':** (male/female)

**'age':** Age of the passenger

**'sibsp':** number of siblings/spouses aboard

**'parch':** number of parents/children aboard

**'fare':** fare made for the tickets

**'embarked':** port of embarkation (C= Cherbourg, Q=Queenstown, S= Southampton)

**'class':** Ticket class (first, second , third)

**'who':** categorization of the passenger (man, woman, child)

**'adult_male':** Indicates if the passenger is an adult male(TRUE/FALSE)

**'deck':** The deck the passengers are assigned to

**'embark_town':** Name of the town the passenger embarked

**'alive':** survival status (yes/no)

**'alone':** indicates if the passenger was alone or not (true/false)

### Data Cleaning 

In the downloaded titanic dataset, I identified the columns for missing values. There are four columns with missing values: age, embarked, deck and embarked_town. For these values I did the following:

**Fill missing values for “age” with the median** (dataset is right skewed, so median chosen as it is more robust in dealing with outliers… this does produce bias so be mindful while interpreting).

**Drop the rows with missing 'embarked values"**

**Drop the ‘deck’ column because of too many missing values**

###
Here is the cleaned titanic dataset [Download here](https://drive.google.com/file/d/1xUwgCaqfGq7L9ebol4cNYP15Yae4ndgD/view?usp=sharing) . After the data cleaning, the data entry was reduced to 889 passengers and 14 columns, having dropped 'deck column. 
