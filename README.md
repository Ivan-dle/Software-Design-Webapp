# Software-Design | Web application
A web app project I built for a Computer Science Software Design Course. 

Front End: The project uses HTML, CSS, a bit of Javascript for the front end design of the web application. 

Back End: For the back end, it is completely coded in PHP for all the logic, actions and funtionalities of the webapp.

Database: 
Apache,
XAAMP,
PHP My Admin,
SQL


Description:
Building a web application to find the rate of selling fuel to a customer based on the following criteria:
1.	Location of the client with respect to the company
2.	Competitors rate
3.	Client rate history 
4.	Gallons requested
5.	Company profit margin (%)
6.	Season rate fluctuation (%)



Architecture:










Explanation:
You are expected to build a web application that will calculate the selling price of the fuel to a client (gas station) depending on the following factors. 
1.	Location of the client:
Your application should ask the client in which state they are located in. If they are in anywhere other than TEXAS. You need to put an additional cost of $0.90/per gallon.
2.	Competitors Rate:
The dataset for the competitor’s rate will be provided to you month wise for the year 2017 and 2018
3.	Client rate History:
This data needs to be generated by you. This will effectively decide the amount of discount that you will be providing to the client. It is left up to your discretion on how you decide the percentage of discount depending upon how many times in the past that the same client has requested fuel.
4.	Gallons Requested:
The number of gallons requested is something that client will be telling you and the total cost will include that component as well.
5.	Company Profit Margin (%):
A profit margin is a number you can decide on how much profit you would want to earn per gallon on this sale.



6.	Season Fluctuation (%):
This is the percentage increase you would like to see in the price of the fuel per gallon. For the ease of this project, you are to consider only 2 seasons namely Summer and Winter.
a.	Summers - March, April, May, June, July, August.
b.	Winter – September, October, November, December, January, February.




*Transportation charges are only applicable if the client is out of Texas
**Discount = client rate history +/- Season fluctuation - profit margin
***Competitors price of fuel = (Gallons requested x Average of fuel price per gallon) + Transportation.
**** Minimum Price of Competitors = minimum value for that month from both the data files and take their average



Form for Client Consists of:
1.	Client Name:
2.	Client Location:
3.	Number of Gallons
4.	Date and Month in which he wants to request the fuel
Output to the Client consists of:
1.	You need to show the client how much you are charging for the price per gallon. 
2.	Charges for transportation
3.	Discounts (in detail)
4.	Competitors price (the formula for calculation is on the top).
5.	Total Price After discount
Final Demo Requirements:
1.	You are strictly required to build a WEB APPLICATION. 
2.	You are to create a few dummy companies who have ordered from you in past few months or years.
3.	There should be a company login
4.	Company login should show all the past orders.
5.	A client order page and check out the page which all the details mentioned above.



