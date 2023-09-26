
# Case Study - Dicoding Collection

## 1. Background

Dicoding Collection or often abbreviated as DiCo is a company specializing in fashion. They produce various fashion items and sell them through online platforms. 

As a contemporary company, DiCo realizes how crucial data is for the growth of a business. Hence, they stored all the sales history along with information related to products and customers in a database. This database consists of four tables, including customers, orders, products, and sales. 

- `Customers table`: this table stores various customer-related information, such as customer_id, customer_name, gender, age, home_address, zip_code, city, state, and country.
- `Orders table`: this table stores various information related to an order consisting of order_id, customer_id, order_date, and delivery_date.
- `Products table`: this table contains various information related to a product, such as product_id, product_type, product_name, size, color, price, quantity, and description.
- `Sales table`: this table contains detailed information related to sales, such as sales_id, order_id, product_id, price_per_unit, quantity, and total_price.

## 2. Project work cycle
1. Data Wrangling: 
 - Gathering data
 - Assessing data
 - Cleaning data
2. Exploratory Data Analysis:
 - Defined business questions for data exploration
 - Create Data exploration
3. Data Visualization:
 - Create Data Visualization that answer business questions
4. Dashboard:
 - Set up the DataFrame which will be used
 - Make filter components on the dashboard
 - Complete the dashboard with various data visualizations

**Note: Numbers 1 to 3 are in the dicoding-collection-exercise and number 4 is in dashboard.**

## 3. Getting Started
### `dicoding-collection-exercise`
1. Download this project.
2. Open your favorite IDE like Jupyter Notebook or Google Colaboratory (but in here I will use Google Colab).
3. Create a New Notebook.
4. Upload and select the file with .ipynb extension.
5. Connect to hosted runtime.
6. Lastly, run the code cells.

### `dashboard`
1. Download this project.
2. Install the Streamlit in your terminal or command prompt using `pip install streamlit`. Install another libraries like pandas, numpy, scipy, matplotlib, and seaborn if you haven't.
3. Please note, don't move the csv file because it acts a data source. keep it in one folder as dashboard.py
4. Open your VSCode and run the file by clicking the terminal and write it `streamlit run dashboard.py`.
