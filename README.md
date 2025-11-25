# Inpatient Hospital Charges – Tableau Project

This project analyzes inpatient hospital charges across the United States using a public dataset from CMS (via Kaggle). The goal is to explore how hospital billing varies by state and provider, and how billed charges compare to Medicare payments.

##  Dataset

- **Source:** Kaggle – "Inpatient Hospital Charges"
- **Key fields used:**
  - Provider State
  - Provider Name
  - DRG (Diagnosis-Related Group) Definition
  - Total Discharges
  - Average Covered Charges (Billed Charges)
  - Average Total Payments
  - Average Medicare Payments

##  Tableau Visualizations

The Tableau workbook (`hospital_charges_inpatients.twbx`) includes:

- Bar chart of **Average Hospital Charges by State**
- Ability to filter by state (interactive filter)
- Formatted currency values for easier comparison

##  What I Did

- Imported the Kaggle inpatient hospital charges dataset
- Cleaned the data (removed unused columns, standardized headers, ensured numeric formats)
- Built a bar chart in Tableau showing **average billed charges per state**
- Added filters and labels to make the visualization easy to read and interactive


##  Files

- `hospital_charges_inpatients.twbx` – Tableau packaged workbook
- `hospital_charges_clean.csv` – cleaned dataset used in Tableau
- `screenshot_dashboard.png` – preview of the dashboard
