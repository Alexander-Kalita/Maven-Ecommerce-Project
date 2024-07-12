
# Overview

This project aims to analyze the website traffic and performance data of Maven Fuzzy Factory, a US-based e-commerce startup. The goal is to identify sources of profitable growth through a detailed examination of various business aspects. The analysis focuses on the conversion funnel, which was analyzed over three years and visualized in an interactive dashboard, as it significantly impacts other key visualizations like gross profit margin by month, average order value by product category and revenue per session by channel group and user type. The dashboard is designed primarily for the top management team but can also benefit other stakeholders by highlighting crucial business insights.

# Problem

The project provides comprehensive insights to address the strategic challenges faced by Maven Fuzzy Factory. Identifying key aspects impacting profitable growth, deciding where to invest resources, and distinguishing essential metrics to monitor can be challenging, thus requiring thorough analysis. A primary recommendation is to focus on optimizing the website's conversion funnel to reduce user drop-off. Addressing this issue will pave the way for studying other critical metrics, such as average order value and revenue per session, ultimately improving the gross profit margin.

# Dataset

The Maven Fuzzy Factory dataset spans from March 2012 to March 2015 and includes six tables essential for ecommerce operations. These tables encompass web analytics data such as website sessions, pageviews, and sales information including products, orders, order items, and order item refunds. For a visual representation, please refer to Figure 1, which illustrates the dataset's structure in a SQL schema. The dataset can be accessed [here].

![Maven_MySQL_Schema](https://github.com/user-attachments/assets/0e565604-4cfa-4696-b078-3de174031fa4)

# Architecture

The project primarily utilizes Python with libraries such as numpy, pandas, and matplotlib. Data stored in MySQL database was accessed and integrated into Python using SQL magic commands for data cleaning, transformation, and analysis. Subsequently, the MySQL database was connected to Power BI Desktop to develop an interactive dashboard for analyzing the conversion funnel across multiple years. The entire project is documented as a report within JupyterLab and uploaded to GitHub for accessibility.

# GIF

The interactive Power BI dashboard is showcased as a demo GIF since the full dashboard couldn't be uploaded to GitHub due to size constraints. The GIF primarily demonstrates the interactive filtering functionality, highlighting how conversion funnel dynamics can be visualized and compared across different years.

![Conversion_Funnel](https://github.com/user-attachments/assets/244c8946-d89c-43e3-9557-ab31bdd826bf)

