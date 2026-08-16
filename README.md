# Job Posting Summarizer with GenAI

This program helps prospective tech employees identify which programming languages, infrastructure, and/or software to master by summarizing hundreds of job postings using the help of GenAI.

This program requires

**Note**: always check the job search website policy on web scraping before performing any web scraping. The code in this project is for educational purposes only.

## Background

Getting into technology positions could be a daunting process with the everchanging landscape and numerous programs or languages to be mastered. You could spend half a year learning a new tool or language only to find out that it is now obsolete. 

To help job seekers identify which skills to focus on, this program looks at tech related job postings on job search platforms like SEEK, count programs or languages, and rank by occurrence.

## Results

For the sample program, I used the program to summarize data analyst jobs in New Zealand.

The top required skills are:
- Languages: SQL, Python
- Program: PowerBI, Tableau
- Microsoft Office: Excel
- Cloud: Azure, Snowflake, AWS
![](./spec/data_analyst_top_skills.jpg)

As for education requirements, most jobs still require a Bachelor's degree in Computer Science, followed by Information Systems then Statistics.
![](./spec/data_analyst_top_education_level.jpg)
![](./spec/data_analyst_top_education_background.jpg)