# 🖼️ Art Museum Visitors – First Pandas Data Analysis
*Simulated visitor data for Metropolitan & Guggenheim museums during and after COVID-19*

## 📌 Project Overview

This project demonstrates how to use the **Pandas** library and **Matplotlib** in a Jupyter Notebook to analyze simulated attendance data for two major New York art museums – **The Metropolitan Museum of Art** and **The Guggenheim Museum**.

The goal is to explore patterns in visitor demographics and behavior **before, during, and after the COVID-19 pandemic**.

---

## 🧪 Dataset Structure

The dataset includes the following fields:

| Column         | Description                            |
|----------------|----------------------------------------|
| `Visitor_ID`   | Unique visitor identifier              |
| `Age`          | Age of the visitor                     |
| `Gender`       | Gender category: Male / Female / Other |
| `Occupation`   | Profession of the visitor              |
| `Visit_Date`   | Date of the museum visit               |
| `Period`       | Pandemic period: Pre-COVID / During-COVID / Post-COVID |
| `Museum`       | Metropolitan or Guggenheim             |

*📝 Note: All data is fictitious and created for educational purposes.*

---

## ⚙️ Technologies Used

- 🐍 Python 3.x  
- 🧮 Pandas  
- 📊 Matplotlib  
- 📓 Jupyter Notebook  
- 💻 Git & GitHub

---

## 🔍 Key Steps in Analysis

### 1. 🧹 Data Loading & Inspection
- Load data from CSV
- Check shape, types, and missing values

### 2. 📊 Aggregations & Calculations
- Group visitors by pandemic period
- Calculate average age per period
- Analyze demographic trends

### 3. 📈 Visualization
- Create a **bar chart** to show changes in average age across COVID periods

---

## 📌 Insights & Conclusions

- The average age of visitors **decreased during the COVID period**, possibly due to travel limitations or safety concerns among older demographics.
- **Post-COVID attendance** appears to return to a broader age distribution.
- This analysis can support future strategies for cultural institutions in adapting outreach and programming to various visitor groups.

---

## 🧠 What I Learned

- Structuring data for analysis with **Pandas**
- Using `groupby()` and `.mean()` to extract insights
- Creating simple and meaningful **visualizations**
- Writing clean, readable **Jupyter Notebooks**
- Documenting a project clearly for public presentation

---

## 📎 Files Included

- `Project with Pandas in Jupyter Notebook.ipynb` – main notebook  
- (optional) `museum_visitors.csv` – dataset (if you want to include it)
- `README.md` – this documentation file  

---

## ✨ Next Steps (Ideas)

- Add more complex queries (e.g., visits by gender or occupation)
- Incorporate **Seaborn** for more sophisticated plots
- Add trendlines or multiple charts per museum
- Expand the dataset to include exhibition data

---

## 👩‍💻 Author

**Desislava Georgieva**  
🌍 Kyustendil, Bulgaria  
📫 desislava.strahilova.georgieva@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/desislava-s-georgieva)  
🔗 [GitHub Portfolio](https://github.com/DesislavaSGeorgieva)

---

## 📢 License

This project is for educational purposes only and is shared under the [MIT License](LICENSE).
