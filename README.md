# 🏥 Insurance Data Analysis 📊  

Welcome to the **Insurance Data Analysis Project**! 🚀  
This project explores the **insurance.csv** dataset to uncover insights about age, gender, BMI, smoking habits, and medical charges.  

---

## 📂 Dataset Overview  
The dataset contains **1338 records** and **7 features**:  

- 👤 `age` → Age of the individual  
- 🚻 `sex` → Gender (male/female)  
- ⚖️ `bmi` → Body Mass Index  
- 👶 `children` → Number of children/dependents  
- 🚬 `smoker` → Smoking status (yes/no)  
- 🌎 `region` → Residential region (northeast, northwest, southeast, southwest)  
- 💰 `charges` → Medical charges billed  

---

## 🔍 Key Explorations  
✔️ **Data Cleaning & Preprocessing**  
- Checked missing values (✅ none found)  
- Encoded categorical features (`sex`, `smoker`, `region`)  

✔️ **Statistical Summary**  
- 📊 Average Age: ~39 years  
- ⚖️ Average BMI: ~30.6  
- 👶 Average Children: ~1  
- 💰 Average Charges: ~$13,270  

✔️ **Visualizations**  
- 📈 Distribution plots for `age`, `bmi`, `charges`  
- 📊 Count plots for `sex`, `children`, `smoker`, `region`  
- 📦 Boxplots to detect outliers in `bmi`, `charges`  
- 📉 Line plots showing relation between `charges` and categorical variables  

---

## 🛠️ Tools & Libraries Used  
- 🐼 **Pandas** → Data manipulation  
- 🎨 **Seaborn & Matplotlib** → Visualization  
- 🤖 **Scikit-learn** → Label Encoding  

---

## 💡 Insights  
- 🚬 **Smokers pay significantly higher charges** compared to non-smokers.  
- 👨 vs 👩 **Gender has little effect** on charges.  
- ⚖️ **Higher BMI** individuals tend to have higher charges.  
- 🌎 **Region** has minor influence compared to smoking & BMI.  

---

## 🚀 Future Improvements  
- ✅ Build a **predictive model** (Linear Regression, Random Forest) to estimate charges.  
- ✅ Perform **feature importance analysis**.  
- ✅ Try advanced visualizations like heatmaps & pairplots.  

---

## 📌 How to Use  
1. Clone this repo  
2. Open `Untitled0.ipynb` in Jupyter/Colab  
3. Run cells step by step to explore dataset & plots  

---

## ✨ Author  
👨‍💻 **Ajay Nishad**  
📅 *Project Date: Sept 2025*  

---

⭐ If you like this project, don’t forget to give it a **star**! 🌟
