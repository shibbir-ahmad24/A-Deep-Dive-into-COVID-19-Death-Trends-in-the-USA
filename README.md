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

- Loaded the dataset into a suitable data structure for analysis.

**Data Exploration:**

- Checked data shape to understand its structure.
- Assessed missing and duplicate values to ensure data quality.

**Data Cleaning:**

- Dropped unnecessary columns to streamline the dataset.
- Removed null values to maintain data integrity.

**Data Wrangling:**

- Added new columns for each desired year, summing values from respective date columns.
- Dropped original date columns after data aggregation.

**Data Analysis:**

- Conducted descriptive statistics to summarize data.
- Created a correlation matrix heatmap to identify relationships between the features.


### **Impact:**

**Enhanced Public Health Understanding**
- Provides insights into COVID-19 death trends, aiding health officials in identifying vulnerable regions.

**Data-Driven Decision Making**
- Empowers stakeholders to formulate effective strategies for virus mitigation and response.
  
**Resource Allocation Optimization**
- Enables targeted resource distribution to high-risk areas for effective public health measures.

**Informed Community Engagement**
- Supports community leaders in communicating risks and preventive measures to the public.

**Contribution to Knowledge**
- Advances academic understanding and serves as a blueprint for future public health data analyses.


### **Dataset Source:**
- [CSSE COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports_us)

### **Data:**

The dataset encompasses daily death case records spanning from 2020 to 2023, featuring essential fields such as:

- UID: Unique Identifier for each entry.
- ISO2/ISO3: Country name and acronym.
- FIPS: Unique identifier for counties within the USA.
- Admin2: County name.
- Population: Population of the specific county in the US.

### **Programming Language & Libraries:**
- Python

### **Libraries:**

To install the required libraries, we can use pip. Run the following commands in the terminal:
- pip install numpy pandas matplotlib seaborn

These libraries are essential for data manipulation, statistical analysis, and visualization.

### **Analysis Visuals:**
-
- Each county is represented by a bubble; size and color indicate death count.
-
- Visualization highlights states with the highest death cases, including New York and New Jersey.
-
- Highlights states like Arizona and California with the highest averages.
-
- Double-clicking on a state shows a histogram representing average COVID-19 deaths across counties.
-
- Displays top counties in New York with the highest death rates.
-
- Clickable map showing death counts for cities within selected states.
- 
- Visualizes the percentage of COVID-19 deaths by state for the year 2022.


### **Summary of Insights:**

- COVID-19 death counts showed significant variability across counties in 2021, influenced by factors like population density and healthcare infrastructure.
- In 2020, deaths varied by state, reflecting the effectiveness of public health responses.
- Average death rates per state in 2022 indicate ongoing pandemic challenges.
- Identifying counties with the highest death rates aids in understanding containment difficulties.
- City-level analysis offers insights into localized transmission patterns and helps target interventions.


