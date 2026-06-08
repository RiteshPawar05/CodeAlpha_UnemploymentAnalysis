# CodeAlpha_UnemploymentAnalysis

## Project Overview
This project is part of the CodeAlpha Data Science Internship. The goal is to analyze the unemployment rate data in India, specifically focusing on the impact of the COVID-19 pandemic on the job market. This involves data cleaning, exploratory data analysis, and visualizations to extract meaningful insights.

## Dataset Information
The datasets used (`Unemployment in India.csv` and `Unemployment_Rate_upto_11_2020.csv`) contain the following key attributes:
- `Region`: States in India.
- `Date`: Date of observation.
- `Frequency`: Frequency of data collection.
- `Estimated Unemployment Rate (%)`: The percentage of people unemployed.
- `Estimated Employed`: The number of people currently employed.
- `Estimated Labour Participation Rate (%)`: The proportion of the working-age population that is part of the labor force.
- `Area`: Rural vs Urban areas.

## Technologies Used
- **Python 3.x**
- **Pandas & Numpy** for data manipulation and analysis
- **Matplotlib, Seaborn, and Plotly** for static and interactive data visualization
- **Jupyter Notebook** for code execution and reporting

## Installation Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/CodeAlpha_UnemploymentAnalysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CodeAlpha_UnemploymentAnalysis
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Unemployment_Analysis.ipynb
   ```

## Results & Insights
- **COVID-19 Impact:** A sharp spike in the unemployment rate was observed around April-May 2020, perfectly aligning with the nationwide COVID-19 lockdown in India.
- **State-wise Variations:** Certain states were hit harder than others depending on their reliance on informal sectors and strict lockdown implementations.
- **Rural vs Urban:** The analysis shows distinct differences in how urban and rural employment sectors were affected, highlighting the vulnerability of urban daily wage earners during the pandemic.

## Screenshots
*(Add screenshots of your EDA pairplot and confusion matrix inside the `screenshots/` folder and link them here)*
- `screenshots/unemployment_trend.png`
- `screenshots/statewise_bar.png`

## Future Scope
- Integrate predictive modeling (Time-Series Forecasting like ARIMA or Prophet) to predict future unemployment trends.
- Combine this data with COVID-19 cases data to show a direct correlation between active cases/lockdowns and unemployment dips.

## Author
[Your Name]  
Data Science Intern at CodeAlpha
