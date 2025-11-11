# 🌍 World Happiness Report — Exploratory Data Analysis (EDA) 📊  

Understanding what makes people happy around the world — through the power of data.  

---

## 🧠 Overview  

This project is a **comprehensive exploratory data analysis (EDA)** of the **World Happiness Report** dataset from [Kaggle](https://www.kaggle.com/). The dataset captures how different social and economic factors influence happiness across countries and years.  

My goal was to explore the data, clean it, visualize relationships, and discover key insights about what truly contributes to global happiness.  

---

## 📦 Dataset Details  

The dataset includes:  

| Feature | Description |
|----------|-------------|
| 🌍 Country/Region | The name of each country or region |
| 📅 Year | The year of observation |
| 😀 Happiness Score | Overall measure of happiness |
| 💰 GDP per Capita | Wealth and economic prosperity |
| 🤝 Social Support | Level of community and family support |
| ❤️ Healthy Life Expectancy | Average life expectancy in good health |
| 🕊️ Freedom to Make Life Choices | Sense of personal freedom |
| 🎁 Generosity | Charitable behavior among citizens |
| ⚖️ Perceptions of Corruption | Trust in public institutions |

---

## 🚀 My EDA Journey  

To achieve clean and meaningful insights, I followed a structured EDA process step by step 👇  

### 1️⃣ Importing Libraries  
I began by importing key Python libraries such as **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** — my core toolkit for handling, cleaning, and visualizing the dataset.  

### 2️⃣ Loading the Dataset  
Next, I loaded the dataset into a pandas DataFrame and explored it using `head()`, `info()`, and `describe()` to understand the data types, ranges, and structure.  

### 3️⃣ Sanity Check  
I ensured all columns were properly loaded, checked the dataset’s shape, verified data types, and made sure there were no inconsistencies or duplicates.  

### 4️⃣ Finding Missing Values  
Missing values can distort results. I checked for null values using `isnull().sum()` and handled them appropriately through imputation or removal.  

### 5️⃣ Detecting and Fixing Outliers  
Outliers in numerical columns like **GDP per Capita** and **Generosity** were identified using boxplots. I then applied **IQR capping** and **log transformation** techniques to smooth their effect without losing valuable data.  

### 6️⃣ Correlation Analysis  
I plotted a **correlation heatmap** using Seaborn to visualize the relationships between variables. The results showed strong positive correlations between **Happiness Score**, **GDP per Capita**, **Social Support**, and **Healthy Life Expectancy**.  

### 7️⃣ Key Feature Exploration  
After identifying important features, I performed deeper analysis using scatter plots and pairplots. It became evident that wealth and social connections go hand-in-hand with happier societies.  

### 8️⃣ Univariate, Bivariate & Multivariate Analysis  
- **Univariate:** Examined the distribution of individual features (like Happiness Score).  
- **Bivariate:** Studied two-variable relationships (e.g., GDP vs Happiness).  
- **Multivariate:** Explored combined effects of multiple variables on Happiness Score.  

---

## 💡 Key Insights  

✨ Countries with higher **GDP per Capita**, **Social Support**, and **Healthy Life Expectancy** tend to have significantly higher happiness scores.  
✨ **Freedom to Make Life Choices** and **lower perception of corruption** are also important happiness indicators.  
✨ Happiness is not purely economic — trust, freedom, and health play equally crucial roles.  

---

## 📊 Visual Storytelling  

During the EDA, several visuals helped uncover insights:  

- 🔥 **Heatmap** — Correlation between all key features  
- 📦 **Boxplots** — Outlier detection and correction  
- 📈 **Pairplots** — Relationship between GDP, support, and happiness  
- 🌐 **Bar Charts** — Happiness trends by country and year  

*(You can find all visuals in the `/images` folder or within the notebook)*  

---

## 🛠️ Tools & Libraries  

- 🐍 **Python**  
- 📘 **Pandas**, **NumPy**  
- 📊 **Matplotlib**, **Seaborn**  
- 🧮 **Jupyter Notebook / Google Colab**  

---
