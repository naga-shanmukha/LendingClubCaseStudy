# Lending Club Case Study
> Aim of this case study is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
<!--* [Acknowledgements](#acknowledgements)-->

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem Statement
  - Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.
  - Aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

- Business Objectives
  - Use EDA to understand how consumer attributes and loan attributes influence the tendency of default
  - Aim of this case study is to use EDA to identify such applicants.
  - Understand the driving factors behind loan default i.e. the variables which are strong indicators of default
- Dataset being used for this case study
[loan.zip](https://github.com/Soumojit28/LendingClubCaseStudy/files/12536966/loan.zip)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Key observations from our analysis
- Grade & Sub Grade - As the loan applicant's Grade / sub grade increase from A to G, we see that proportion of charged off data is increasing.
- Loan Term - More charged off data is having loan term as 60 months
- Interest Rate - As the interest rate increases, the tendency of charged off is also increasing.
- Annual Income - Majority of loan write offs are for loan applicants having annual income between 35000 and 50000
- Loan Amount increases as the annual income increases.
- We see more density in charged off data for the loan amounts 19,000 to 24, 000 across three different annual income buckets and that is for grades 'E', 'F' and 'G'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!--
## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).
-->

## Contact
Created by [@Soumojit28] & [@naga-shanmukha]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
