# AutomateFinancesWithPython

WEBAPP LINK : https://autofinance.streamlit.app/


# Simple Finance Dashboard

## INTRODUCTION
This application is an interactive finance analyzer built with Streamlit in Python. It is designed to help users upload, categorize, and analyze their financial transactions from CSV files. The app automates transaction categorization based on user-defined keywords, provides editable expense classifications, and visualizes spending patterns to support better personal financial management and decision-making.

## PROBLEM STATEMENT
Many individuals and small businesses struggle to efficiently analyze their financial transactions due to lack of automated tools that categorize and summarize expenses. Manual methods such as spreadsheets or basic accounting software often require tedious data entry and do not provide insightful visualizations or dynamic categorization, leading to poor financial awareness and management.

## IMPORTANCE OF THIS PROJECT
This project simplifies personal finance management by automating transaction categorization and providing clear, interactive visual summaries of expenses and payments. It reduces manual effort, minimizes errors in classification, and empowers users to track spending habits effectively. The project also demonstrates practical use of Python, Streamlit, and data visualization libraries to build user-friendly financial tools.

## MAIN OBJECTIVE
To develop an easy-to-use web application that automates the categorization and analysis of financial transactions, enabling users to gain insights into their spending and payments through interactive tables and charts.

## SPECIFIC OBJECTIVES
- Enable uploading of transaction data via CSV files.
- Automatically categorize transactions based on customizable keyword lists.
- Allow users to create new categories and assign keywords dynamically for better classification.
- Provide an editable interface for users to manually adjust transaction categories.
- Summarize expenses by category with sortable tables and pie chart visualizations.
- Display payment (credit) transactions separately with total payment metrics.
- Persist category data across sessions using JSON storage.
- Ensure robust parsing of dates and amounts for accurate financial calculations.

| Step                          | Description                                                                                  |
|-------------------------------|----------------------------------------------------------------------------------------------|
| Transaction Upload             | Upload CSV files containing transaction data for analysis.                                  |
| Data Parsing                  | Clean and convert transaction dates and amounts into appropriate formats.                   |
| Automatic Categorization       | Assign categories to transactions based on user-defined keywords.                           |
| Category Management            | Add, edit, and save categories and keywords persistently.                                   |
| Interactive Editing            | Modify transaction categories directly in the app interface.                               |
| Expense Summary               | Aggregate and display expenses by category in tables and pie charts.                        |
| Payments Overview             | Show all credit transactions and total payments.                                           |
| Data Persistence              | Store categories and keywords in a JSON file for reuse across sessions.                     |

## METHODOLOGY
- **Data Upload and Loading:** Users upload CSV files containing transaction data with columns such as Date, Details, Amount, and Debit/Credit.
- **Data Cleaning:** The app processes and cleans the data, converting amounts to numeric and parsing dates.
- **Categorization:** Transactions are initially marked "Uncategorized." The app matches transaction details with keywords in each category to assign categories automatically.
- **User Interaction:** Users can add new categories and keywords, and edit categories for individual transactions via an interactive data editor. Changes update keyword lists and improve future categorization.
- **Visualization:** Expense data is aggregated by category and displayed in sortable tables and pie charts using Plotly for interactive exploration. Payments are summarized separately.
- **Persistence:** Categories and keywords are saved in a JSON file to maintain user customizations between sessions.

## PROJECT FEATURES

| S.No | Feature                          | Description                                                                                     |
|-------|---------------------------------|-------------------------------------------------------------------------------------------------|
| 1     | CSV File Upload                 | Upload transaction data in CSV format for analysis.                                            |
| 2     | Automatic Categorization        | Assign categories to transactions based on keyword matching.                                   |
| 3     | Custom Category Creation        | Add new expense categories dynamically within the app.                                         |
| 4     | Keyword Management              | Assign keywords to categories to improve automatic classification.                             |
| 5     | Editable Transaction Categories | Modify categories directly in an interactive data editor.                                     |
| 6     | Expense Summary Table           | View aggregated expenses by category in a sortable table.                                     |
| 7     | Pie Chart Visualization         | Interactive pie chart showing expense distribution by category.                               |
| 8     | Payments Summary                | Separate tab displaying all credit transactions and total payment amount.                      |
| 9     | Persistent Category Storage     | Save and load category keywords from a JSON file for persistent customization.                 |
| 10    | Robust Data Parsing             | Handle date formatting and amount conversion for accurate analysis.                            |
| 11    | Responsive UI Layout            | Use Streamlit tabs and wide layout for an intuitive, organized user experience.                |

## PROJECT PAGES

### PAGE 1: EXPENSES (DEBITS)
- Upload and display debit transactions.
- Add new categories and keywords.
- Edit transaction categories interactively.
- View expense summary by category in table and pie chart formats.

### PAGE 2: PAYMENTS (CREDITS)
- Display all credit transactions.
- Show total payments metric.

