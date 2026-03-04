# Loan-Default-Analysis
Project 1: Alpha Dreamers Banking - Loan Default Analysis
Student Name: Bonolo Ramolapong
Date Completed: March 4, 2026

Project Description
This project analyzes 252,000 records to find why customers default on loans. I acted as a BI technician to identify high-risk patterns using 15 visualizations and built a Logistic Regression model to help the bank automate their loan approval decisions.

Project Requirements
- Identify factors related to high defaulter rates.
- Provide at least 10 visualizations with business insights.
- Clean and curate data for machine learning.
- Develop and evaluate a Logistic Regression model.

Key Takeaways from my 15 Charts
After making 15 different charts—everything from bar graphs to line plots—one thing really stood out: **stability is everything**. It was the biggest pattern I noticed.

- **Age and Life Stage:** My age histogram and line plots showed that people between 20 and 50 are much riskier, while older applicants are safer. Single people also default more often than married ones.
- **The Housing Factor:** This was the biggest "aha!" moment. Renters default about 13–15% of the time, while homeowners are only at 5%. Not owning a car was another major red flag. 
- **Work History:** Risk drops sharply once someone hits 8–10 years of experience. The longer someone stays in their career, the more reliable they become.

## Data Cleaning and Model Evaluation
I scaled the numbers (like Income and Age) to make them all the same size so the model could focus on patterns instead of just the size of the numbers. 

Model Evaluation, I checked my results using a confusion matrix. Even though my accuracy was about 88%, I focused mostly on **recall**. It is much more important for a bank to catch a potential defaulter than to be perfectly accurate about every safe person.

