# 🍽️ Restaurant Market Analysis using Web Scraping & Exploratory Data Analysis

## 📌 Project Overview

This project focuses on **collecting restaurant data from an online platform using web scraping and performing Exploratory Data Analysis (EDA)** to understand market trends, pricing patterns, and restaurant distribution.

The main objective is to demonstrate how **real-world data can be collected from websites and analyzed using Python to extract meaningful insights**.

This project showcases skills in:

* Web Scraping
* Data Cleaning
* Data Analysis
* Data Visualization

It is designed as a **portfolio-ready Data Analytics project** that demonstrates an end-to-end workflow from **data collection to insights generation**.

---

# 🎯 Objective

The primary objectives of this project are:

* Scrape restaurant data from a live website
* Clean and preprocess the collected data
* Perform exploratory data analysis
* Identify patterns in restaurant pricing and ratings
* Visualize insights using charts and graphs

---

# ❗ Problem Statement

Restaurant platforms contain large amounts of valuable data such as:

* Restaurant names
* Locations
* Dining times
* Prices
* Ratings

However, this data is not always available in structured datasets.

The challenge is to:

1. Extract restaurant information from websites.
2. Convert the scraped data into a structured dataset.
3. Perform analysis to identify useful business insights.

---

# 🌐 Data Collection

The data was collected using **Web Scraping techniques**.

### Steps followed:

1. Send request to the website using `requests`
2. Parse the HTML using `BeautifulSoup`
3. Extract relevant information such as:

   * Restaurant Name
   * Location
   * Dining Time
   * Price
   * Rating
4. Store the extracted data in lists
5. Convert the lists into a **Pandas DataFrame**

---

# 🛠️ Technologies Used

| Tool             | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming Language      |
| Requests         | Sending HTTP requests     |
| BeautifulSoup    | HTML parsing              |
| Pandas           | Data manipulation         |
| NumPy            | Numerical operations      |
| Matplotlib       | Data visualization        |
| Seaborn          | Statistical visualization |
| Jupyter Notebook | Development environment   |

---

# 📂 Project Structure

```
Restaurant-Market-Analysis
│
├── Restaurant_analysis(webscraping).ipynb
│
├── README.md
│
└── dataset (generated after scraping)
```

---

# 🔎 Data Cleaning

After scraping the data, the following preprocessing steps were performed:

* Handling missing values
* Removing unwanted characters
* Converting data types (Type Casting)
* Standardizing text values
* Preparing the dataset for analysis

---

# 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand patterns in the restaurant data.

### Types of Analysis Performed

### 1️⃣ Univariate Analysis

Analysis of individual variables such as:

* Restaurant pricing
* Ratings distribution
* Dining options

Visualization methods used:

* Bar Charts
* Histograms
* Count Plots

---

### 2️⃣ Bivariate Analysis

Analysis of relationships between variables such as:

* Price vs Ratings
* Location vs Restaurant availability
* Dining time vs restaurant distribution

Visualization methods used:

* Box plots
* Scatter plots
* Bar charts

---

# 📈 Key Insights

Some of the major insights observed from the analysis:

* Certain locations have **higher restaurant density**
* Restaurants with **moderate pricing tend to receive better ratings**
* Lunch dining options are **more commonly available**
* Some premium restaurants have **significantly higher pricing**

These insights help understand **restaurant market trends**.

---

# 🚀 How to Run This Project

### Step 1

Clone the repository

```bash
git clone https://github.com/yourusername/Restaurant-Market-Analysis.git
```

### Step 2

Navigate to the project folder

```bash
cd Restaurant-Market-Analysis
```

### Step 3

Install required libraries

```bash
pip install pandas numpy matplotlib seaborn beautifulsoup4 requests
```

### Step 4

Run the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Restaurant_analysis(webscraping).ipynb
```

---

# 💼 Skills Demonstrated

This project demonstrates the following **data analytics skills**:

* Web Scraping
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Python Programming
* Real-world dataset creation

---

# 📌 Future Improvements

Possible enhancements for this project:

* Scrape data from multiple restaurant platforms
* Add restaurant reviews analysis
* Build an interactive dashboard
* Automate daily data collection

---

# 👨‍💻 Author

**Mohammad Sohel**

Aspiring **Data Analyst / Data Scientist**

Skills:

* Python
* SQL
* Data Analysis
* Web Scraping
* Data Visualization

---

⭐ If you found this project helpful, consider **starring the repository**.

---
