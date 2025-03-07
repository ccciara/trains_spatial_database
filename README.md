# Train Station Spatial Database
#### UCL CEGE0052 Spatial Databases and Data Management project
In this project, I created a spatial database in PostgreSQL and populated it with train stations, entrances, and ticket barriers. Non-spatial data within the database included tickets, customers, and transactions. Transactions were linked to customers, tickets, ticket barriers, entrances, and stations. Physical assets nested within each other (station->entrance->ticket barrier) are also linked.

Queries were written to provide information for decision making. Some are maintenance oriented, for example viewing the ticket barriers with the highest failure rate for transactions. Others queries include retrieving the average age of customers passing through each station at each hour of the day, in order to best target station advertisements.

I recommend viewing the files in this order:
1. Create table
2. Create constraints
3. Insert data
4. Create views
5. Decisions (Queries)

Here's a screenshot of the spatial elements of the database imported into QGIS. Not sure why I did not turn on a background map layer at the time! Unfortunately I had to uninstall QGIS to free up some space on my laptop so that's the best I have at the moment.

<img width="1022" alt="Screenshot 2025-01-25 at 5 29 22 PM" src="https://github.com/user-attachments/assets/29176b31-6871-4e7d-8111-c282e3ba4bd9" />
