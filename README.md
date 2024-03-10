# Loan-Management-System

The module to be developed is a loan management system for any type loan.
The loan is to be considered as a high-level module. The objective of the program is to provide the details of the loan once the loan is disbursed. It has to provide all the details with the following components.

1. Principal amount
2. Loan creation date
3. No of EMI’s
4. Each EMI should have the following
a. Principal EMI amount
b. Interest EMI amount
c. Total EMI amount
d. EMI date (can consider a period 30 days for every EMI since the creation date)
e. Principal amount remaining from the main loan account.
5. Total Payable amount


The input should be a command line executable, no graphical UI needed. The input can be provided as command line parameters or a JSON file based on your convenience. The inputs which needs to be passed is the loan amount and loan tenure(No of EMI’s). The program should perform all computations and give an output of all the components provided above.
Note : The interest for the loan can be a static value of 12% for one year. A difference of +/- 10 Rs is exempted from calculation.




Sample Input/output:
Input : 1,000 , 12 months

Output :
1. Loan creation date : 10th April 2020
2. Principal Amount : 1,000
3. No Of EMI’s : 12
4. Total payable amount : 1,000 (Principal) + 120 (Interest for 12 months) = 1,120

5. EMI Details :

a. EMI No : 1, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th May 2020, Principal remaining : 1026.67

b. EMI No : 2, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th June 2020, Principal remaining : 933.34

c. EMI No : 3, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th July 2020, Principal remaining : 840.01

d. EMI No : 4, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th Aug 2020, Principal remaining : 746.68

e. EMI No : 5, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th Sept 2020, Principal remaining : 653.35

f. EMI No : 6, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th Oct 2020, Principal remaining : 560.02

g. EMI No : 7, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th Nov 2020, Principal remaining : 466.69

h. EMI No : 8, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th Dec 2020, Principal remaining : 373.36

i. EMI No : 9, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th Jan 2021, Principal remaining : 280.03

j. EMI No : 10, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th Feb 2021, Principal remaining : 186.70

k. EMI No : 11, Principal EMI : 83.33, Interest EMI = 10, Total EMI=
93.33, EMI Date : 10th March 2021, Principal remaining: 93.37

l. EMI No : 12, Principal EMI : 83.33, Interest EMI = 10, Total EMI =
93.33, EMI Date : 10th April 2021, Principal remaining : ~0
