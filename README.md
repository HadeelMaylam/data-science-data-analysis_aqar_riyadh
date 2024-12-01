
# Data Science Project: Riyadh Aqar Real Estate Analysis

## Project Overview
This project explores the Riyadh real estate market using the Aqar Riyadh dataset. The goal is to uncover key insights into property trends, popular districts, agency performance, and price drivers through Exploratory Data Analysis (EDA) and visualize it. The aim is to deliver actionable insights that help stakeholders (e.g., investors, buyers, and agencies) make decisions in the real estate sector.

## Deliverables

### 1. Presentation
The presentation will follow a storytelling format covering:
- **Project Idea**: The role of data in understanding Riyadh’s real estate market.
- **Data Collection**: Description of the data source.
- **Data Cleaning**: Handling missing values, outliers, duplicates, and feature engineering.
- **Insights**: Key insights supported by visualizations, such as:
  - Distribution of property types.
  - Analysis of districts with the most properties.
  - Agencies with the highest activity and price trends.
  - Trends in price per square meter by district.
- **Recommendations**: Insights for buyers, sellers, and investors.
- **Optional**: Deployment showcase (Streamlit).

### 2. Python Notebooks
- **Data Cleaning**:
  - Code and documentation for handling:
    - Missing values.
    - Outliers and duplicates.
    - Transformations (e.g., feature engineering: extracting Price-per-sqm).
  - **File**: `data_cleaning.ipynb`

- **Insights**:
  - Markdown cells explaining derived insights.
  - Visualizations (e.g., bar charts, heatmaps, scatter plots) created using Matplotlib and Seaborn.
  - **File**: `insights_and_visualizations.ipynb`

### 3. Deployment (Optional)
- An interactive dashboard using **Streamlit**:
  - Visualize property prices by district.
  - Display the top-performing agencies by average price and activity.
  - Allow users to filter properties by type, district, or agency.
  - Hosted link or instructions to run locally.

## Project Structure (Example)

Riyadh_Aqar_Real_Estate_Analysis/
│
├── data_cleaning.ipynb               # Data cleaning and preprocessing code
├── insights_and_visualizations.ipynb  # EDA and visualizations
├── streamlit_dashboard/              # (Optional) Streamlit app folder
│   └── app.py                        # Streamlit dashboard
└── README.md                         # Project documentation

 ````
Riyadh_Aqar_Real_Estate_Analysis/
├── data/
│   ├── raw/             # Original data files
│   ├── processed/       # Cleaned and transformed data
├── notebooks/
│   ├── 01_data_collection.ipynb  # Data collection (if scraped)
│   ├── 02_data_cleaning.ipynb    # Data cleaning and preprocessing
│   ├── 03_insights.ipynb         # Insights and visualizations
├── deployment/          # Files for deployment (if applicable)
├── slides/              # Presentation slides (e.g., .pptx or .pdf)
├── requirements.txt     # Python dependencies
├── README.md            # Project overview and instructions
`````


## Team Members
- [Adwa Alshehri]
- [Abdulkarim Almalki]
- [Hadeel Almayalm]
- [Alawi Alalawi]



## Data Source
- Kaggel
- [kaggel >>.](https://www.kaggle.com/datasets/mohammedalsubaie/riyadh-real-estate)



## Tools and Libraries
- Python tools: pandas, numpy, matplotlib, seaborn, arabic.reshape, BIDI Algorithm 
- Deployment tools (optional): Streamlit, Power BI, etc



## Usage (Example)
1. Clone the repository:
   ```bash
   git clone [repo_url]
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run notebooks in the specified order:
   1. `01_data_collection.ipynb`
   2. `02_data_cleaning.ipynb`
   3. `03_insights.ipynb`



## Notes
- Emphasize collaboration and version control through GitHub.
- Use clear and consistent documentation.
- Optional deployment adds significant value to the project.
