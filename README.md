# WORK SAMPLES
Medical-device-maintenance-analytics
A complete analytics and visualization project designed to support hospital  Biomedical Engineering and Health Informatics teams.
This dashboard analyzes:
- Equipment downtime
- Preventive maintenance compliance
- Common failure patterns
- Work order response times
- Inventory utilization
- Predictive failure risk (Machine Learning)

This project combines Biomedical Engineering knowledge with modern Health 
Informatics and analytics skills (Python, SQL, ML, Streamlit).

Features

Data Preprocessing
- Cleaning of maintenance logs  
- Categorization of device types  
- Time-series formatting for PM scheduling  

Analytics & KPIs
- Downtime per device  
- Mean Time Between Failure (MTBF)  
- Mean Time To Repair (MTTR)  
- Preventive maintenance compliance %  
- Work order aging report  

Machine Learning Model
A predictive model using:
- Random Forest  
- Logistic Regression  
- Feature importance (SHAP)  

Predicts:
- High-risk devices likely to fail in the next 30 days.

Interactive Dashboard (Streamlit)
Visualizes:
- Failure trends  
- Maintenance KPIs  
- Device risk scores  
- Inventory summaries  


Technologies Used

- Python (Pandas, NumPy, Scikit-learn)
- Streamlit (Dashboard)
- Plotly (Interactive Charts)
- SQL (optional)
- Jupyter Notebooks
- SHAP (Model Explainability)

data/ → Sample datasets
notebooks/ → Exploratory notebooks
src/ → Core analytics and ML code
app/ → Streamlit dashboard

How to Run the Dashboard

Install dependencies:

Run the Streamlit app:


Example KPIs Included
- PM Compliance %
- Avg Downtime (hrs)
- MTTR (hours)
- Total Work Orders
- Failure Probability %


Future Enhancements
- FHIR integration for health system compatibility  
- Database integration (PostgreSQL)  
- Automated PDF maintenance reports  
- API for hospital CMMS system  

Author
George Erasto Maleko  
Biomedical Engineer | Health Informatics  

