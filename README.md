# LoanDefaultPrediction
LendingClub used to be the biggest peer to peer lending platform until 2020, when they changed their business focus. During its operation, LendingClub would establish a platform for borrowers and investors where borrowers were allowed to create loan requests on its website. They were also required to provide their information like credit score, credit history, desired loan amount and the debt-to-income ratio. Based on the data, LendingClub would decide if the loan request would be accepted and what the interest rate would be. Allowable loan range was between $1,000–40,000 and the return period was 3 or 5 years. Investors would make money from interest rates which were varied from 6.03% to 26.06%. LendingClub would make money from charging an origination fee to its borrowers and a service fee to its investors. The interest rates that LendingCub was offering were better for borrowers and lenders than most of banks and therefore, it was highly received.

The data is from Kaggle website and can be found here: All Lending Club loan data | Kaggle The data is in two files and originate from Lending Club and include information of rejected and accepted loan applications from 2007 to 2018. The accepted file has more than 2 million rows and 151 columns. It includes information about the applicant such as credit score, income and employment, as well as data about the loan, its amount and terms.

We are looking for a model to predict default of a loan based on the characteristics at the time of application. Therefore, any columns that was not established prior to the decision was dropped. The focus is on the single applicants, therefore, join applications were also dropped.

A heat map of the numerical features show that 'fico_range_low' and 'fico_range_high' were highly correlated, as well as, 'installment' and 'funded amount', which is expected.

![image](https://user-images.githubusercontent.com/85642689/149711246-8b78f885-c713-4fa5-8cff-2569db374e27.png)


