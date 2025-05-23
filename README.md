﻿# MIDS_207_Session6_LiWangZhu
## Group: 
Allen Li / Skylar Wang / Tommy Zhu

## Question:
Which factors contribute most to the approval / denial of a H1B petition once it has been selected from the lottery? 


## Dataset source: 
https://github.com/BloombergGraphics/2024-h1b-immigration-data/blob/main/TRK_13139_FY2024_single_reg.zip


## Basics of feature selection with python
https://www.kaggle.com/code/ar2017/basics-of-feature-selection-with-python

## Baseline Presentation Criteria
**Your slides should include**:
- Title, Authors
    - "From Lottery to Approval: What Really Determines H-1B Visa Outcomes?"
    - By: Allen Li, Skylar Wang, Tommy Zhu

- What is the question you will be working on? Why is it interesting?
    - Which factors contribute most to the approval / denial of a H1B petition once it has been selected from the lottery?
        - By identifying the factors that contribute the most towards H-1B petition outcomes, prospective applicants and employers can better understand the criteria that influence the decision-making process of the U.S. Citizenship and Immigration Services (USCIS). 
        - Understanding these factors may also shed light on potential biases or inconsistencies in the adjudication process. This information can inform policymakers and advocacy groups in their efforts to promote fairness and transparency in the immigration system.

- What is the data you will be using? Include data source, size of dataset, main features to be used. Please also include summary statistics of your data.
    - The data that we will be using comes from the U.S. Citizenship and Immigration Services (USCIS) and covers H-1B visa lottery registrations, selections, and petitions for fiscal years 2021-2024. This data was obtained by Bloomberg News and made public on GitHub after bringing a lawsuit against the Department of Homeland Security under the Freedom of Information Act.
    
    
    - This dataset includes detailed information about each lottery registration, including the applicant's employer, job title, wage, what state they work in, and their education level. 
    
    
    - The H1B data is split into 5 different files by fiscal year. After filtering for applicants that have been selected for the H1B Lottery, the amount of observations in each dataset is as follows: 

        -    TRK_13139_FY2021.csv (FY2021 data on April 2020 lottery) (124368 observations)

        -    TRK_13139_FY2022.csv (FY2022 data on April 2021 lottery) (131896 observations)

        -    TRK_13139_FY2023.csv (FY2023 data on April 2022 lottery) (127563 observations)

        -    TRK_13139_FY2024_single_reg.csv (FY2024 data on April 2023 lottery for single registrations) (103060 observations)
            
        -    TRK_13139_FY2024_multi_reg.csv (FY2024 data on April 2023 lottery for multiple registrations) (85304 observations)

Please refer to the [slides](https://docs.google.com/presentation/d/1I-cwnfegvCYMV55N1OeUwffzS9aUDHaLoC6DuTTLGfc/edit?usp=sharing) for the following bullet points: 

- Main features to be used

- Summary Statistics of the data

- What prediction algorithms do you plan to use? Please describe them in detail?

- How will you evaluate your results? Please describe your chosen performance metrics and/or statistical tests in detail

