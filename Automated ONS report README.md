# projects
Current Data Science / Statistics projects

Every month the UK Office of National Statistics releases statistics on UK labour markets.

The releases include data on variables such as employment rates and economic activity rates.

The Automated ONS Report project presents python code that can be used to automate downloading, wrangling and visualisation of data from these releases.
The code effectively automates a workflow from a previous job at London City Hall and visualises employment and economic activity data for UK regions, quarter on wuarter change and presents a long run time series.
These visualisations can then be used as the main highlights of a monthly bulletin for policy makers.

Each of the following stages are defined in a function:
- Downloading the relevant dataset from the ONS website
- Wrangling the data to produce a chart showing regional comparisons
- Repaeating this process to create a chart showing regional quarter on quarter change rates
- Wrangling data to create a time series chart.

These functions are then scheduled to run on the second Tuesday of each month when the ONS releases the data
