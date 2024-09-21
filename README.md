# Unveiling Insights: A Deep Dive into COVID-19 Death Trends in USA

### **Problem:**

The COVID-19 pandemic has profoundly impacted public health across the globe, particularly in the USA. Understanding the trends in COVID-19 death cases is crucial for effective public health response and resource allocation. However, analyzing these trends presents significant challenges. Variability in death cases across counties and states complicates the identification of high-risk areas, while the need for data-driven insights remains paramount. This project seeks to illuminate these trends through a detailed analysis of daily death case records, enabling stakeholders to make informed decisions in their ongoing response to the pandemic.


### **Solution:**

This project employs a systematic approach to analyze COVID-19 death data through the following steps:

**Data Collection:**

- Gathered daily death case records from the CSSE COVID-19 dataset published by Johns Hopkins University.

**Import Necessary Libraries:**

- Utilized essential Python libraries to facilitate data manipulation and visualization.

**Data Load:**

- Load the dataset into a suitable data structure for analysis.

**Data Exploration:**

- Checked data shape to understand its structure.
- Assessed missing and duplicate values to ensure data quality.

**Data Cleaning:**

- Drop unnecessary columns to streamline the dataset.
- Remove null values to maintain data integrity.

**Data Wrangling:**

- Add new columns for each desired year, summing values from respective date columns.
- Drop original date columns after data aggregation.

**Data Analysis:**

- Conduct descriptive statistics to summarize data.
- Create a correlation matrix to identify relationships between the features.

**Impact**

•	Enhanced understanding of COVID-19 death trends across different regions.
•	Informed public health strategies by identifying high-risk areas and patterns.
•	Contributed to resource allocation and targeted interventions based on localized data.

