# no-show-data-investigation-with-python
In this project, I analyzed the data associated with 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. I used pandas, NumPy, Matplotlib, CSV, to go through the data analysis process.

The goal of this project is to investigate a dataset of appoinment records for Brasil public hospitals. The data includes some attributes of patients and state if the patients showed up to appointments. The analysis should be focused on finding trends influencing patients to show or not show up to appointments. Using descriptive statistics the following question should be answered: What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment? Predictive analytics is out of scope of this project.

The original problem description and data set can be found here: https://www.kaggle.com/joniarroba/noshowappointments/home

This project was completed as part of Udacity's Data Analyst Nanodegree certification.

# Details
I have looked into the dataset and managed a few problems like unifying names, removing wrong data, adding new features based on existing data. I have also investigated most of independent variables in the dataset and made a few observations comparing them to each other as well as to the dependent one (no_show). As this was only an exploratory analysis, many potential correlations may remain uncovered. The data should be investigated further with more advanced statistical analysis to potentially reveal new insights and correlations.

For details see analysis documentation Jupyter Notebook or HTML as below
https://github.com/1993Vivi/no-show-data-investigation-with-python/blob/main/Investigate_a_Dataset%20(1).ipynb

# Statistical Analysis Scope
Data Wrangling
Exploratory Data Analysis (EDA)
Examination of central tendency and spread
Data visualizations

# Findings
SMS received or not is not the main factor to affect patient show in the appointment because most of patients show in appointment without receiving SMS
Gender is an important factor affect the no show numbers, male has the highest number of not showing in an appointment.
Jardim camburi, Maria ortiz, Itarare, Resistencia, Centro, Jesus De nazareth, Caratoiza, Tabuazeiro, Bonfim are the top ten neighbours that have highest no show numbers in the dataset, more research need to be done to idenfity the reason, such as traffic issue, average income....
Scholarship is not the key factor to decide patients attendance of appointment
Age is an important factor to affect the number of people not showing in an appointment, people under 60 are more likey not to show in appointment, people age above 60 show in appointment more frequently, we can assume that they have better health awareness.¶
