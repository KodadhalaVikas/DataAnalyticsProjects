# DataAnalyticsProjects
Data Analysis on few data sets

Data_Analytics_Projects-
Data Analytics and Analysis on few datasets Inter-State Probability Transactions under ONORC plan during Jul 2021 [Government Dataset]

Dataset Description: This report analyzes state probability transaction data between different Indian states. The dataset consists of 315 rows and 7 columns, including home state, sale state, transaction count, and (month, year).

The columns in our dataset are homestate code, salestate code, month, year.

Observations:

Delhi and Uttar Pradesh dominate in terms of transactions.

Although there are variations by state, there was no statistically significant difference between the major states.

Smaller states like Goa and Daman & Diu have significantly fewer transactions.

The dataset is complete with no null values and is very clean.

There are no duplicate entries.

The transaction count is much more in big states

Description:

Dataset contains 86 entries and 12 columns.

The "Total" column seems to represent the total marks.

Other columns represent:

Q1aM4 - marks for question 1a (out of 4)

Q1bM6 - marks for question 1b (out of 6)

Q2aM6 - marks for question 2a (out of 6)

Q2bM4 - marks for question 2b (out of 4)

Q3aM5 - marks for question 3a (out of 5)

Q3bM5 - marks for question 3b (out of 5)

Q4aM3 - marks for question 4a (out of 3)

Q4bM7 - marks for question 4b (out of 7)

Q5M10 - marks for question 5 (out of 10)

Q6aM4 - marks for question 6a (out of 4)

Q6bM6 - marks for question 6b (out of 6)

Dataset size: (86 × 12 columns) Dataset Observation:

Total marks distribution:

The total marks range from 3 to 40, with an average of ≈ 29.36.

Most students scored between 22 and 34, indicating a fairly consistent performance.

Missing data:

We remove the missing values and replace them with mean values.

Q5 has the highest scores, where it is considered to be an easy one.

Description: The Midmarks dataset contains midterm exam marks for students in different sections. The columns of the dataset are:

S.NO: Serial number of students

Section: Section name

DV, M-II, PP, BEEE, FL, PEMS: Subject names with corresponding scores

Observation: The dataset contains students' midterm marks for multiple subjects.

Missing values: Some subjects had missing values in marks, which were handled during analysis.

Marks distribution: Histograms and total plots showed normal mark distribution patterns.

Observed distributions for the different analysis of different subjects.

Statistical Tests on Midmarks dataset Dataset: Midmarks.csv Dataset Description: This dataset describes the midmarks scores of students from different sections. The columns of the dataset are:

S.No: Serial number of students

Section: Section name

Subjects: DV, M-II, PP, BEEE, FL, FRMS

Additional Data: Grading details, total marks, etc.

Observations:

t-tests: t-tests were performed to compare the mean marks between two subjects or sections and to check various parameters.
The differences were statistically significant.

χ² (Chi-square) tests: χ² tests were conducted to assess the independence between categorical variables such as marks.
Findings:

Some subjects had worse performance in DV subject.

Subjects with p-value < 0.05 indicated a statistically significant association

Dataset: Titanic.csv Description: Basic Information: Rows: 891 (Passengers)

Columns: 8 (Features)

Missing values: 0 (No missing values in the dataset)

Column Description: Survived

Pclass

Name

Sex

Age

Siblings/Spouses Aboard

Parents/Children Aboard

Fare (Fare paid by passengers) Observations: Passengers' Distribution: Gender Distribution: The dataset has more male passengers than females.

Male ~ 75%, Female ~ 25% (approx).

Age Distribution: Average passenger age is 30-31 years.

Majority of passengers are aged between 20 to 40.

Survival Insights: 38.6% of passengers survived, while 61.4% did not.

Survival by Gender: Females had a highly significant higher survival rate (74%) compared to males (~19%).

Building Logistic Regression on Titanic Dataset Dataset: Titanic.csv

Dataset Description: Basic Description: Rows: 877 (Passengers)

Columns: 8 features

Missing Values: 0 (No missing values in the dataset)

Column Description: Survived → (1 = Survived, 0 = Did not survive)

Pclass → Passenger class (1,2,3)

Name → Full name of the passenger

Sex → Gender of passengers (M/F)

Age → Age of passengers (in years)

Siblings/Spouse Aboard

Parents/Children Aboard

Fare

Observations: This week contains data preprocessing steps such as:

Dropping irrelevant columns

Handling missing values by filling missing age with mean

One-hot encoding used for the Cabin column using pd.get_dummies()

Model used: Logistic Regression

Model uses Logistic Regression from sklearn.linear_model

Data Analysis on Car Price Dataset Dataset: CarPrice.csv

Description: The Car Price dataset contains 10,000 records with 10 attributes detailing used cars and their resale prices. It includes brand, model, years (1990-2023), engine size (1.0L - 5.0L), fuel type, transmission mileage, doors, owner count, and price (1000-1,00,000).

The discussion is based on price prediction models and insights such as depreciation patterns. The dataset is ideal for studying the buying and selling trends of vehicles.

Observations: Price frequency by year

Price vs Year scatter plot and violin plot reveal that newer cars (post-2015) have significantly higher prices, while older models tend to be cheaper.

The median price steadily increases for recent cars, reflecting higher market value.

Mileage and price relationship

Mileage vs Price scatter plot highlights a clear trend:

Cars with higher mileage tend to have lower prices, reflecting wear and depreciation.

Linear Regression model on Car Price dataset

Dataset: 'CarPrices.csv'

Description: The Car Price dataset contains 1000 records with 10 attributes detailing used cars and their resale prices. It includes brand, model, years (2000-2023), engine size (1.0L - 5.0L), fuel type, transmission, mileage, doors, owner count, and price.

The dataset is ideal for price prediction models and market analysis, revealing trends such as depreciation patterns and the rising popularity of hybrid and electric vehicles.

Columns: Brand

Model

Years

Engine size

Fuel Type

Transmission

Mileage

Doors

Owner count

Price

Data Analysis on Car Price Dataset Dataset: CarPrice.csv

Description: The car price dataset contains 10,000 records with 10 attributes detailing used cars and their resale prices. It includes brand, model, years (2000-2023), engine size (1.0L - 5.0L), fuel type, transmission, mileage, doors, owner count, and price.

The dataset is ideal for price prediction models and makes analysis revealing trends such as depreciation patterns and the rising popularity of hybrid and electric vehicles.
