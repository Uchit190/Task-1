Task 1 : Data Cleaning and Preprocessing
1.	Objective: To clean and prepare the Netflix movies dataset by handling missing values
And remove deplicates and standardizing text entries , and correcting data formats


2.	Tools used:  
•	Python(pandas)
•	Vs code(jupyter notebook )
•	Excel(optional)

3.	Steps:
  i.	Handled Missing Values:
•	Director: filled with ‘Unknown’
•	Cast: filled with ‘not available’
•	Country: filled with ‘Unknown’
•	Rating: filled with ‘not rated’
•	Data_added: convert to datetime format
ii.	Removed Duplicates:
•	Use drop_duplicates() to remove duplicate rows

iii.	Standardized Text:
•	Convert all the text fields to lowercase
•	Remove leading whitespaces
•	Cleaned inconsistent entries like country name 

iv.	Fixed data types:
•	Convert date_added to datetime
•	Checked and fixed other data types where necessary

4.	Deliverables:
•	Cleaned dataset: Netflix_dataset.csv,Book1
•	Code file : task-1.ipynb
•	Report: This word file(README)

5.	Learning Outcome:                                                 
•	Practical experience in handiling missing values and duplicates
•	Gain knowledge in Cleaning raw datasets using Pandas 

