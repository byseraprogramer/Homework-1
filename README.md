# Homework-1

Software Design and Architecture 
Homework 1

1.	Our team consists of two members 

•	Bisera Zejnelovikj 221556;
•	Ognen Petrovikj 221510;

2.	Project Description:
Our project focuses on stock market analysis related to the Macedonian Stock Exchange. We will develop a database-driven web application that automates the process of downloading and transforming daily stock data for issuers such as companies and financial institutions listed on the exchange. The application will collect and store at least 10 years of historical stock data for further analysis, making it easier for users to understand market trends. The architecture of the system follows a Pipe and Filter pattern, where each stage in the data processing pipeline will handle specific tasks, such as downloading, transforming, and formatting stock data.

3.	Specification of Functional and Non-Functional Requirements
Functional:
•	Historical Data Storage: Store at least 10 years of stock data for all issuers in a database.
•  Web Interface for Analysis: Develop a user interface where users can view and analyze stock trends for specific issuers over time.
•  Export Data: Enable users to export processed data for further analysis in different formats such as CSV or Excel.
	Non-Functional:
•  Performance: The application must efficiently process large volumes of stock data, minimizing the time for downloading and transforming the data.
•  Scalability: The system should be able to handle an increasing number of issuers as the stock market grows.
•  Reliability: Ensure high reliability in data download and processing, with mechanisms to recover from failures.

4.	User Scenarios and Personas
Persona 1:
•	Name: Ilija
•	Occupation: Financial Analyst
•	Goals: Ilija wants to analyze the performance of different companies on the Macedonian Stock Exchange over the last 10 years to advise his clients on investment strategies.
•	Scenario: Ilija logs into the system and filters stock data by specific companies. He views the stock trends for the last year, identifies patterns, and downloads the data for further analysis.
Persona 2:
•	Name: Ana
•	Occupation: Stock Market Enthusiast
•	Goals: Ana is interested in monitoring how certain stocks have performed historically. She wants to identify the best stocks to invest in by analyzing the stock trends over the past 10 years.
•	Scenario: Ana visits the website and selects specific stocks she's interested in. She adjusts the filters to view the data from the last 5 years and exports it to CSV to analyze the data on her own.
Narrative
•	The Macedonian stock market has experienced significant changes over the last decade, with fluctuations in the stock prices of key issuers. Ilija, a financial analyst, regularly advises clients on investment opportunities. He needs a reliable tool that provides historical stock data quickly and allows him to compare trends over long periods. Similarly, Ana, a stock market enthusiast, looks for user-friendly tools to make better-informed personal investment decisions. Both users benefit from a streamlined web application that provides comprehensive and accurate stock data, backed by an efficient pipeline that downloads, transforms, and stores daily stock market data for further analysis.
