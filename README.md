# LOAN-ELIGIBILITY-PREDICTICTION

# Problem Statement:
Dream Housing Finance company deals in all home loans. They have a presence across all urban, semi-urban, and rural areas. Customer-first applies for a home loan after that company validates the customer eligibility for a loan.

The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling the online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others. To automate this process, they have given a problem to identify the customer's segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

In loan prediction involves the lender looking at various background information about the applicant and deciding whether the bank should grant for loan or not.
Here, I apply logistic regression for this prediction and get the accuuracy score is 80.94%

COME TO THE INSIGHT: Those who belongs to urbanized area and Educated male married applicant has higher approval. So, according to the prediction bank decided whose applicant grant or not

### df_ID--------------> Unique Loan ID.
- ### Gender --------------> Male/ Female
- ### Married --------------> Applicant married (Y/N)
- ### Dependents ------------> Number of dependents
- ### Education -------------> Applicant Education (Graduate/ Under Graduate)
- ### Self_Employed ---------> Self-employed (Y/N)
- ### ApplicantIncome -------> Applicant income
- ### CoapplicantIncome -----> Coapplicant income
- ### LoanAmount -----------> Loan amount in thousands
- ### Loan_Amount_Term ------> Term of a loan in months
- ### Credit_History --------> Credit history meets guidelines
- ### Property_Area ---------> Urban/ Semi-Urban/ Rural
- ### Loan_Status -----------> Loan approved (Y/N)
