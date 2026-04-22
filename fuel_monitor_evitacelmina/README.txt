Fuel Price Monitoring Tool
==========================

What the tool does
------------------
The tool monitors two things. The first one is the global Brent Crude Oil price in USD/barrel. And the second one is the retail price of E95 petrol and diesel prices for the top 4 Latvian fuel providers (Virsi, Circle K, Neste, and Viada)

Business problem it solves
--------------------------
Fuel holds a high margin over operating expenses for e-commerce companies that run their own delivery fleet. Without monitoring, overpay can happen at the pump. This tool turns a manual price check into an automated process and builds a historical dataset.


Challenge and how vibe coding solved it
---------------------------------------
Biggest chalange was activating the generating .py file. However, when giving AI the way I was trying to activate the file turned out that I had to add a 'python3 fuel_monitor.py'  instead of 'python fuel_monitor.py'

Files in this archive
---------------------
- fuel_monitor.py          Full Python script with all four modules + main()
- fuel_price_history.csv   Timestamped history (populated from 4 runs)
- price_trend.png          Auto-generated line chart
- README.txt               This file

How everything was run
----------------------
    pip install yfinance requests beautifulsoup4 pandas matplotlib lxml
    python3 fuel_monitor.py

Process
-------
A new GitHub repository was created 
Access was given to Antigravity to the repository
Requirements were given 1 task at a time.
Generated code was automatically (with human approval) committed to GitHub 
Github repository added to the computer
Run with the above commands