# 🧠 Data Analysis and Model Development Using Python (IBM Coursera Project)

This repository contains my practical lab work and mini-projects completed as part of the **IBM Data Analysis with Python** course on Coursera.  

It demonstrates real-world **data analysis and machine learning techniques** using Python — covering **data wrangling**, **exploratory data analysis (EDA)**, **visualization**, and **predictive model development** for both car and laptop pricing datasets.

---

## 📚 Completed Modules

### 🧹 1. Data Wrangling
**Estimated time:** 30 minutes  
**Objective:** Clean, transform, and prepare raw data for analysis.  

**Key Skills:**
- Handle missing values (imputation, dropping, or replacement)  
- Correct data types for numerical and categorical variables  
- Apply **standardization** and **normalization** techniques  
- Use **binning** to group data and visualize distributions  
- Convert **categorical variables** into **indicator (dummy) variables**  

**Libraries used:**  
`pandas`, `numpy`, `matplotlib`  

**Notebook:**  
`notebooks/01_laptop_data_wrangling.ipynb`

---

### 🔍 2. Exploratory Data Analysis (Automobile Dataset)
**Estimated time:** 30 minutes  
**Objective:** Explore automotive features and analyze how different attributes affect car price.  

**Key Skills:**
- Perform descriptive statistical analysis  
- Visualize feature relationships using scatter plots and boxplots  
- Create **pivot tables** and **grouped summaries**  
- Identify correlations between independent variables and price  

**Libraries used:**  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`  

**Notebook:**  
`notebooks/02_Car_price_EDA.ipynb`

---

### 💻 3. Exploratory Data Analysis (Laptop Pricing Dataset)
**Estimated time:** 45 minutes  
**Objective:** Explore relationships between laptop specifications and price.  

**Key Skills:**
- Visualize feature distributions and categorical effects on price  
- Analyze patterns using **pivot tables** and **group-by** operations  
- Compute **Pearson correlation coefficients** to study dependencies  
- Identify features with the greatest influence on pricing  

**Libraries used:**  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`  

**Notebook:**  
`notebooks/03_Laptop_pricing_EDA.ipynb`

---

### 🤖 4. Model Development (Laptops)
**Estimated time:** 45 minutes  
**Objective:** Develop and evaluate regression models to predict laptop prices.  

**Key Skills:**
- Build **Multiple Linear Regression** models  
- Apply **Polynomial Regression** and **Ridge Regression**  
- Perform **train/test splits** and **cross-validation**  
- Evaluate models using **R² score** and **Mean Squared Error (MSE)**  

**Libraries used:**  
`scikit-learn`, `pandas`, `numpy`, `matplotlib`  

**Notebook:**  
`notebooks/04_Laptop_Model_development.ipynb`

---

### 🚗 5. Model Development (Cars)
**Estimated time:** 45 minutes  
**Objective:** Develop predictive models for automobile pricing.  

**Key Skills:**
- Train and test regression models using car dataset  
- Measure accuracy using **R²**, **MAE**, and **MSE**  
- Compare multiple regression techniques  
- Visualize predicted vs actual prices  

**Libraries used:**  
`scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`  

**Notebook:**  
`notebooks/05_Car_Model_Development.ipynb`

---

## 📊 Insights Summary

- **EDA Insights:**
  - Car *engine size* and *horsepower* show strong correlation with price.  
  - In laptops, *RAM*, *processor type*, and *brand* significantly influence pricing.  
  - Outlier detection improved accuracy of correlation analysis.

- **Modeling Insights:**
  - **Multiple Linear Regression** gave reliable baseline results.  
  - **Polynomial Regression** improved model fit for non-linear relationships.  
  - **Ridge Regression** reduced overfitting and stabilized performance.  
  - Best models achieved **R² ≈ 0.85–0.88**, showing strong predictive capability.

---

## 📂 Repository Structure

data-analysis-python-ibm/
│
├── data/
│ ├── laptops.csv
│ ├── usedcars.csv
│ └── laptops_model_dev.csv
│
├── notebooks/
│ ├── 01_laptop_data_wrangling.ipynb
│ ├── 02_Car_price_EDA.ipynb
│ ├── 03_Laptop_pricing_EDA.ipynb
│ ├── 04_Laptop_Model_development.ipynb
│ └── 05_Car_Model_Development.ipynb
│
├── requirements.txt
├── LICENSE
├── .gitignore
└── README.md


---

## ⚙️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/lokeshbollada/data-analysis-python-ibm.git
cd data-analysis-python-ibm

2️⃣ Create & activate virtual environment
python -m venv venv
.\venv\Scripts\activate   # Windows
# source venv/bin/activate  # macOS/Linux

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Launch Jupyter Lab
python -m jupyter lab


Then open any notebook from /notebooks/.

🧰 Tools & Libraries
Category	Tools
Data Wrangling	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Statistical Analysis	SciPy
Model Development	Scikit-learn
Environment	JupyterLab, Python 3.12
🪪 License

This project is licensed under the MIT License
.

🌟 Acknowledgment

Developed as part of the IBM Data Analysis Using Python (Coursera) certification.
Datasets are provided by IBM Skills Network and used solely for educational and research purposes.


---

## ✅ What to Do Next

1. Open `README.md` in VS Code or your text editor.  
2. Replace **all content** with the version above.  
3. Save the file.  
4. Then run these commands:

```powershell
git add README.md
git commit -m "docs: finalize README with model development and insights"
git push