# CSV-TASK
Upload CSV files through a simple form.
Process the CSV file asynchronously using Celery.
Perform column-wise calculations on numerical columns: Sum, Average, and Count.
Calculate additional metrics like Total Revenue, Average Discount, Best-Selling Product, Most Profitable Product, and Product with Maximum Discount.
Display processed data on the frontend in a tabular format.
Implement search functionality to filter displayed data by product name.
Dynamically update the processed data without page refresh.

Dependencies:
Django: Web framework for building the project.
Celery: Asynchronous task queue for background processing.
Redis: Message broker used by Celery.
Pandas: Data manipulation and analysis library for CSV processing.
