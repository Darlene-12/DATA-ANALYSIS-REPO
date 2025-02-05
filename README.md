# Billionaires Data Analysis

This project provides an in-depth analysis of a dataset of billionaires to uncover insights into their wealth distribution, age, industries, sources of wealth, and geographic locations. The analysis includes nine interactive visualizations created using Python and Plotly.

## Features

- **Data Cleaning**:
  - Converted raw dataset values (e.g., `$130 B`) into numerical format for analysis.
  - Handled missing values and detected outliers using statistical methods.
  
- **Interactive Visualizations**:
  - Nine insightful visualizations providing detailed insights into the data.

## Visualizations

### 1. # Total Net Worth by Country
- A treemap displaying the cumulative net worth of billionaires by country.
- **Key Insight**: The United States and China dominate in total billionaire wealth.

### 2. # Top 20 Countries with Most Billionaires
- A bar chart showing the top 20 countries ranked by the number of billionaires.
- **Key Insight**: The United States leads with 720 billionaires, followed by China with 610.

### 3. # Top Industries with Most Billionaires
- A bar chart ranking the industries producing the highest number of billionaires.
- **Key Insight**: Finance & Investments, Technology, and Manufacturing are the top three industries.

### 4. # Visualization of the Age Distribution of Billionaires
- A 2D line chart illustrating the age distribution of billionaires.
- **Key Insight**: Billionaire wealth peaks between the ages of 55 and 70.

### 5. # Top 10 Richest Billionaires
- A bar chart showing the top 10 billionaires by net worth.
- **Key Insight**: Jeff Bezos, Elon Musk, and Bernard Arnault & family dominate the list.

### 6. # Scatter Plot of Age vs. Net Worth
- A scatter plot analyzing the relationship between age and net worth, categorized by industry.
- **Key Insight**: Wealth accumulation is highest in middle age, particularly in Technology and Finance.

### 7. # Top Sources of Wealth for Most Billionaires
- A bar chart showcasing the most common sources of billionaire wealth.
- **Key Insight**: Real Estate, Pharmaceuticals, and Investments are leading sources.

### 8. # Correlation Heatmap: Age, Rank, and Net Worth
- A heatmap visualizing the correlation between Age, Rank, and Net Worth.
- **Key Insight**: Net Worth and Rank have a strong negative correlation, while Age shows minimal influence.

### 9. # Correlation Heatmap: Country, Source, and Industry
- A heatmap showing the correlation between Country, Source, and Industry.
- **Key Insight**: Weak correlations suggest diverse distributions of wealth sources and industries across countries.

## Tools and Libraries

- **Python**:
  - **Pandas**: Data manipulation and preprocessing.
  - **Plotly**: Interactive data visualizations.
  - **Jupyter Lab**: Organizing and running the analysis.

## Dataset Overview

The dataset contains the following columns:
- **Name**: The billionaire's name.
- **Net Worth**: Their net worth (in billions of USD).
- **Country**: Country of citizenship.
- **Source**: Primary source of their wealth.
- **Industry**: The industry they operate in.
- **Age**: Age of the billionaire.
- **Rank**: Their rank in the global billionaire list.

## How to Run

1. **Set up a virtual environment**:
   ```bash
   python3 -m venv billionaire_env
   source billionaire_env/bin/activate
   pip install -r requirements.txt
   ```

2. **Install Dependencies**:
   ```bash
   pip install pandas plotly jupyterlab
   ```

3. **Launch Jupyter Lab**:
   ```bash
   jupyter lab
   ```

4. **Run the Notebook**:
   - Open the `billionaires.ipynb` notebook to explore the analysis and visualizations.

## Insights

- The United States and China dominate in billionaire count and total wealth.
- Finance & Investments and Technology are the most lucrative industries for billionaires.
- Wealth accumulation peaks in middle age, with a significant drop after age 70.
- Real Estate, Pharmaceuticals, and Investments are leading wealth sources.

## Future Improvements

- Add time-series analysis to explore trends over the years.
- Integrate Power BI dashboards for more advanced visualizations.
- Build predictive models to estimate billionaire wealth based on key features.

## Contributing

Contributions are welcome! Feel free to fork this repository, make a feature branch, and submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).
