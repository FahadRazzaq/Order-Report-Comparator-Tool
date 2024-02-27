## Project Summary: Order-Report-Comparator-Tool

### Objective: Automate the comparison of consecutive reports from an e-commerce order management system to track inventory changes efficiently.

### Key Features: 
1. Web Scraping: Extract data using Selenium from the order management system.
2. Data Parsing: Utilize BeautifulSoup to parse HTML data into structured tables.
3. Comparison Analysis: Compute differences between successive reports to highlight inventory fluctuations.
4. Visualization: Present comparison results in visually appealing tables for easy interpretation.
5. Slack Integration: Send comparison tables as images to Slack channels for timely updates.

### Workflow:
1. Data Extraction: Selenium fetches inventory reports and related metrics from the system.
2. Data Parsing: BeautifulSoup converts HTML data into structured Pandas DataFrames.
3. Comparison Analysis: Pandas computes differences between consecutive reports.
4. Visualization: Comparison results are formatted into visually appealing tables.
5. Slack Notification: Script sends comparison tables as images to designated Slack channels.

### Conclusion:
By automating the comparison of e-commerce order reports, this project significantly enhances operational efficiency and decision-making processes. Stakeholders receive timely insights into inventory fluctuations, enabling proactive measures to optimize inventory management and ensure seamless order fulfillment.
