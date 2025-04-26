## ***SAL_BW_Project_1*** 
## ***Assignment: Web Scraping, SQL Insights, and Data Visualization***  


### **Project Objective** 
* To scrape book data from the website (http://books.toscrape.com/)
* Save the data in a CSV file
* Generate SQL insights using MySQL
* Perform Exploratory Data Analysis (EDA) and Data Visualization using Python.
* 

### **Project Walkthrough (Video)**


   
  2. Store the data in a CSV file with columns:
 
    ```
    title, price, availability, rating
    
    ```
3. Ensure that all pages are scraped, not just the first one.


### **Part 2: SQL Insights**

After scraping and saving the data, load it into a SQL database and answer the following questions:

1. **Find the number of books available in stock.**
2. **List the top 5 most expensive books.**
3. **Find the average rating of books.**
4. **Retrieve the total number of books for each rating (e.g., 1-star, 2-star, etc.).**

**Example Insights (For Reference)**

- There are **X** books available in stock.
- The most expensive book is **"XYZ"**, priced at **£59.99**.
- The average rating of books is **4.2 stars**.
- There are **Y** books with a **5-star** rating.


### **Part 3: Exploratory Data Analysis (EDA) and Data Visualization**

Using **Pandas, Matplotlib, and Seaborn**, perform the following:

1. **Basic EDA**
    - Load the CSV into a Pandas DataFrame.
    - Display basic statistics about the dataset (e.g., number of books, average price, missing values, etc.).
2. **Data Visualization**
    - **Bar chart** of the number of books for each rating (1 to 5 stars).
    - **Histogram** showing the distribution of book prices.
    - **Pie chart** representing the proportion of books in stock vs. out of stock.
    - Any other creative visualization that helps understand the dataset.
