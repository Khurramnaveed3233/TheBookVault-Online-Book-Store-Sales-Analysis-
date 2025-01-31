# TheBookVault-Online-Book-Store-Sales-Analysis

The project aims to analyze book inventory by understanding the availability and demand for different genres and specific books. It also seeks to gain customer insights by identifying purchasing trends, customer locations, and frequent buyers.

Additionally, tracking sales performance is a key objective, including revenue, best-selling books, and total sales figures. Operational efficiency is evaluated by assessing stock levels and recommending restocking strategies. The analysis further delves into market trends by identifying customer preferences through an examination of genres, authors, and pricing trends. Ultimately, the project provides stakeholders with actionable recommendations based on data-driven insights to optimize business decisions and enhance overall performance.

Basic Queries
 1) Retrieve all books in the "Fiction" genre
 2) Find books published after the year 1950
 3) List all customers from the Canada
 4) Show orders placed in November 2023
 5) Retrieve the total stock of books available
 6) Find the details of the most expensive book
 7) Show all customers who ordered more than 1 quantity of a book
 8) Retrieve all orders where the total amount exceeds $20
 9) List all genres available in the Books table
 10) Find the book with the lowest stock
 11) Calculate the total revenue generated from all order
     
Advance Queries
 1) Retrieve the total number of books sold for each genre
 2) Find the average price of books in the "Fantasy" genre
 3) List customers who have placed at least 2 orders
 4) Find the most frequently ordered book
 5) Show the top 3 most expensive books of 'Fantasy' Genre 
 6) Retrieve the total quantity of books sold by each author
 7) List the cities where customers who spent over $30 are located
 8) Find the customer who spent the most on orders
 9) Calculate the stock remaining after fulfilling all order

-- 1) Retrieve all books in the "Fiction" genre:

    SELECT * FROM Books WHERE Genre='Fiction';


   
