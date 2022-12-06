__Notes__
- rows_number --> 614
- columns -->  13
- data is small so i will fill null values  

    __Nulls__
    - Gender
    - Married
    - Dependents
    - Self_Employed
    - LoanAmount
    - Loan_Amount_Term
    - Credit_History

    __Outliers__
    - ApplicantIncome
        * left skewed

    - LoanAmount
        * left skewed --> 2.49

    __New Features__

    - TotalIncome by
        - ApplicantIncome
        - CoapplicantIncome
        
    __Transformation__
    
    - TotalIncome Transformed with log
    - LoanAmount Transformed with log
- Dependents column converted to integers
- data not palanced 
