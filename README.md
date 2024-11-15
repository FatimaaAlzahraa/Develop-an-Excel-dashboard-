## Excel Dashboard for Inventory Monitoring
This project provides an Excel dashboard that enables store management to:

Monitor inventory levels.
- Track missing items by day, time of day, and responsible staff member.
- Visually summarize data for quick insights and informed decision-making.
= The dashboard is developed using Python and Excel, and the analysis is automated through the provided Jupyter Notebook.

#### Objective
The primary objective of this dashboard is to provide store managers with a tool
to easily track and analyze missing inventory items over various dimensions, including:
- Date
- Time of day
- Responsible staff members
- Item categories

#### Features
The dashboard includes the following elements:
##### KPIs Summary Section:
- Total Missing Items: Total count of missing items in the dataset.
- Highest Missing Quantity per Day: Day with the most missing items.
- Top Missing Item: Item with the highest overall missing quantity.
- Staff Member with Most Missing Items: Staff member with the most missing items.

##### Detailed Analysis:
- Total Missing Items per Day
- Missing Items by Time of Day
- Missing Items by Staff
- Missing Patterns by Day of the Week
- Top 2 Items with the Highest Missing Quantities
- Time Shifts (Morning, Afternoon, Evening) with Highest Missing Quantities

##### Interactive Filtering & Slicers:
= Date, Time of Day, Responsible Staff, Item Category
= Real-time updates on the dashboard based on slicer selections

##### Data Visualization:
- Trend analysis for missing items
- Top missing items
- Missing items distribution by time and staff

##### Requirements
To run this project, you will need:
- Python 3.x
- Jupyter Notebook
- Libraries:
- pandas for data manipulation
- matplotlib and seaborn for visulization


##### Run the Notebook:
- Open the Jupyter Notebook provided in this repository (Develop an Excel dashboard.ipynb).
- Run the notebook cells sequentially to generate the analysis.
- The notebook reads an Excel file, processes the data, calculates metrics, and saves the results to an output file.

  
##### Input Data:
- Ensure the input Excel file with columns such as Date, Time, Item ID, Category, Responsible Staff, Expected Quantity, 
and Actual Quantity is available in the specified path.

##### Generate the Output:
- The notebook will produce dashbored to view the result and produce a new Excel file with multiple sheets containing key insights and metrics ready to be used in an Excel dashboard.


##### Usage
The Jupyter Notebook (Develop an Excel dashboard.ipynb) automates the data analysis and prepares the data for dashboard creation. Follow these steps:

- Load Data: Import the Excel data into the notebook.
- Run Analysis: Execute each cell in the notebook to calculate metrics and generate data tables.
- Review Output: The notebook saves an output Excel file containing:
  -- KPI Summary
  -- Detailed analysis data for each dimension (by day, staff, time, and items)
  -- dasbord in notebook 
