## Exchange Rate Analysis with Interactive Visualizations
 Colab notebook for analyzing exchange rate data and generating interactive visualizations.
[![Open Notebook In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wajahatqazii/Exchange_Rate_Visualization/blob/main/exchange_rate_analysis.ipynb)
### Overview:
This Colab notebook analyzes exchange rate data from a provided dataset, focusing on the years 2022, 2023, and 2024. It calculates the percent change in exchange rates for each currency pair between these years and visualizes the trends using interactive and colorful plots.

### Requirements:
- Python 3.x
- Libraries: pandas, fastparquet, matplotlib

### How to Use:
1. Open the Colab notebook(exchange_rate_analysis.ipynb) it's linked you can run in Google Colab.
2. Ensure the required libraries are installed using `!pip install pandas fastparquet matplotlib`.
3. Run the cells in the notebook.
4. Interactive plots will be displayed showcasing exchange rate trends and percent changes.

### Features:
1. **Exchange Rate Analysis:**
   - The notebook reads exchange rate data from a provided Parquet file.
   - It filters the data for the years 2022, 2023, and 2024.
   - Calculates the percent change in exchange rates between consecutive years.

2. **Interactive Visualizations:**
   - Utilizes matplotlib library to create interactive and colorful visualizations.
   - Generates bar charts for percent changes and a line chart for exchange rate trends over time.

### Files:
- `exchange_rate_analysis.ipynb`: Colab notebook for analyzing exchange rate data and generating interactive visualizations.

### Data Source:
The exchange rate data is sourced from the Malaysian government's financial sector repository and is stored in a Parquet file format.

Please ensure you have access to the dataset and adjust the file paths accordingly in the notebook.
