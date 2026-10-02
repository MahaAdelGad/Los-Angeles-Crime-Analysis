# Los Angeles Crime Analysis

An end-to-end data analytics project analyzing a large, real-world Los Angeles crime dataset. This project uses Python for data cleaning and Exploratory Data Analysis (EDA), followed by an interactive Power BI dashboard to visualize the findings. Completed during Week 3 of the NTI × ITIDA Advanced Data Analytics Internship.

### 🛠️ Tech Stack & Tools
* **Python:** Pandas, Matplotlib, Seaborn (Data cleaning, EDA, statistical visualization)
* **Microsoft Power BI:** Interactive dashboard design and dynamic filtering
* **Analytical Techniques:** IQR-based outlier detection, data binning, categorical mapping

---

## 📊 Dashboard & Exploratory Visualizations

<img width="1221" height="701" alt="Crime Frequency by Area - barh chart" src="https://github.com/user-attachments/assets/c5dc6e09-35be-404d-89a7-8ba8199eff0e" />
<img width="1178" height="701" alt="Crime Frequency by Hour - bar chart" src="https://github.com/user-attachments/assets/57906acb-7537-47d5-ac02-705dee93d5ab" />
<img width="1178" height="701" alt="Victim Age Distribution - hist" src="https://github.com/user-attachments/assets/22db3208-3b6d-47c3-969d-388ccca12b32" />
<img width="1109" height="701" alt="Outlier Detection - box plot of victim age" src="https://github.com/user-attachments/assets/27802cc2-4643-4edc-aa49-9f8a2b8992e3" />
<img width="1161" height="657" alt="Dashboard" src="https://github.com/user-attachments/assets/979d8366-de56-4e0a-b40e-c6eb773b7501" />

---

## 🔍 Data Processing & Workflow

* **Data Cleaning (Python/Pandas):** Handled duplicate records and null values to prepare the messy raw dataset for analysis.
* **Feature Engineering:** Formatted complex temporal data (timestamps), mapped ethnicity codes to readable demographic categories, and binned continuous age data into specific age groups.
* **Outlier Detection:** Applied Interquartile Range (IQR) statistical methods to detect and handle anomalies within the dataset.
* **Statistical Analysis:** Used Matplotlib and Seaborn to uncover trends and answer specific project requirements regarding crime distribution.
* **Interactive BI Dashboard:** Built a dynamic Power BI report featuring slicers for **Year**, **Victim Sex**, **Age Group**, and **Ethnicity**. This allowed for deep-dive filtering into how crime is distributed across time, demographics, and geography.

## 💡 Key Findings & Surprising Insights
Through the EDA process, the data revealed several unexpected patterns:
* ⚠️ **Crime peaks exactly at noon** — contrasting with the common assumption that most crimes occur late at night.
* 📈 **June records nearly double** the crime volume compared to an average month in the dataset.
* 🎯 **Victims aged 26–34** are the most frequently targeted demographic by a significant margin.
