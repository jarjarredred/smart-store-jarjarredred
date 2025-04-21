# smart-sales-raw-data
Holds some raw data for a smart sales project. Generally, save these files to your project and put them in the data/raw folder. 
# smart-sales-starter-files
# Use .venv\Scripts\activate
# Update/Install Required Packages w/ python -m pip install --upgrade -r requirements.txt

# Use git add .
# Use git commit -m "add BLANK files"
# Use git push -u origin main
Starter files to initialize the smart sales project.

-----

## Project Setup Guide (2-Windows)

Run all commands from a PowerShell terminal in the root project folder.

### Step 2A - Create a Local Project Virtual Environment

```shell
py -m venv .venv
```

### Step 2B - Activate the Virtual Environment

```shell
.venv\Scripts\activate
```

### Step 2C - Install Packages

```shell
py -m pip install --upgrade -r requirements.txt
```

### Step 2D - Optional: Verify .venv Setup

```shell
py -m datafun_venv_checker.venv_checker
```

### Step 2E - Run the initial project script

```shell
py scripts/data_prep.py
```

-----

## Initial Package List

- pip
- loguru
- ipykernel
- jupyterlab
- numpy
- pandas
- matplotlib
- seaborn
- plotly
- pyspark==4.0.0.dev1
- pyspark[sql]
- git+https://github.com/denisecase/datafun-venv-checker.git#egg=datafun_venv_checker

### Step 3 Update DataScrubber Class
# Run test script w/ py tests\test_data_scrubber.py

# P4 Created DW. Star Scheme with. Column names may not be consistant due to not catching it in previous modules. Updated column names to reflect the incosistant names.

# Created SQL query for Top Customers (tried to). Created visualization reports.
![alt text](<Screenshot 2025-04-10 195323.png>)
![
](<Screenshot 2025-04-10 195311.png>)
![alt text](<Screenshot 2025-04-10 195307.png>)
![alt text](<Screenshot 2025-04-10 195301.png>)
![alt text](<Screenshot 2025-04-10 195245.png>)

# Section 1. The Business Goal
# The business goal is to determine the top grossing product by month. This can be useful to see if advertising needs to be more targeted during certian months.
# Section 2. Data Source
# I started with a prepared data and a data warehouse.
# I used Products table, ProductName; and the Sale table, saleamount, sale date, month year.
# Section 3. Tools
# I used python and power bi and measures within power bi.
# Section 4. Workflow & Logic
# I needed saleamount totaled by month by each productID
# If using a graphical tool like Power BI or Tableau Prep, use screenshots to show your work.
![alt text](<Screenshot 2025-04-21 001131.png>)
# Section 5. Results
# The laptops bring in the most money but we will need cost data to determine revenue.
# Section 6: Suggested Business Action 
# The company should be aware of their cost of the laptops and if they have a wide margin, they should consider increasing their stock quantity so that they can sell more.
# Section 7. Challenges
# I had some challenges with measures in Power BI with syntax errors when trying to convert the date column to a single variable like month.