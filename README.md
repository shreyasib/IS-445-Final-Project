# NYC Yellow Taxi Trips 
##### For IS 445: Data Visualization Final Project

##### Libraries: pandas, numpy, matplotlib, seaborn

 
 ## Introduction
The yellow taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data was collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP).

Data source: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
 

## Data Cleaning
1. Treat the nulls
2. Drop unneeded columns
3. Split columns
4. Remove outliers and invalid data
5. Fixing data types




## Data Analysis and Visualizaion
Q1: Which days have the highest taxi usage?

Q2: Which hours of the day typically have a high taxi usage?

Q3: Which is the most popular Vendor?

Q4: Which is the preferred payment method?

Q5: What is the average passenger count in a taxi?

Q6: What is the trend between Fare amount and the distance covered by taxis?

Q7: What is the trend between Tip amount and the distance covered by taxis? Does more distance covered result in more tip?

Q8: Which days cover the most distance by taxis?

Q9: What is the average tip by Time of Day?

Q10: What is the average Fare amount by Time of Day?




## Key Findings
1. Tuesdays and Wednesdays are the busiest days of the week. Taxis are used the least on Sundays.
2. Morning hours see less passengers than hours from 10am to 9pm.
3. Vendor 2(VeriFone Inc.) is preferred by passengers.
4. Payment method 1 (Credit Card) is preferred the most, followed by method 2(Cash).
5. Most taxis have 1 passenger. Taxis have 4-6 passengers on rare occasions.
6. Most amount of distance is mainly covered during weekdays. Saturday and Sundays have the least total distance travelled by taxis.
7. Higher tips are given after midnight especially at 12-1am and 4-6am.
8. Fares are higher after midnight.


## Strategic Recommendations
After the analysis, we share our high-level business recommendations:

1. The final taxi price can automatically include a 5% tip which the customer can choose to opt out of if he or she wants to before paying the fare. For some customers, the 5% tip would not make a difference and would not make an effort to ask to exclude the tip.
2. As weekdays see the least number of passengers, a special rate could be implemented - if the travel distance extends beyond 10kms, then the customers can get a 5% discount. This can possiblity attract more customers on the weekend.
3. Increase transparency and accountability. This could include implementing a system for tracking and responding to passenger feedback, and making more information about the performance and behavior of drivers available to the public.
4. Enhance driver training and support. This could include providing additional training on customer service, safety, and navigation, as well as offering support and resources to help drivers manage the challenges of the job.
5. Improve the quality of vehicles in the fleet. This could include establishing stricter maintenance and safety standards for Yellow taxis, and investing in newer, more fuel-efficient vehicles.


