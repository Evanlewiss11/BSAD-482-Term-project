

1. ### **Data Wrangling Summary – Global Sea Level Rise Dataset**

1. **Removed Unnecessary Columns**

   * Deleted extra columns that were not relevant to the analysis, such as metadata or redundant values.  
   * Kept only the necessary columns: **Year** and **Sea Level Change (mm from 1993–2008 average)**.  
2. **Renamed Columns for Clarity**

   * Changed "mm from 1993-2008 average" to "Sea Level Change (mm)" to make it easier to understand.  
   * Ensured column names were simple and intuitive for visualization.  
3. **Removed Missing and Duplicate Data**

   * Checked for and removed rows where sea level data was missing.  
   * Removed duplicate records to ensure accuracy.  
4. **Standardized Data Types**

   * Converted "Year" to an **integer** format.  
   * Ensured "Sea Level Change (mm)" was stored as a **numeric** value to avoid formatting issues.

### **2\. Data Wrangling Summary –  Severe Weather**

1. **Removed Unnecessary Columns**

   * Deleted extra columns that were not relevant to the analysis, such as metadata or redundant values.  
   * Kept only the necessary columns: **Year, Tornadoes and Fatalities.**

   

2. **Removed Missing and Duplicate Data**

   * Checked for and removed rows where severe weather data was missing.  
   * Removed duplicate records to ensure accuracy.

3. ### **Data Wrangling Summary – Yearly C02 Admissions** 

1. **Removed Unnecessary Columns**

   * Deleted extra columns that were not relevant to the analysis, such as metadata or redundant values.  
   * Kept only the necessary columns: **Year** and **Entity and annual co2 emissions**  
       
2. **Removed Missing and Duplicate Data**

   * Checked for and removed rows where c02 emission data was missing.  
   * Removed duplicate records to ensure accuracy.

	**4\. Data Wrangling Summary – Renewable Energy**					

1. **Removed Unnecessary Columns**  
   * Deleted extra columns that were not relevant to the analysis, such as metadata or redundant values.  
   * Kept only the necessary columns: **Year** and **Entity and Energy renewables**  
       
2. **Removed Missing and Duplicate Data**

   * Checked for and removed rows where energy renewable data was missing.  
   * Removed duplicate records to ensure accuracy.

   ### **5\. Data Wrangling Summary – Global Temperature Anomalies vs. CO₂ Emissions Dataset**

1. **Removed Unnecessary Columns**

   * In the **CO₂ dataset**, removed columns unrelated to total emissions, such as:  
     * Country-specific CO₂ values  
     * Other greenhouse gases (methane, nitrous oxide, etc.)  
     * Energy consumption details not relevant to CO₂  
   * In the **Temperature Anomalies dataset**, kept only **Year** and **Global Temperature Anomaly (°C)**.  
2. **Renamed Columns for Clarity**

   * `"J-D"` (January–December temperature anomaly) → **"Global Temperature Anomaly (°C)"**  
   * `"year"` → **"Year"** to match formats between both datasets.  
   * `"co2"` → **"CO₂ Emissions (Million Metric Tons)"** to clarify the unit of measurement.  
3. **Filtered Data to Match Year Ranges**

   * **Kept only matching years** in both datasets.  
   * Removed any years in the CO₂ dataset that didn’t have a corresponding temperature anomaly.  
4. **Checked for Missing or Duplicate Values**

   * **Dropped any missing values** in either dataset to prevent errors in Tableau.  
   * **Removed duplicate records** that might have been included in either dataset.  
5. **Merged the Two Datasets**

   * **Joined the CO₂ and Temperature Anomalies datasets on `Year`** to create a combined dataset.  
   * Ensured that every row contained a **matching CO₂ value and temperature anomaly** for each year.

 


     

 


     

     