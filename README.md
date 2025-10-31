# Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

## Objective
Perform EDA on the Titanic dataset to extract insights using statistical and visual methods.

---

## Tools Used
- Python  
- Pandas, Matplotlib, Seaborn  
- Jupyter Notebook  

---

## Steps Performed
1. **Imported libraries** and **loaded dataset**.  
2. Checked dataset using `.info()`, `.describe()`, and `.value_counts()`.  
3. **Cleaned data**:
   - Filled missing `age` with median.  
   - Filled missing `embarked` and `embark_town` with mode.  
   - Dropped `deck` column.  
4. **Plotted visuals**:
   - Pairplot (`age`, `fare`, `pclass`, hue = `survived`)  
   - Heatmap (correlation matrix)  
   - Histograms, boxplots, and scatterplots.  
5. **Added observations** below each visual.  
6. **Created a summary PDF report** of findings.

---

## 🧾 Key Insights
- Females and 1st-class passengers had higher survival rates.  
- Higher fares were linked to better survival chances.  
- Adult males and 3rd-class passengers had lower survival rates.  

---

## 📁 Deliverables
- Jupyter Notebook  
- PDF Summary Report  

---


