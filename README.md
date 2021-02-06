# My-Aktia-Challenge-2021

Here you can find my answer as the PowerBI file. On the file there are four pages. The main page includes a short description of the file and what I did to solve the problem. The three other pages present the visualizations and the insights that can be seen from them.

In addition, here is the SQL query for the bonus task to get the entire usable dataset from the database:

SELECT *

FROM Events, Customers, Products

WHERE Events.CustomerID = Customers.CustomerID AND Events.ProductID = Products.ProductID;
