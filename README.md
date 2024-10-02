# PortfolioAssignment5.1 : Will the Customer Accept the Coupon?
PortfolioAssignment5.1 by Ravi Duvvuri

**REPOSITORY DETAILS:**

**1.Jupyter Notebook**  
  https://github.com/ravikduvvuri/PortfolioAssignment5.1

  Assignment5.1__Ravi_Duvvuri .ipynb
  
**2.Dataset**  
  coupons.csv

**EXECUTION DETAILS**

**STEP1: Analysis of the dataset**

  A. Checked datasets using info(), Describe(), head() etc.

  B. Checked for duplicate data

    Duplicate data identified:

  ![image](https://github.com/user-attachments/assets/7bcf9d6d-ef1c-4ce9-80bd-f768e384a91a)


  C. Checked for missing values

    Missing values identified

![image](https://github.com/user-attachments/assets/f5e8e215-b539-4bbc-a5ad-66a41dd84478)


  D. Analyzed how to fill-in missing values

  E. Finalized what data to drop

**STEP2: CLEAN UP of DATA**

1. Drop 'Car' column data since greater than 99% is missing and is not useful for data analysis

2. Drop duplicated data of 74 rows as it is not going to impact the overall data of 12684 rows

3. Fill-in missing values for other columns using appropriate method (ex. mode)

**STEP3: OBSERVATIONS**

  1.Carry out & Takeaway coupons were accepted **more** when presented
  
  2.Similarly cheaper restaurant coupons (<20) were accepted **more** when presented
  
  3.**Younger Age groups (<30)** tend to accept coupons when presented compared to other ages 
     groups
  
  4.When compared with **widowed & divorced** people, **single & married** people are lot   
    willing to accept coupons

![image](https://github.com/user-attachments/assets/9f8ca749-60cf-450a-83af-0af527e1a423)


![image](https://github.com/user-attachments/assets/1556f7cd-3fdc-495b-b439-c7dc82e4276c)


![image](https://github.com/user-attachments/assets/72496114-0a22-4c51-b6db-aa8c29c6ced6)

**STEP4: BAR COUPON INVESTIGATION and FINDINGS**

Bar Coupons acceptance percentage: **41%**

![image](https://github.com/user-attachments/assets/b1e9a77d-7b9b-42fd-b229-b2a34d928e1c)

**FINDINGS:**

  1. Only 41 % of Bar coupons were accepted by the drivers

  2. The coupon acceptance rate of drivers who go to bar more than 3 times a month is very low 
     at 7.6%

  3. Acceptance rate of drivers who go to bar more than once a month and under the age of 30 is 
     moderately high at 12.36%

  4. Even though some drivers go to cheap restaurants more than 4 times a month they did not 
     accept more bar coupons

**Based on results, the age group under 30 and those who go to bar fewer times a month are more willing to accept bar coupons when presented.**

**STEP5: INDEPENDENT INVESTIGATION 'COFFEE HOUSE COUPON'**

![image](https://github.com/user-attachments/assets/5fda6bc1-4994-4ab3-a507-b618163e9753)


![image](https://github.com/user-attachments/assets/2c116279-8d31-448f-859d-33e93fd2cdcc)


![image](https://github.com/user-attachments/assets/90952492-768e-42f4-a8dc-e6fb0e2a8a32)

**Coffee House Coupon Findings:**
1. Younger generation under 30 years are accepting coffee house coupons more when compared to other groups

2. Coffee House Coupons acceptance is same at 7 am as well as at 2pm and 6pm. Seems like consumption is higher in the evenings.

3. Compared to Divorced and Widowed people, other groups Coffee House coupon acceptance is very high (<~2.5% versus ~20%)

**NEXT STEPS**

A. Analyze other coupons data and see if any patterns are same across all coupon types

B. Recommend offers to those groups with appropriate coupons and timing
