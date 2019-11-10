# Info Student 

No Matrix : 271395

Name : Siti Norsuhada Binti Ibrahim 


# Introduction 


In this assignment 1, I am going to investigate a car loan then make a JAVA code to discover the monthly repayment that should be made and the amount of principal, interest, and balance of each year and for assignment 2 I going to typing code programming.


# Pseuducode

Start 
	Declare 
	double A=0,B=0,D=0,total_interest,monthly_repayment,principal,interest,balance
	int C=0,years=1
	Input car price
	Output enter the car price
	Loop enter the car price if the car price less than RM30000
	Input down payment 
	Output enter the down payment	
	Loop enter the down payment if the down payment less than equal to zero 
	Input loan period 
	Output enter the loan period
	Loop enter the loan period if the loan period less than five or more than nine 
	Input interest rate 
	Output enter the interest rate
	Loop enter the interest rate if the interest rate less than 0.03 or more than 0.07
	Calculate the total interest = (car price - down payment) * interest rate * loan period
	Calculate the total monthly repayment = ( car price - down payment + total interest ) / (loan period * 12)
	Output monthly repayment
	Loop depending on loan period 
		Calculate principal = monthly repayment *12*years 
		Calculate interest = total interest / loan period * years 
		Calculate balance = monthly repayment*12*(loan period-years)
	Output years,principal,interest,balance
		Calculate years ++
End 



