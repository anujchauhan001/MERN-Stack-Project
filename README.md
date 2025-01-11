MERN Stack Project - Transaction Management System
This is a MERN Stack project that implements a Transaction Management System. It allows you to interact with product transactions, perform searches, view statistics, and visualize data through bar and pie charts. This project consists of both a Backend API and a Frontend UI.

##Features
#Backend APIs:
Initialize Database: Fetch data from a third-party API and initialize the database with seed data.
Transaction Listing API: Lists all product transactions with support for search and pagination.
Statistics API: Fetches total sales amount, total number of sold items, and total number of not sold items for a given month.
Bar Chart API: Returns the price range and the number of items sold in each range for the selected month.
Pie Chart API: Fetches unique categories and the number of items sold in each category for the selected month.
Combined Data API: Combines responses from the above APIs into a single response.

#Frontend:
Transaction Table: A table to list product transactions with options for month selection, search, and pagination.
Statistics Display: Displays statistics such as total sales amount, total sold items, and total unsold items for the selected month.
Bar Chart: Displays a bar chart of item counts in different price ranges for the selected month.
Pie Chart: Displays a pie chart of item distribution across different categories for the selected month.
Technologies Used
Frontend: React.js, Axios, Chart.js
Backend: Node.js, Express.js
Database: MongoDB
API Communication: RESTful APIs
Charting: Chart.js (for Bar and Pie charts)
