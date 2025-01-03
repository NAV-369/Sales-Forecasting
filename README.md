# Rossmann Pharmaceuticals Sales Forecasting

## Project Overview
This project focuses on analyzing customer purchasing behavior and forecasting sales for Rossmann Pharmaceuticals. By leveraging data-driven insights, the goal is to enhance sales forecasting accuracy, which is crucial for effective inventory management and strategic planning.

## Data Sources
The analysis utilizes two primary datasets:
- **Training Dataset**: Contains daily sales information for various stores, including features such as sales, customers, promotions, and holidays.
- **Store Dataset**: Provides additional information about each store, including assortment types and competitor distance, which are essential for understanding sales dynamics.

## Project Structure
- **.vscode/**: Contains settings for Visual Studio Code.
- **.github/**: Contains GitHub workflows for continuous integration and deployment, including unit tests.
- **.gitignore**: Specifies files and directories to be ignored by Git to maintain a clean repository.
- **requirements.txt**: Lists all Python packages required for the project, ensuring a consistent development environment.
- **README.md**: Provides an overview and documentation for the project, guiding users through its structure and usage.
- **src/**: Contains source code files for data processing, analysis, and modeling.
- **notebooks/**: Contains Jupyter notebooks for exploratory data analysis (EDA) and visualizations, showcasing key findings and methodologies.
- **tests/**: Contains unit tests to validate the functionality and reliability of the code.
- **scripts/**: Contains scripts for data processing and other utility functions relevant to the project.

## Getting Started
To get started with the project, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required dependencies using the command:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter notebooks to explore the analyses and visualizations.

## Analysis Overview
The exploratory data analysis (EDA) conducted in this project focuses on understanding customer purchasing behavior through various visualizations and statistical analyses. Key areas of focus include:
- **Distribution of Promotions**: Analyzing how promotions impact sales across different stores.
- **Seasonal Trends**: Identifying seasonal purchasing behaviors and their implications for inventory management.
- **Sales Correlation**: Exploring the relationship between sales and customer footfall to inform marketing strategies.
- **Assortment and Competitor Analysis**: Evaluating how assortment types and competitor distance affect sales performance.

## Future Work
Future analyses could include predictive modeling to forecast sales based on the identified trends and factors. Additionally, incorporating external data such as economic indicators and demographic information could enhance the understanding of customer purchasing behavior and improve forecasting accuracy.

## Acknowledgments
We would like to acknowledge the contributions of the Rossmann Pharmaceuticals team and the Kaggle community for providing the datasets used in this analysis. Their efforts have been instrumental in facilitating this project.
