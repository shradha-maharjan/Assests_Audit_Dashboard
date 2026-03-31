# Healthcare IT Asset Audit Dashboard
<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/e10cf64d-ecb5-4687-808c-a856cbb9d32a" />

## Project Overview
This project focuses on building a **Healthcare IT Asset Audit Dashboard** using Power BI to monitor asset utilization, lifecycle, and compliance risks. The dashboard simulates how IT auditors and operations teams analyze asset data to identify inefficiencies, reduce financial waste, and ensure proper asset management.

---

## Objective
The main goal of this project is to:
- Analyze IT and medical asset usage
- Identify underutilized (idle) assets
- Detect compliance risks (e.g., expired warranties)
- Monitor lifecycle status of assets
- Provide actionable insights for better asset management

---

## Business Context
Healthcare organizations rely on a wide range of IT and medical devices such as:
- Laptops and workstations
- Tablets and servers
- Medical devices (MRI, ECG, infusion pumps)

These assets:
- Handle sensitive patient data (HIPAA relevance)
- Impact patient care and operations
- Require proper tracking and lifecycle management

---

## Tools Used
- Power BI Desktop (data modeling and visualization)
- Power Query (data cleaning and transformation)
- DAX (calculated measures and KPIs)
- Python (for synthetic dataset generation)

---

## Dataset
A synthetic dataset of **3,000+ healthcare IT assets** was generated to simulate real-world conditions.

### Key Fields:
- asset_id
- asset_type
- department
- location
- status (In Use, Idle, In Stock, etc.)
- purchase_cost
- purchase_date
- last_used_date
- warranty_expiry
- expected_life_years
- criticality
- data_sensitivity

---

## Data Preparation
Data was cleaned and transformed using Power Query:

### Calculated Columns:
- **Idle Days** → Days since last usage
- **Warranty Status** → Active / Expired
- **Asset Age** → Age of asset in years
- **Lifecycle Status** → Within Life / Beyond Life

---

## Key Metrics (KPIs)
- Total Assets
- Idle Assets (> 60 days)
- Critical Idle Assets
- Expired Warranty Assets
- Unassigned Assets
- Idle Cost (financial impact)

---

## Dashboard Features

### Filters (Slicers)
- Department
- Location
- Asset Type
- Status

---

### Visualizations

#### 1. Asset Distribution
- Donut chart showing assets by type

#### 2. Asset Status Overview
- Bar chart showing asset status (In Use, Idle, etc.)

#### 3. Idle Assets by Department
- Identifies inefficiencies across departments

#### 4. Warranty Risk Analysis
- Highlights expired warranties by asset type

#### 5. Risk Detail Table
- Displays high-risk assets based on:
  - Idle days
  - Criticality
  - Warranty status
  - Lifecycle status

---

## Key Insights
- A significant number of assets are idle (>60 days), indicating underutilization
- Critical devices show inactivity, posing operational risks
- Several assets have expired warranties, increasing maintenance risk
- High-value assets contribute to financial waste when unused

---

## Business Impact
This dashboard enables organizations to:
- Reduce unnecessary costs
- Improve asset utilization
- Minimize operational risks
- Enhance compliance and control

---

## What This Project Demonstrates
- Data cleaning and transformation
- KPI design and business metrics
- Dashboard design and visualization
- Audit and risk analysis mindset
- Healthcare domain understanding

---

## How to Use
1. Open the `.pbix` file in Power BI Desktop
2. Use slicers to filter data
3. Analyze KPIs and charts
4. Investigate high-risk assets in the table

---

## Conclusion
This project simulates a real-world IT audit scenario by combining data analysis, visualization, and risk assessment to improve asset management in a healthcare environment.

