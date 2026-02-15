# Apple iOS App Store EDA 📱📊

A comprehensive **Exploratory Data Analysis (EDA)** on 10,000+ Apple iOS apps using Python, Pandas, Plotly, Seaborn, and Matplotlib to uncover insights about the iOS app ecosystem, user engagement, pricing strategies, and content trends.

---

## 🌟 Features

### Core Features
- **Data Cleaning & Preprocessing:** Handling missing values, duplicates, feature engineering (e.g., size conversion to MB), and type conversions.
- **Statistical Insights:** Summary statistics, distribution analysis, and outlier detection.
- **Genre & Rating Analysis:** Visualizations to understand which genres perform best in terms of ratings and engagement.
- **User Engagement Analysis:** Insights on total ratings, current version ratings, and user satisfaction trends.
- **Pricing & Monetization Insights:** Analysis of Free vs Paid apps, pricing distribution, and rating impact.
- **Device & Language Analysis:** Understanding supported devices, multilingual reach, and screenshot optimization.
- **Visualization:** Interactive and static plots using Plotly, Seaborn, and Matplotlib.

---

## 🗂 Project Structure

The project folder is organized as follows:

```text
Apple_iOS_App_Store_EDA/
├── AppleStore.csv                     # Dataset of 10k Apple iOS apps
├── Apple_iOS_App_Store_EDA.ipynb      # Jupyter Notebook with full EDA
├── requirements.txt                   # Python dependencies
└── venv/                              # Virtual environment
```

---

## 🏗️ EDA Architecture

```text
+----------------------+  
|      DATA LAYER      |  
|  Raw iOS app dataset |  
|  (CSV)               |  
+----------+-----------+  
           ↓  
+----------------------------+  
|  ANALYSIS LAYER            |  
|  - Data Cleaning           |  
|  - Statistical Insights    |  
|  - Genre & Rating Analysis |  
|  - User Engagement         |  
|  - Pricing & Monetization  |  
|  - Device & Language Scope |  
+----------+-----------------+  
           ↓  
+----------------------------------------+  
| VISUALIZATION LAYER                    |  
|  - Interactive Dashboards (Plotly)     |  
|  - Static Plots (Seaborn & Matplotlib) |  
|  - Scatter, Bar, Boxplots, Heatmaps    |  
+----------------------------------------+  

```

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Data Source:** [Kaggle – Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

---

## 📊 Dataset Overview

- **Rows:** 7200 apps  
- **Columns include:** id, track_name, size_bytes, price, rating_count_tot, rating_count_ver, user_rating, user_rating_ver, ver, cont_rating, prime_genre, sup_devices.num, ipadSc_urls.num, lang.num, size_mb, Type.

**Context:**  
The Apple App Store is one of the largest digital marketplaces globally. This dataset provides structured insights into app pricing, ratings, device compatibility, content restrictions, and multilingual strategies within the iOS ecosystem.

**Acknowledgements:**  
- Data sourced from Apple App Store via Kaggle.
- Thanks to Kaggle contributors for making this dataset publicly available.

**Inspiration:**  
Understanding iOS app performance patterns helps developers, product managers, and data analysts make strategic decisions around pricing, user engagement, and global reach.

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/TejasMJ/Google-Play-Store-App-EDA-.git
cd Google-Play-Store-App-EDA-
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```
### 3. Activate Virtual Environment
#### Windows:
```bash
.\venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```
### 5. Run Notebook

```bash
jupyter notebook
```

# 📊 App Analysis Project

## Detailed Analysis Scope

### Data Cleaning & Preprocessing
- Remove duplicates
- Convert size_bytes to size_mb

### Statistical Insights
- Summary statistics (mean, median, standard deviation)
- Distribution analysis for user_rating, price, and size_mb
- Outlier detection for pricing and rating counts

### Pricing & Revenue Insights
- Free vs Paid apps distribution
- Price analysis and trends
- Paid apps with highest installs

### Visualization
- Interactive dashboards using **Plotly**
- Static plots using **Seaborn** & **Matplotlib**

## 👨‍💻 Author
**Tejas Jadhav**  

- GitHub: [@tejas-jadhav](https://github.com/TejasMJ)  
- LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-m-jadhav/)
