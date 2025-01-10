# Loan-Portfolio-Analytics-and-Visualization

## Project Overview
This project focuses on analyzing a bank loan portfolio to assess performance, identify risks, and forecast future loan outcomes. Using SQL for data extraction, Tableau, and Power BI for data visualization, the project provides insights into portfolio health, including loan defaults, trends, and risk levels. The goal was to deliver a comprehensive analysis that aids in making informed, data-driven decisions for loan portfolio management.

## Key Features
- **Data Extraction & Cleaning**: Utilized SQL to extract and clean loan data from the database, ensuring that the data was structured and ready for analysis.
- **Data Analysis**: Analyzed loan portfolio metrics, such as loan amounts, interest rates, payment history, and borrower demographics, using SQL queries.
- **Data Visualization**: Created interactive and dynamic visualizations using Tableau and Power BI, showcasing key portfolio insights, trends, and risk areas.
- **Risk Assessment**: Visualized and highlighted areas of risk in the loan portfolio, offering insights into loan default likelihood, delinquency, and trends over time.

## Technologies Used
- **SQL**: For data extraction, transformation, and analysis.
  - Queries were used to retrieve and aggregate data from relational databases.
- **Tableau**: For creating interactive data visualizations and dashboards.
- **Power BI**: For building additional reports and visualizations, comparing insights with Tableau to ensure data consistency and accuracy.
  
## Installation and Setup
To use this project, you will need access to the loan portfolio dataset and the appropriate software. Follow these steps to set up the environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/loan-portfolio-analysis.git
    ```

2. **SQL Database**:
    - Ensure you have access to the loan portfolio data stored in a SQL database.
    - Modify the SQL queries in the `scripts/queries.sql` file to reflect your database's connection and table names.

3. **Tableau/Power BI**:
    - Open the Tableau and Power BI files located in the `visualizations/` folder to explore the interactive dashboards.
    - You may need to connect the data source (SQL database or CSV files) to refresh the visualizations.

## File Structure
- `data/`: Contains the loan portfolio data in CSV format (if applicable).
- `scripts/`: SQL queries used for data extraction, transformation, and analysis.
- `visualizations/`: Tableau and Power BI files for data visualizations and reports.
- `README.md`: Documentation for the project setup and usage.

## How to Use
1. **SQL**:
    - Open the SQL scripts in the `scripts/queries.sql` file to perform data extraction and analysis.
    - Modify queries based on your database structure and execute them using your preferred SQL client (e.g., MySQL Workbench, SQL Server Management Studio).
  
2. **Tableau**:
    - Open the `.twb` Tableau workbook file in Tableau Desktop.
    - Connect to the loan data (from the SQL database or CSV) and refresh the data source to view the visualizations.
  
3. **Power BI**:
    - Open the `.pbix` Power BI file.
    - Connect to the data source, refresh the dataset, and explore the visual reports and insights.

## Results
- Interactive dashboards and visualizations in Tableau and Power BI, displaying key loan portfolio metrics such as loan performance, default risk, and trends over time.
- Insights on high-risk loans, portfolio health, and loan performance based on various factors like borrower demographics, loan amounts, and interest rates.

## Contributing
Feel free to fork the repository and contribute to the project. You can submit improvements via pull requests. If you have suggestions or improvements, please feel free to open an issue or contact me.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
If you have any questions or suggestions, feel free to reach out to me via email at aasthamistry2003@gmail.com.

---

Thank you for checking out my Data-Driven Loan Portfolio Analysis and Visualization project!
