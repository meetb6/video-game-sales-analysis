# video-game-sales-analysis
# Video Game Sales Analysis
# Project Title
# Video Game Sales Analysis Using SQL and Python

# Short Description
# This project explores historical video game sales data through SQL queries executed in Python. The primary objective is to analyze average global sales before and after the year 2005. The script demonstrates how to connect to a MySQL database, run SQL queries, and utilize window functions for data analysis.

# Getting Started
# To run this project, ensure the following are installed on your system:

# Version Required:- Python 3.x

# MySQL Server

# pip (Python package installer)

# Installing
# Install the required Python packages using:

# nginx
# Copy
# Edit
# pip install pandas pymysql sqlalchemy
# You will also need a MySQL database named vediogame with a table called vgsales containing the relevant data.

# Important: Avoid pushing your database credentials (e.g., username and password) to GitHub.

# Running the Tests
# Breakdown of Tests
# The Python script performs two main queries:

# Sales by Period
# It groups the video game sales data into two categories: games released before 2005 (pre-2005) and those released in or after 2005 (post-2005). It then calculates the average global sales for each period.

# Window Function Query
# This query uses a SQL window function to annotate each row with the average global sales of its respective period. This helps compare individual game sales to the overall average of their time group.

# The outputs are printed to the console for quick inspection.

# Deployment
# To deploy this project locally:

# Clone the repository:

bash
Copy
Edit

Update the connection string in the script to match your MySQL credentials (but do not commit these credentials to GitHub).

# Run the script:

css
Copy
Edit
python main.py
Author
Your Name
# Meet Bhanushali 

# License
This project is licensed under the MIT License.

# Acknowledgement
Public datasets inspired the structure of the vgsales table.

Documentation references used: pandas, SQLAlchemy, and MySQL.
