# Project-Proposal
## Inroduction of the research question
The main research question is to explore the impact of one or more different factors on salaries. For example, is there any relationship between the company size and the salaries of workrs there? Or are there any differences between groups of different job titles or employment types?
## The meaning of this research question
This research can help find the potential differences between each factor and the salary, and also further explore if these relationships are causation relationships. The results can be useful to the employees and the employers, which can guide both sides of them to make decisions about salary payment or acceptance. The results can even serve the government for policy making, which may do good to various aspects such as improving the salary level and wage protection system.
## A preliminary description of data sources
1. The data source is [Data Science Job Salaries](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)
2. The information of the features in this dataset is in the table below:
| column                | Discription                                                                                        |  
|:---------------------:|:--------------------------------------------------------------------------------------------------:|
| work_year             | The year the salary was paid                                                                       |
| experience_level      | The experience level in the job during the year with the following possible values:EN Entry-level / Junior MI Mid-level / Intermediate SE                             Senior-level / Expert EX Executive-level / Director                                              |       
|employment_type        |The type of employement for the role: PT Part-time FT Full-time CT Contract FL Freelance            |
|job_title              |The role worked in during the year                                                                  |
|salary                 |The total gross salary amount paid                                                                  |
|salary_currency        |The currency of the salary paid as an ISO 4217 currency code                                        |
|salaryinusd            |The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com)|
|employee_residence     |Employee's primary country of residence in during the work year as an ISO 3166 country code         |
|remote_ratio           |The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully                                remote (more than 80%)                                                                          |
|company_location       |The country of the employer's main office or contracting branch as an ISO 3166 country code         |
|company_size           |The average number of people that worked for the company during the year: S less than 50 employees (small) M 50 to 250 employees (medium) L                            more than 250 employees (large)                                                                   |
## A scope that explains the intended analysis and resulting visualizations for my project
1.I'll draw scatter plots about each pairs of quantitive factors and the salary. From other qualitive factors like experience level, I'll draw bar charts to see if there are any differences between groups.
2.I'll then use algorithms like variance analysis or regression to check, and the results will be showed graphically.
## A concluding paragraph of the insights I expect to gain from my research
From my research, I hope to first make assumptions and then verify them. I'd like to find if salaries are related the factors like experience level, job title and other things and is the relationship a correlation one or a causation one? For more interesting questions, I'm trying to find the interactive effect between two or more factors and give my comments whether it's reasonable.Then I shall do some literature review and give the practical significance or applications of the results with some examples. Finally, I'll talk about the potential meaning of this research to different groups and make a conclusion. 
