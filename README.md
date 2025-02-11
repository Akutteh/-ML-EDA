# -ML-EDA
GenZ Dating App Dataset

Overview

This dataset contains information on how GenZ users engage with dating apps. It includes demographic details, app preferences, usage behavior, and user sentiments.

Data Summary

Total Rows: 500

Total Columns: 16

Missing Values: Primary_App has some missing values

Data Types:

Numeric: User_ID, Age, Satisfaction

Categorical: Gender, Location, Education, etc.

Columns & Descriptions

Column Name

Data Type

Description

User_ID

int

Unique identifier for each user

Age

int

Age of the user

Gender

object

Gender identity of the user

Location

object

User's city of residence

Education

object

Highest level of education attained

Occupation

object

User's employment status or role

Primary_App

object

Main dating app used by the user

Secondary_Apps

object

Other dating apps used

Usage_Frequency

object

How often the user engages with dating apps

Daily_Usage_Time

object

Average daily time spent on dating apps

Reason_for_Using

object

The user's primary reason for using dating apps

Satisfaction

int

User satisfaction rating (scale of 1-5)

Challenges

object

Common issues faced by the user

Desired_Features

object

Features users wish to see in dating apps

Preferred_Communication

object

Preferred communication method

Partner_Priorities

object

What users prioritize in a potential partner

Data Cleaning Steps

Missing Values:

Primary_App: Fill missing values with "Unknown"

Standardization:

Normalize values for Usage_Frequency (e.g., "Daily" vs. "Everyday")

Ensure consistency in categorical values (e.g., "Male" vs. "male")

Outlier Detection:

Use IQR method for Age and Satisfaction columns
Machine Learning Class
