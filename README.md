# Car Dataset EDA

This project performs **Exploratory Data Analysis (EDA)** on a car dataset.  
The goal is to clean, preprocess, and analyze the dataset to uncover meaningful insights and prepare it for further modeling.

---

## 📌 Key Steps in the Analysis

1. **Data Loading**
   - Reads the dataset (Excel file) using `pandas`.

2. **Data Cleaning**
   - Removing duplicates  
   - Handling missing values  
   - Outlier detection & treatment  

3. **Feature Engineering**
   - Normalization and scaling of numerical variables (`StandardScaler`)  
   - Encoding categorical variables (dummy variables / one-hot encoding)  

4. **Exploratory Analysis**
   - **Univariate analysis**: distributions of single variables  
   - **Bivariate analysis**: relationships between variables  
   - Visualization using `matplotlib` and `seaborn`

---

## 📂 Project Structure

```
EDA_Cars_Demo_blank.ipynb   # Main Jupyter Notebook
README.md                   # Project documentation
requirements.txt            # Python dependencies
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone <your-repo-link>
cd car-eda
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the notebook
```bash
jupyter notebook EDA_Cars_Demo_blank.ipynb
```

---

## 🛠 Requirements

- Python 3.8+
- Jupyter Notebook

See [`requirements.txt`](requirements.txt) for package details.

---

## 📊 Tools & Libraries

- **pandas** → data manipulation  
- **numpy** → numerical operations  
- **matplotlib, seaborn** → visualization  
- **scikit-learn** → scaling & preprocessing  
- **os** → file handling  

---

## ✨ Future Work

- Apply machine learning models for prediction  
- Automate preprocessing pipeline  
- Create an interactive dashboard for EDA insights  

---

## 📜 License

This project is open-source and available under the MIT License.
