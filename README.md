````markdown
# 🎬 Netflix Content Trends Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on Netflix movies and TV shows to uncover trends and patterns in the platform's content library.

The analysis focuses on understanding content distribution, release trends, genres, ratings, countries, and other key attributes using Python-based data analysis and visualization techniques.

## 🎯 Objectives

- Analyze the distribution of Movies and TV Shows on Netflix.
- Identify trends in content releases over the years.
- Explore the most common genres and content categories.
- Analyze content distribution across countries.
- Study the distribution of ratings across Netflix titles.
- Identify patterns and trends that provide insights into Netflix's content strategy.
- Clean and preprocess the dataset before performing analysis.

## 🛠️ Technologies & Libraries

- **Python**
- **Pandas** – Data cleaning, transformation, and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Analysis and documentation

## 📊 Dataset

The project uses the **Netflix Titles Dataset**, containing information about movies and TV shows available on Netflix.

### 🔑 Key Features

- `show_id` – Unique identifier for each title
- `type` – Movie or TV Show
- `title` – Name of the content
- `director` – Director of the title
- `cast` – Cast members
- `country` – Country of production
- `date_added` – Date the title was added to Netflix
- `release_year` – Original release year
- `rating` – Content rating
- `duration` – Movie duration or number of TV show seasons
- `listed_in` – Genres/categories
- `description` – Content description

## 🔍 Analysis Performed

### 🧹 1. Data Cleaning & Preprocessing

- Identified and handled missing values.
- Checked for duplicate records.
- Converted columns into appropriate data types.
- Extracted useful information from date-related fields.
- Prepared categorical and numerical variables for analysis.

### 🎥 2. Content Type Analysis

Compared the number and proportion of:

- Movies
- TV Shows

to understand the overall composition of Netflix's content library.

### 📅 3. Release Year Analysis

Analyzed the distribution of titles across release years to identify:

- Growth in Netflix's content library
- Years with higher content production
- Changes in content availability over time

### 🎭 4. Genre Analysis

Analyzed Netflix categories to identify:

- Most common genres
- Popular content categories
- Distribution of genres across Movies and TV Shows

### 🌍 5. Country Analysis

Examined country-wise content distribution to identify major contributors to Netflix's content library.

### ⭐ 6. Rating Analysis

Studied content ratings to understand the target audience and distribution of different rating categories.

### 📈 7. Data Visualization

Created visualizations using Matplotlib and Seaborn to communicate trends and patterns effectively.

## 💡 Key Insights

The analysis provides insights into:

- The relative distribution of Movies and TV Shows on Netflix.
- Trends in Netflix content releases over time.
- Popular genres and content categories.
- Countries contributing significantly to Netflix's content library.
- Distribution of content ratings.
- Overall patterns in Netflix's content strategy.

## 📁 Project Structure

```text
Netflix-Content-Trends-Analysis/
│
├── Netflix_EDA.ipynb
├── netflix_titles.csv
└── README.md
````

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/Ratt52/Netflix-Content-Trends-Analysis.git
```

2. Navigate to the project directory:

```bash
cd Netflix-Content-Trends-Analysis
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open the notebook:

```bash
jupyter notebook Netflix_EDA.ipynb
```

5. Run the notebook cells to reproduce the analysis and visualizations.

## 🧠 Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Data Wrangling
* Statistical Analysis
* Data Visualization
* Python Programming
* Pandas & NumPy
* Matplotlib & Seaborn
* Insight Generation

## 👤 Author

**Pranit Rathor**

B.Tech – Metallurgical and Materials Engineering
National Institute of Technology, Raipur

```
```
