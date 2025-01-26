### REGIONAL-SALES-REPORT

# Introduction
The purpose of this report is to provide an analysis of regional sales performance based on demographic and job classification data. The goal is to identify trends and patterns across regions, age groups, job classifications, and gender, enabling stakeholders to make informed decisions to improve sales strategies and target specific market segments effectively.
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Step 1: Load the dataset
def load_data(file_path):
    """Loads the dataset into a pandas DataFrame."""
    try:
        data = pd.read_excel(C:\Users\ADMIN\OneDrive\Desktop\Bluesky\Excel practice doc)
        print("Data loaded successfully.")
        return data
    except Exception as e:
        print(f"Error loading data: {e}")
        return None
```
# Tools Used
This analysis was conducted using:

Excel: For initial data preparation, cleaning, and structuring.

Tableau: For creating an interactive dashboard that visually represents sales data across multiple dimensions and facilitates data-driven insights.

# Data Cleaning
Data cleaning involved the following steps:

Standardizing Regional Data: Ensured that all regional identifiers (England, Scotland, Wales, and Northern Ireland) were correctly categorized.

Validating Age Data: Checked for outliers and incomplete entries within the age distribution.

Consolidating Job Classifications: Mapped diverse job descriptions into three key categories—White Collar, Blue Collar, and Other.

Addressing Missing Values: Filled gaps in gender and sales figures using imputation methods or cross-referenced data from reliable sources.

# Data Visualization
The interactive dashboard created in Tableau highlights:https://public.tableau.com/app/profile/adaolisa.okafor/viz/Tableausprint2_17193610047820/Dashboard1

![image](https://github.com/user-attachments/assets/c6d47215-ac5e-42ee-9bc7-e5a62aca5e5f)
Regional Sales Performance

![image](https://github.com/user-attachments/assets/c6ea3a67-d758-4938-b03e-04dc2fe29738)
Sales by Age

![image](https://github.com/user-attachments/assets/9ad19e78-0341-47ab-9b48-b4118d3af208)
Sales by Job Description

![image](https://github.com/user-attachments/assets/2c8272b2-1d79-4c82-a4b5-663dcab71459)
Sales by Gender

# Results
Regional Dominance: England leads with 53% of total sales, followed by Scotland (28%), Wales (14%), and Northern Ireland (5%). England's strong sales performance underscores its potential as a key focus area for future campaigns.

Age and Sales Correlation: The 30–44 age group generates the highest sales, with declining sales observed in older age groups (50–65). The highest sales among the 30–44 demographic suggest targeting this segment for maximum impact.

Job Classification Insights: White-collar workers contribute 49% of sales, followed by Blue-collar (26%) and Other job classifications (25%). The near-equal distribution between White Collar and Other classifications highlights the need for diverse marketing approaches.

Gender Trends: Males account for 54% of total sales, while females contribute 46%. The gender balance suggests equitable sales opportunities across male and female audiences.

# Summary
The analysis highlights England as the leading region, with a significant share of sales driven by the 30–44 age group. White-collar job classifications dominate sales contributions, and both genders contribute almost equally to the overall performance.

To enhance sales further, resources should be concentrated on maintaining England’s lead while increasing efforts in Scotland to bridge the regional sales gap. Campaigns tailored to the 30–44 age group should be developed to capitalize on their spending power. Gender-inclusive marketing strategies that appeal equally to both genders can leverage their balanced sales contribution. 

Additionally, implementing distinct approaches for White-collar, Blue-collar, and Other job classifications will help diversify the customer base and broaden market reach.
