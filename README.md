# neural-network-challenge-1
Creating a model to predict student loan repayment, to see the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. 
The business team has given you a CSV file that contains information about previous student loan recipients. Will use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as their credit ranking.

# Discuss creating a recommendation system for student loans

**1. Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.**

Age, Education Level, Income, Employement Status, Credit Score, Debt-to-Income Ratio, are the primary data to build a recommendation system. Said features give insighr to a students financial capacity and helps build a risk profile. This help recommend suitable loan and interests rates.
  
**2. Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.**

Conent-based filtering would be the most appropriate approach. Content-based filtering relies on matching the characteristices of loan products with students profiles. By anaylzing student demo, financial health, academic detials and loan characteristics, the system can recommend loans best suited for specific needs and circumstances.

**3. Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.**

Data Privacy and security is the first conern. Student finicial and academic data is very sensitive. Data privacy and security is key to avoiding potenial misuse.

Bias and fairness would be the second challenge. ML models can perpetuate and amplify biases in leanding practices. This can obviously lead to unfair and discriminatory recommendations for certain groups.
