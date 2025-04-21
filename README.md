Loaded the dataset using pandas.

Handled missing values:

Identified missing data using  isnull() and .isnull().sum().

Removed all rows with any missing values using .dropna().

Also Handled columns like income and education and marital_status by using .fillna().

Removed duplicate rows using .drop_duplicates().

Standardized text columns:

Converted all text values (e.g., education, marital_status) to lowercase 

Converted dates:

Transformed Dt_Customer to a consistent format: dd-mm-yyyy using pd.to_datetime() and .strftime().

Renamed columns:

Made column headers lowercase and replaced spaces with underscores for consistency.

Fixed data types:

Converted numerical columns like year_birth, kidhome, teenhome, and recency to integers.

Ensured income is stored as a float.

Converted dt_customer to proper datetime format, then formatted as string for consistency.

Saved the cleaned dataset to a new CSV file:

 cleaned_customer_personality_analysis_data.csv

