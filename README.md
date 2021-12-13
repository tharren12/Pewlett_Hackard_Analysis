# Pewlett Hackard Analysis

## Overview of Project

This project involved two primary assignments. The first assignment is to determine the number of retiring employees per job title, with retiring being defined as employees who were born between January 1, 1952 and December 31, 1955. The second assignment is to identify employees who are eligible to participate in a mentorship program, with eligibility based on whether the employee was born between January 1, 1965 and December 31, 1965.

## Resources

* Data Source: Various .csv Employee and HR files

* Software: pgAdmin 4 v6.1

## Pewlett Hackard Analysis Results


### Number of Close to Retiring Employees by Title


![image](https://user-images.githubusercontent.com/92001105/145740497-d3fb58c5-df08-4a8d-9a04-8c6ba088fe2e.png)


* Overall there are 300K  employees with 90K or 30% at retirement age
* The job titles with the most number of employees nearing retirement are Senior Engineers (29K) and Senior Staff (28K)
* Most job titles have close to 30% of employees nearing retirement, with only Managers being lower at 22%, however small sample size


### Mentorship Eligible Employees


![image](https://user-images.githubusercontent.com/92001105/145740588-31c1ddc4-100f-4fb2-8b7f-ae0a1d5b1a6e.png)


* Very concerning that the mentorship eligible population only covers 1.7% of the number of employees close to retiring
* The highest percentage of mentorship eligible employees of retiring age are Assistant Engineers with 3.4% and the lowest number is Managers with no employees eligible for the mentorship program


## Pewlett Hackard Summary

Through the analysis it was determined that 30% of employees are close to retirement, which will be a very significant impact to the business over the coming years. The business will to identify additional employees for upward mobility or need to bring a large number of external new hires to address this labour shortage.

Out of the 90K retiring employees there are only 1.5K that have been identified as Mentorship Eligible. This criteria needs to be expanded and also potentially beyond age criteria and look to mentor currently Assistant Engineers to become Senior Engineers. 

It was identified through an additonal query of the date range if expanding the criteria for mentorship eligibility and including employees born in 1964 or 1963 would include 18K for each additional year and would therefore account for closer to 42% of employees that could be retiring shortly.

Another way to refine target list is to deprioritize employees that have only been hired recently out of the employees nearing retirement based on birth date only. Potentially a number of these employees will not actually be retiring if they have only recently been hired. As detailed in the below table there are 11.5% or 8.3K employees that are in the most recent 5 years of hiring and these could be deprioritized in terms of replacing.

![image](https://user-images.githubusercontent.com/92001105/145698190-2c4e57f5-9034-4eb3-83d7-f28abf5bb453.png)


