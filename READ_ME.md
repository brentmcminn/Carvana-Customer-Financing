Carvana provides financing to our customers to help them purchase their Carvana vehicle. Carvana needs to decide what APR's (interest rate) we'd like to offer customers on those loans. The rate we offer affects the profitability of the loans we originate, as well as the likelihood that the customer purchases a vehicle from us.

To help us optimize our rate offering, we run randomized experimentation so that we can measure how things change as we adjust the rates we offer.

Attached is a sample psuedo-realistic data set for the exercises. Each row represents an application ("app"), someone who applied for credit on carvana.com. Here's a quick data dictionary:

Column	Description
app_id	id # of the application
fico	the FICO score of the applicant (700 or 600 in this exercise)
apr_test_group	whether or not the applicant is in the test group (randomized)
apr	the APR that Carvana offers the customer
converted to sale	whether or not the applicant ended up buying a car from Carvana
vehicle margin	the profit that Carvana makes on selling the vehicle
finance margin	the profit that Carvana makes on the loan to the customer (after selling the loan to a counter-party at a fair price)

Here's a series of questions for the exercise. You could either work with the data in excel, or potentially pull it into python/R and knock out the questions with helpful summary statistics and maybe regression models.
1.	Carvana pricing: what’s the current APR pricing strategy for the different FICO buckets? How is the randomized test structured? How do APR's vary by test group?
2.	Customer conversion rate: in general, how many applications is Carvana able to convert to a sale? How does that vary by FICO? Using the APR test group data, how does the APR affect conversion?
3.	Carvana margin: what does Carvana make in margin overall (vehicle + financing), per sale and per application? How does APR affect the finance margin per sale? How does FICO affect the finance margin per sale?
4.	Using your understanding of conversion and total margin (across all applications) and how APR affects the two, if Carvana wants to optimize total margin, do you think Carvana should raise or lower rates on 700 FICO customers? What about 600 FICO customers?
5.	Other than these cut and dry numbers, can you think of other factors Carvana might want to take into account before changing rates? A few several-sentence bullet points are sufficient
