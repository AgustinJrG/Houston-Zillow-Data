# Houston-Zillow-Data

## Introduction
The purpose of this Analysis Project is to find out the cost of living for each Zip Code in the city of Houston, Texas. This is useful for an individual who is interested in knowing 
about the Cost of Living in Houston. The information gathered in this project is useful for someone who wants to buy a house in Houston, whether they currently live in Houston or 
may want to move to Houston. The project shows how different Zip Codes have different cost of living.
## Data Selection
The data used for this Analysis Project is gathered from House Listing Data from Zillow. According to Zillow, Houston has a total of 10,500 House Listings available. Due to Zillow’s 
anti-scraping methods not all 10,500 House Listings are available. Only 800 House Listings are used in this project. From each of the available listing the following was gathered, 
Listing URL, Zip Code, Listing Price, Square Footage and Bedrooms
## Method Selection
House Listing Data was gathered using Scrapeak’s Zillow API. As stated earlier, not all listings available was gathered. A Python automated program runs through each listing. It 
gathers the data desired and stores it into a Microsoft Excel Workbook. Within the workbook listings are organized into different sheets depending on the listing’s Zip Code. Once 
all listings are gathered and organized another Python Automated program will go through and calculate each sheet’s Listing Price Average. It then stores each listing price average 
along with the sheet’s name, which is the Zip Code, and stores it into another Excel Workbook dedicated to only Zip Codes and Listing Price Averages. The program runs through the 
spreadsheet and uses the Listing Price Average to calculate Mortgages and the Salaries recommended to have.


## Mortgage Algorithm

    M=P (r(1+r)^n)/((1+r)^n-1)

		M = Total Monthly Mortgage Payment
		
		P = Principal Loan Amount

		r = Monthly Interest Rate

		n = Number of Payments over loan’s term

## Result Selection

### Highest:
Zip Code: 77019
House Value: $7,278,993
Mortgage: $49,508
Monthly Salary: $141,451
Yearly Salary: $ 1,697,412

### Lowest:
Zip Code: 77013
House Value: $75,000
Mortgage: $510
Monthly Salary: $ 1,457
Yearly Salary: $ 17,484

### Average
Zip Code: 77089
House Value: $297,923
Mortgage: $2,026
Monthly Salary: $5,789
Yearly Salary: $69,468

## Map

<img width="468" alt="image" src="https://github.com/user-attachments/assets/5e606d76-2706-43c3-b8f3-d71f5010b7d4">

## Discussion
Limitations first appear when scraping data from Zillow. According to Zillow, Houston has around 10,500 House Listings available to scrape data. Zillow’s anti-scraping methods made
it possible to only scrape 800 of the 10,500 possible listings, which is about 7% of the total listings available. Due to only acquiring 7% of the total listings there is a 
disproportionate number of listings in for each Zip Code that was recorded. Some Zip Codes may only have one listing. Some may have 10 listings and some Zip Codes did not have a 
single listing recorded for them.





