# OA-Transitions-Project
This repository is to showcase my analysis into the effect of Open Access transitions on journal performance. All journal names have been redacted and numerical data has been scrambled to protect company confidentiality.

#Business Context
The aim of this project was to investigate how transitioning to Open Access affected journal performance, as there were some anecdotal theories about this but little supporting evidence or insight into the scale of the change and the journals most affected. To address this, I collected data on publications, submissions and downloads (usage) of journals that had recently 'flipped' to Open Access. I then used Python to transform this data to show the publications, submissions and downloads per month and plotted this as 'months since flip' rather than calendar months, so that journals that flipped at different times could be compared. I also fitted a linear regression model to demonstrate the overall impact of 'flipping' on journal performance and generate expected values for submissions, publications and usage for each month before/after the flip. The transformed data was then loaded into Power BI to create an interactive dashboard and allow stakeholders to filter to specific journals of interest, subject areas or year of flip. I also added insightful summary statistics such as the number of journals with increased submissions/publications/usage following the flip and the number of journals with reduced submissions/publications/usage.

#Business Impact
This project significantly improved understanding of the impact of flipping to Open Access on journal submissions, publications and usage. The dashboard is updated on a monthly basis and is used by 20+ cross-departmental stakeholders to monitor journal performance against expected levels and inform decisions on intervention strategies and the rate of journal transitions.

#Tools used
- SAP
- Excel
- Power BI desktop (DAX, PowerQuery, custom measures)
- Python (Pandas, NumPy, statsmodels, matplotlib, scikit-learn, seaborn

#Contents
'OA Transitions Home Page' - A screenshot of the Power BI report homepage
'OA Transitions Submissions Example' - A screenshot of the submissions page of the Power BI report (sample data)
