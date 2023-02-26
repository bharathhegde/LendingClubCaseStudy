# Lending Club Case Study

The problem is related to a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.

The problem statement is to come up with the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.  The driving factors should be such that they can be utilised during the process loan grant decision itself.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Overall Approach](#overall-approach)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

This is a case study taken as part of Executive PG Programme in Machine Learning & AI - January 2023, offered by IIIT - Bangalore in association with Upgrad.

Name: Bharat Hegde
Email: bharathhegde2005@gmail.com
26th Feb 2023

Bharat Hegde.ipynb: Contains the Python code used for analysis
Lending Club Case Study.pdf : contains the summary of the analysis and conclusions and recommendations

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Overall Approach

The company has shared a data file which contains the performance data of the loans in past many years. As part of this case study:

•	Understand the structure of the data
•	Clean the data
•	Analyse and Visualise the data
•	Conclusion: Suggest driving factors behind the loan default to the company

The python language is used for all above steps. The libraries used as numpy, panda, matplotlib and seaborn


## Conclusions

Summarizing Recommendations to the  company 

1.	Grade A (6% defaulters) and B ( 11% defaulters) are relatively safer. Other grades: C ( 16.6% defaulters ), D( 21.0% defaulters), E( 25.1% defaulters), F( 30% defaulters), G( 31.96% defaulters) are risky, since the defaulting % is comparatively higher. – This is the major deciding factor
2.	The loan Term = 36 months is much safer (11% defaulters) compared to term = 60 months ( 22.6% defaulters)
3.	As interest rate increases (above 13.8% )probability of borrowers repaying decreases. 
4.	As number of inquiries in last 6 months increases, the chances of default also decreases. As per the data, if number of inquiries is more than 1, then chances of repaying decreases.
5.	If somebody mentions purpose of loan as Small Business, then there is 26% chance of defaulting. Other high risk categories are: Educational, House, Medical, Renewable Energy ( with probability ~= 15% )
6.	Also during the tenure of the loan, As the Revolving Utilisation of the bank balance increases by more than 50%, the chances of default also increases. When company gets indications around, company needs to take suitable measures to avoid the default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 
- numpy
- panda
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@bharathhegde] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->