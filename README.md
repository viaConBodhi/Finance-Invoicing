![My Project Logo](https://github.com/viaConBodhi/finance-invoicing/blob/main/images/logo.png)

# Finance-Invoicing Project

## Overview
The Finance-Invoicing project automates monthly invoicing for services through API integration with Jira, Smartsheets MS-SQL. Aimed at streamlining financial operations, the system efficiently processes billing data, applies gratis hours, and generates detailed billing reports.

## Features
- **Automated Monthly Invoicing**: Leverages Jira data to automate the invoicing process, enhancing efficiency and accuracy.
- **Comprehensive Data Integration**: Integrates with Smartsheets to manage and store billing information, ensuring data consistency.
- **Advanced Data Processing**: Applies business logic to calculate billable hours, incorporates gratis hours, and generates billing reports for each project.
- **Error Handling and Variance Reporting**: Identifies discrepancies in billed hours and generates variance reports for review and correction.
- **Automated Report Generation**: Saves detailed billing reports as Excel files, facilitating easy distribution and record-keeping.

## Technologies Used
- **Python**: For scripting and automation.
- **Jira API**: To retrieve project and billing data.
- **Smartsheets API**: For data management and report generation.
- **Pandas**: For data manipulation and analysis.
- **SQL Server**: For database interactions, storing, and processing data.

## Installation
1. Clone this repository to your local machine.
2. Ensure Python 3.9 is installed.
3. Install required Python packages:
4. Configure API keys and database connection settings as per your environment.

## Usage
1. Update the `api_key`, `server`, `database`, `username`, and `password` variables with your credentials.
2. Execute the script in the rams_force_chargeback.ipynb file to start the automated billing process:
3. Review the generated billing reports in the specified output directory.

## Contributing
Contributions to improve the project are welcome. Please fork the repository, make your changes, and submit a pull request for review.

## License
This project is licensed under the GPL-3.0 License. See the LICENSE file for more details.

## Acknowledgments
- Special thanks to the open APIs provided by Jira and Smartsheets, enabling the automation of complex billing processes.
- Gratitude to the Python community for the invaluable libraries that support data manipulation and API interactions.

