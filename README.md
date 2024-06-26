# Lending Club Case Study
Lending Club, a marketplace for consumer finance focusing on urban customers, is grappling with a critical issue in managing its loan approval process. When assessing loan applications, the company must make prudent decisions to minimize financial losses, particularly from loans extended to applicants deemed "risky."

These financial losses, known as credit losses, occur when borrowers fail to repay their loans or default. Simply put, borrowers classified as "charged-off" contribute significantly to the company's losses.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
This case study aims to accomplish this objective by conducting exploratory data analysis (EDA) using the dataset provided.The company seeks to identify the key factors (or driver variables) influencing loan defaults—those variables that strongly indicate the likelihood of default. This understanding will enable the company to enhance its portfolio management and risk assessment strategies.

The main goal here is to help Lending Club reduce credit losses. This challenge arises from two possible scenarios:

It's crucial to identify applicants likely to repay their loans because they generate profits for the company through interest payments. Rejecting such applicants would mean losing potential business.

Conversely, approving loans for applicants unlikely to repay and at risk of default can result in substantial financial losses for the company.

## Conclusions
1.Risk Assessment for Grades B, C, and D: Since loan applicants in Grades B, C, and D account for the majority of "Charged Off" loans, stricter risk assessment and underwriting criteria should be implemented for these grades.

2.Subgrades B3, B4, and B5: Special attention should be given to applicants with Subgrades B3, B4, and B5 due to their higher likelihood of loan default. Consider implementing additional risk mitigation measures or adjusting loan amounts accordingly.

3.Term Length: Applicants choosing 60-month loans show higher default rates. Evaluate the risk associated with longer-term loans and consider limiting maximum term lengths or adjusting interest rates accordingly.

4.Experience and Default Probability: Applicants with over ten years of experience are more likely to default, suggesting experience alone may not reliably indicate creditworthiness. Adopt a more comprehensive credit scoring system that considers additional risk factors.

5.Positive Growth Trend: The consistent rise in loan applicants from 2007 to 2011 signals market growth. Capitalize on this trend by maintaining competitiveness while ensuring robust risk management practices.

6.Seasonal Trends: December and Q4 see peak loan applications, likely due to the holiday season. Prepare for increased demand during these periods to ensure efficient processing and meet customer needs.

7.Debt Consolidation Risk: Debt consolidation loans have high default rates despite their popularity. Carefully assess applicants seeking these loans and consider adjusting interest rates or providing financial counseling services.

8.Housing Status and Default Risk: Applicants living in rented or mortgaged houses show higher default probabilities. Include housing stability in underwriting to better assess repayment ability.

9.Verification Process: Verified loan applicants exhibit higher default rates than unverified ones. Review the verification process to enhance creditworthiness assessment and consider necessary improvements.

10.Geographic Risk: Applicants from states such as California (CA), Florida (FL), and New York (NY) are more prone to default. Monitor regional risk trends closely and adjust lending strategies or rates accordingly in these areas.

11.High Loan Amounts: Applicants requesting $15,000 or more are at greater risk of default. Conduct thorough assessments for larger loan amounts and potentially cap loans for higher-risk applicants.

12.DTI and Interest Rates: Defaults are linked to high Debt-to-Income (DTI) ratios and interest rates between 13% and 17%. Review interest rate setting processes and adjust rates based on DTI ratios to align with borrowers' repayment capacities.

13.Low Annual Income: Applicants earning less than $40,000 annually have higher default rates. Consider offering financial education resources or setting maximum loan amounts based on income levels to ensure affordability.

These adjustments aim to enhance risk management practices and improve the overall quality of lending decisions based on identified risk factors.

## Technologies Used
- Python - version 3.11.7
- Numpy - version 1.26.4
- Pandas - version 2.1.4
- Seaborn - version 0.13.2
- Matplotlib - version 3.8.0

## Acknowledgements
- This Case Study is from UpGrad


## Contact
Created by [@https://github.com/lavanyap2823] - feel free to contact me!