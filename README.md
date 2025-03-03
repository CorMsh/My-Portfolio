# My Portfolio 🗃️

Dear Viewer,

Thank you for taking the time to look through my portfolio. In it, I have put just a handful of projects that I have worked on in my time as a data analyst. It show cases a mixture of my advanced capabilities in SQL, Python and even a Power BI dashboard. Each of these projects have also delivered great insights to stakeholders. Below is a list of each of the projects that feature in this portfolio:

## 1. Crave Basket Analysis:

With some of the stores having smart fitting room technology, there is a need to understand which items are frequently being taken into the fitting rooms together. Using unsupervised machine learning apriori and associaten rules pacakages from the mlxtend.frequent patterns library, metrics such as confidence and leverage between different departments for different stores was visualised on a heat map to show the levels of association between different departments. The outcome of this analysis was an improved understanding of which items from which departments customers are trying on together and from this, a change in merchandising layout in stores. 

## 2. Manchester Trafford FR Occupancy:

This store is one of the busiest stores owned by the company and frequently has the highest amount trade. As a result of its popularity, the smart fitting rooms are sometimes fully occupied during certain hours and certain times of the week. As a result of all of this congestion, customers are left dissatisfied by the long queues to use the fitting rooms. During these peak times, staff are stressed by the increase in customer fitting room requests. The two factors lead to a negative customer experience and loss in staff morale. The Fitting room (FR) Occupancy was used to justify the need for more fitting rooms in this store and also to identify the peak hours so that staff could be better managed. The occupancy was completed using colour coded heat maps which allowed stakeholders to identify peak occupancy periods. This piece of work successfully led to the installation of more fitting rooms and better management of staff. 

## 3. Crave Dashboard:

This is a power BI dashboard which gives in-depth insight into smart fitting room metrics such as capture rate (% of customers using the fitting rooms) and % of fittng room visits leading to a sale. It is dynamic, intuitive and allows users to analyse the data in a number of different ways thanks to the use of slicers. The neat layout makes it less overwhelming for users to use and its user-friendly layout encourages interaction. This includes the use of animated visualisations as well as static visualisations. 

## 4. Fitting Room Metrics:

The finance department asked for a report for stores with smart fitting room technology. They want to know whether the installation of smart fitting room technology was a worthwhile investment. They wanted to do this by using 4 metrics:
- Capture Rate
- Fitting room visits --> sales
- Fitting room requests --> sales
- % Missed Requests
From these metrics, they wanted to compare the performance of each store in the most recent period to their YTD performance. YTD was a rolling 13 period window. I ensured that this code automatically determined the start and end of the timeframe by using surrogate keys and the current_date() function in order to minimise the reliance on someone running the report to change the week and period numbers in several parts of the report.

## 5. Fitting Room Occupancy:

This is the code that was used to perform the Fitting room occupancy analysis mentioned above.

## 6. Stockloss reporting:

Each period, stakeholders want to know how stores are performing with regards to stockloss. Each period, I generate a power BI dashboard which is built from this SQL. The SQL requires no need to manually change the time frame due to the CTE used which automatically gives the necessary weeks needed for the report which compared performance this year vs last year. A number of store attributes are also used in the output statements to allow users to analyse performance by different regions, store types and whether they are special measure stores or not. 

## 7. Stockloss Model 2022

Using Machine learning, I built a multivariate machine learning model which predicts stockloss for all of the stores for the following year. Numerous factors were accounted for in the model, including local crime rates, adult literacy and number of floors that a store has. This was then used to set targets for stores. 
