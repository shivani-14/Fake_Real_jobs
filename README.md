# Fake_Real_jobs
fake or real jobs predictions

## What Exactly is Real/Fake Job Predictions is about?
   There are many job postings out there. Where many people are desperate in search of jobs. Many of the scammers take advantage of the situation and target people who are looking out for jobs. These scammers try to collect all the personal valuable information like address , phone number , birth date and etc, and might ask money in return to get a job. 
   The Dataset is provided by Kaggle. This dataset has few attributes which tends to job postings. It is been divided in such a way that if that particular job post is real or fake. There are 18 k job descriptions where 800 are fake jobs. Our main goal is to find out which is fraudulent.

## The dataset which was provided is in csv format with the following columns:
1. job_id: The unique job_id's for each job postings.
2. title: title of the job.
3. location: geographical location of the job.
4. department: Corporate department (eg: sales).
5. salary_range: salary range of that particular job.
6. company_profile: a brief company description.
7. description: the detail description of the job.
8. requirements: requirements related to job openings.
9. benefits: enlisted offered benefits by the employer.
10. telecommuting: True for telecommuting positions.
11. Has_company_logo: True if the company logo is present.
12. Has_questions: True if screening questions are present.
13. Employment_type: Full-time, Part-time, Contract, etc.
14. Required_experience: Executive, Entry-level, Intern, etc.
15. Required_education: Doctorate, Master’s degree, Bachelor’s, etc.
16. Industry: Automotive, IT, Health care, Real estate, etc.
17. Function: Consulting, Engineering, Research, Sales, etc.
18. Fraudulent (Target Variable): 1 if fake posting else 0.

## Project Goal:->
The main goal is to create a classifier that helps to identify which is real or fake.

## Lets get started....

## Data extraction:
lets extract the dataset provided by kaggle: https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction
-Download the dataset using opendatasets .
-start importing the basic packages needed
-try to store the data with the help of pd.read_csv 
