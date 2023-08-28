# Job_Search_Insights
To provide a comprehensive snapshot of the job market, we obtained daily job listings from ai-jobs.net, encompassing roles such as SAP, Data Engineer, Machine Learning Engineer, and Software Developer. Investigate data extraction, cleansing, analysis, visualization, and prediction strategies to obtain an advantage in your job search.

Background:
project was meticulously designed to collect and analyze job data across four distinct job criteria: SAP, Software Engineer, Data Scientist, and Machine Learning Engineer. This endeavor encompassed transforming raw data into meaningful insights, complemented by dynamic data visualizations accomplished through Power BI. Furthermore, the project culminated in the creation of a mobile application using PowerApps, offering a multifaceted toolkit for prospective job seekers.

Data Extraction:
To gather job data, I utilized web scraping techniques to extract information from the job listing website. The selectors involved were HTML elements such as input fields, headings, and spans, which were essential for locating and retrieving specific data points. These selectors were crucial in navigating the website's structure and extracting the required information. The extracted data provides valuable insights into the job market for different roles, experience levels, and countries.

Data Transformation:
After scraping the job data, I processed and cleaned it to prepare it for analysis. I used Python's Pandas library to structure the data and fill in missing values. The data transformation phase involved handling null values, structuring job attributes, and organizing the information into a more usable format for analysis and visualization.

Data Load:
Data loading phase will reads data from a TSV file, creates an SQLite database, defines a table structure, processes the data, inserts it into the database, fetches and prints the data, and provides a coherent way to manage this process through well-defined functions.

Data Visualization:
For data visualization, I leveraged Power BI to create insightful visualizations based on the cleaned job data. I visualized factors such as job roles, types, experience levels,
salaries, skills, and benefits. Using Power BI's interactive features, I generated graphs, charts, and tables that allowed for easy exploration and analysis of the job data.
Power BI was the technology of choice for creating dynamic and interactive visualizations. With its user-friendly interface and powerful capabilities, I created engaging dashboards that provided insights into job trends and attributes. The visualizations helped in identifying patterns, trends, and relationships within the job data.
