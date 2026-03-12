# PhonePe
# 📊 PhonePe Transaction & Demographic Data Analysis

## 📌 Project Overview

This project analyzes transaction data from the PhonePe digital payment platform along with demographic data across states and districts in India. The objective of this analysis is to identify transaction trends, understand device usage patterns, explore demographic relationships, and generate meaningful insights from the data.

Using Python and data visualization techniques, the analysis explores digital payment adoption across different regions and time periods.

---

## 📂 Dataset Description

The dataset consists of multiple sheets in an Excel file containing transaction and demographic data.

### 1️⃣ State_Txn and Users
State-level transaction and user information.

Columns include:
- State
- Year
- Quarter
- Transactions
- Amount (INR)
- ATV (Average Transaction Value)
- Registered Users
- App Opens

---

### 2️⃣ State_TxnSplit
Breakdown of different transaction types at the state level.

Columns include:
- State
- Year
- Quarter
- Transaction Type
- Transactions
- Amount (INR)
- ATV (INR)

---

### 3️⃣ State_DeviceData
Information about device brands used by registered users.

Columns include:
- State
- Year
- Quarter
- Brand
- Registered Users
- Percentage

---

### 4️⃣ District_Txn and Users
District-level transaction and user data.

Columns include:
- State
- District
- Code
- Year
- Quarter
- Transactions
- Amount (INR)
- ATV (INR)
- Registered Users
- App Opens

---

### 5️⃣ District Demographics
Demographic information for each district.

Columns include:
- State
- District
- Headquarters
- Population
- Area (sq km)
- Density
- Code
- Alternate Name

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  
- GitHub  

---

## 🔍 Data Analysis Steps

### 1️⃣ Data Loading
- Loaded datasets from Excel using **Pandas**
- Stored each sheet into separate DataFrames

### 2️⃣ Data Understanding
- Displayed dataset structure using:
  - `.head()`
  - `.tail()`
  - `.info()`

### 3️⃣ Data Exploration
- Generated **summary statistics** (mean, median, std)
- Checked **data types**
- Identified **missing values**
- Calculated **percentage of missing values**

---

## 📈 Exploratory Data Analysis

### State & District Analysis
- Calculated total number of states and districts
- Identified state with highest number of districts

### Transaction Analysis
- Calculated total transactions and transaction amounts by state
- Identified **top 5 states with highest transaction volumes**
- Identified **top 5 states with lowest transaction volumes**

### Transaction Type Analysis
- Determined most frequent transaction type for each state and quarter

### Device Usage Analysis
- Identified the device brand with the highest number of registered users in each state

### Demographic Analysis
- Identified district with highest population for each state
- Analyzed population density distribution across districts

---

## 📊 Data Visualizations

Several visualizations were created to identify patterns in the data.

### Transaction Trends
Line plots showing:
- Transaction growth across years
- Quarterly transaction trends

### App Usage Trends
Line plots showing:
- App opens over time for selected states

### Transaction Type Distribution
- Bar charts and pie charts showing distribution of transaction types

### Device Brand Distribution
- Bar charts showing device brand usage ratio across states

### Population Density Analysis
- Bar plots comparing population density of districts

---

## 🔗 Data Integration & Advanced Analysis

### District Mapping
- Identified unique district name and district code mappings
- Exported mappings to a CSV file

### State-Level Aggregation
Aggregated district data to calculate:
- Total transactions
- Total transaction amount
- Total registered users for each state

### User to Population Ratio
Merged transaction and demographic datasets to calculate:

Registered Users / Population ratio for each state.

### Correlation Analysis
Calculated correlation between:
- Population Density
- Transaction Volume

The correlation was very weak, indicating population density alone does not strongly influence transaction activity.

---

## 🔑 Key Insights

- Digital payment transactions have increased significantly over the years.
- Merchant payments and peer-to-peer transfers dominate transaction activity.
- A few smartphone brands account for the majority of registered users.
- Population density shows weak correlation with transaction volume.
- Digital payment adoption varies significantly across states.

---

## 💡 Recommendations

- Increase digital literacy programs in low-transaction regions.
- Improve internet and digital infrastructure in rural districts.
- Encourage merchant onboarding to increase transaction volume.
- Optimize the application for commonly used smartphone brands.

---

## 📌 Conclusion

This analysis highlights the growth of digital payments in India and demonstrates how transaction trends, device usage, and demographic factors interact within the PhonePe ecosystem. The insights can help identify opportunities to improve digital payment adoption across different regions.

---

## 👩‍💻 Author

**Anusha**
**Data Analyst**
