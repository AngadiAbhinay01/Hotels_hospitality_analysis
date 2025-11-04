# AtliQ Hotels Data Analysis Project  

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-blueviolet)
![Plotly](https://img.shields.io/badge/Interactive-Plotly-ff69b4)

---

## Overview  

This project analyzes **AtliQ Hotels' booking data** to uncover meaningful insights into business performance, customer behavior, and operational efficiency.  
Using Python’s data analysis libraries, we explore patterns in occupancy, revenue, and booking trends to support data-driven decision-making.  

The analysis is performed in a Jupyter Notebook

---

##  Table of Contents  

1. [ Introduction](#-introduction)  
2. [ Datasets](#-datasets)  
3. [ Tools & Technologies](#️-tools--technologies)  
4. [ Analysis Process](#-analysis-process)  
5. [ Key Insights](#-key-insights)  
6. [ How to Run](#-how-to-run)  
7. [ Visual Highlights](#-visual-highlights)  
8. [ Conclusion](#-conclusion)  
9. [ Author](#️-author)  

---

##  Introduction  

AtliQ Hotels, a fast-growing hospitality brand, aims to leverage its data to understand how bookings, platforms, and regions impact overall performance.  
This notebook performs **Exploratory Data Analysis (EDA)** and generates actionable insights to optimize operations and enhance profitability.

**Objectives:**  
- Analyze occupancy rates, revenue, and booking platforms.  
- Compare hotel performance across multiple cities and room categories.  
- Identify growth opportunities based on booking behavior.  

---

##  Datasets  

The project uses five CSV files stored in the `datasets/` folder:  

| File Name | Description |
|------------|-------------|
| `dim_date.csv` | Date information for time-based analysis |
| `dim_hotels.csv` | Hotel details and metadata |
| `dim_rooms.csv` | Room types and category data |
| `fact_aggregated_bookings.csv` | Summarized bookings and revenue data |
| `fact_bookings.csv` | Detailed transactional booking data |

---

##  Tools & Technologies  

- **Programming Language:** Python 
- **Libraries:**  
  - `pandas` – Data manipulation and cleaning  
  - `matplotlib` & `seaborn` – Static data visualization  
  - `plotly` – Interactive plots  
  - `numpy` – Numerical operations  
- **Environment:** Jupyter Notebook  

---

##  Analysis Process  

The notebook is structured as follows:  

1. ** Data Import & Cleaning**  
   - Loading multiple CSV files  
   - Handling missing values and data types  
2. ** Exploratory Data Analysis (EDA)**  
   - Understanding booking trends and room occupancy  
   - Platform and city-level performance comparison  
3. ** Visual Insights**  
   - Interactive graphs using Plotly  
   - Revenue and occupancy KPIs  


## Key Insights  

✅ Most bookings originate from a few dominant platforms.  
✅ Certain cities show higher occupancy and profitability.  
✅ Room category and season strongly influence booking behavior.  
✅ Aggregated data helps identify peak months and off-season dips.  

##  How to Run  
1. Clone this repository:
   git clone https://github.com/<your-username>/atliq-hotels-analysis.git
   cd atliq-hotels-analysis
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn plotly
3. Launch Jupyter Notebook:
   jupyter notebook EDA_Hospitality_analysis.ipynb

## Conclusion

1. Through this analysis, AtliQ Hotels gains a clear understanding of:
2. Key performance indicators driving revenue
3. Booking patterns across channels
4. Seasonal and regional variations

## Next Steps:
1. Incorporate machine learning to predict future occupancy.
2. Build dashboards using Power BI or Tableau.

## Author
Angadi Abhinay
Contact: [angadiabhinay2001@gmail.com]
LinkedIn: https://www.linkedin.com/in/abhinay-angadi-541004159/

