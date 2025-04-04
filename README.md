# **AgriData Explorer: Unlocking Insights from Indian Agriculture with EDA** 🌾📊

## **Project Overview**  
**AgriData Explorer** is a comprehensive data analysis and visualization platform that aims to explore and visualize agricultural trends across India. By leveraging **Python**, **SQL**, and **Power BI**, this project provides insights into crop production, yields, cultivation areas, and growth trends, supporting farmers, policymakers, and researchers in making data-driven decisions.

### **Tech Stack**  
- **Python**: Pandas, Seaborn, Matplotlib, Plotly for data analysis and visualization  
- **SQL**: TiDB Cloud, MySQL, SQLAlchemy for efficient data management  
- **Power BI**: Real-time data visualization using ODBC integration  
- **Google Colab**: For data processing, cleaning, and preliminary analysis

---

## **Project Workflow**  

### **1️⃣ Data Acquisition & Cleaning**  
- **Dataset**: Downloaded agricultural data (Excel format) and stored it in **Google Drive** for easy access.  
- **Data Cleaning**:  
  - Loaded the data using **Pandas**.  
  - **Handled missing values**, **checked for duplicates**, and removed any **extra spaces** in the text fields.  
  - Renamed columns for clarity.  
  - Used **Seaborn** and **Matplotlib** to visualize and detect **outliers** (boxplots).  
  - Analyzed relationships between features using a **correlation heatmap**.  
- **Cleaned Dataset**: Saved the cleaned data and re-uploaded it to Google Drive for further analysis.  

---

### **2️⃣ Exploratory Data Analysis (EDA)**  
Conducted exploratory data analysis using various charts from matplotlib, searborn and plotly on key topics, such as:  
- **Rice and Wheat Production Trends**  
- **Oilseed and Sunflower Production**  
- **Sugarcane and Sorghum Production**  
- **Groundnut, Soybean, and Maize Production**  
- **Impact of Area Cultivated on Crop Yield**  
- **Rice and Wheat Yield Comparison**  

---

### **3️⃣ Database Creation & Querying**  
- **Database**: Created the **AGRI_DATA** database in **TiDB Cloud**.  
- **Migration**: Installed **MySQL** and **pymysql** in **Google Colab** and migrated the cleaned dataset to TiDB Cloud using **SQLAlchemy**. The table was named **CROP_DETAILS**.  
- **SQL Queries**:  
  - Executed **25 queries** to analyze key agricultural metrics.  
  - Results were displayed using **Tabulate** for improved readability and accessibility.  

---

### **4️⃣ Power BI Integration & Advanced Visualization**  
- **Connection**: Installed **Power BI Desktop** and connected to **TiDB Cloud** using **ODBC** for seamless data fetching.  
- **Data Import**: Imported results from **SQL queries** directly into Power BI.  
- **Visualization**: Created impactful visualizations including:  
  - **Bar Charts** for top producers of rice, wheat, oilseeds, and more  
  - **Pie Charts** for production distribution across states  
  - **Line Charts** for trends in production over time (e.g., Sugarcane, Rice vs. Wheat)  
  - **Scatter Plots** for relationship analysis (e.g., Area vs. Yield)  
  - **KPI Cards** highlighting key performance indicators for each crop  
  - **Stacked Bar Charts** for comparing multiple variables over time  

---

## **Key Achievements**  
- **Cleaned and Processed Data**: Thoroughly cleaned the agricultural dataset, making it ready for deep analysis.  
- **Comprehensive EDA**: Gained valuable insights on crop production trends, growth patterns, and correlations across states.  
- **Efficient Database Management**: Utilized **TiDB Cloud** for large-scale data storage and querying, ensuring smooth and fast data management.  
- **Powerful Data Visualizations**: Developed **interactive Power BI dashboards** to provide real-time insights into the Indian agricultural sector.
