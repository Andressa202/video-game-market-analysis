# 🎮 Video Game Market Analysis | Sales Trends & Statistical Insights

### Exploring Global Video Game Sales, Regional Preferences, and Market Trends with Python

**Python • Pandas • NumPy • Plotly • SciPy • Statistical Analysis**

## 📌 Project Overview

The video game industry is a dynamic global market influenced by consumer preferences, gaming platforms, genres, and regional trends.

This project conducts an exploratory data analysis of historical video game sales to identify patterns in commercial performance, investigate regional differences, and evaluate statistical hypotheses about user ratings.

The analysis uses historical video game data through 2016 and focuses on understanding factors associated with market performance.

## 🎯 Project Objectives

- Analyze historical trends in video game releases and sales.
- Identify leading gaming platforms and genres.
- Explore platform life cycles and changes in market performance.
- Compare consumer preferences across North America, Europe, and Japan.
- Investigate relationships between critic scores and sales.
- Evaluate statistical hypotheses regarding user ratings.
- Generate actionable insights to support market analysis.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and programming |
| Pandas | Data cleaning, transformation, and aggregation |
| NumPy | Numerical operations |
| Plotly Express | Interactive data visualization |
| SciPy | Statistical hypothesis testing |
| Jupyter Notebook | Analysis and documentation |

## 📂 Dataset Description

The dataset (`games.csv`) contains historical information about video games, including:

- `name` — Game title
- `platform` — Gaming platform
- `year_of_release` — Release year
- `genre` — Game genre
- `na_sales` — North American sales
- `eu_sales` — European sales
- `jp_sales` — Japanese sales
- `other_sales` — Sales in other regions
- `critic_score` — Professional critic ratings
- `user_score` — User ratings
- `rating` — ESRB age classification

An additional variable, `global_sales`, was created by summing sales across regions.

## 🧹 Data Preparation

The data preparation process included:

1. Standardizing column names to lowercase.
2. Converting release years to nullable integer format.
3. Replacing `"TBD"` user ratings with missing values.
4. Converting user scores to numerical values.
5. Identifying missing and duplicate records.
6. Removing duplicate rows.
7. Creating the `global_sales` variable.

Missing evaluation scores were not artificially imputed to avoid introducing misleading information into the statistical analysis.

## 📊 Exploratory Data Analysis

### 1. Video Game Releases Over Time

The analysis identified historical growth in video game releases, with a peak around 2008–2009.

### 2. Gaming Platform Performance

Global sales were compared across platforms, including an examination of platform life cycles.

The results highlighted the concentration of sales among leading platforms and the evolution of their commercial performance over time.

### 3. Sales by Genre

Action and Sports were among the dominant genres in global sales.

### 4. Regional Market Analysis

Sales patterns were examined across three major markets:

**North America:** Strong interest in major console platforms and popular genres such as Action, Sports, and Shooter.

**Europe:** Similarities with North American preferences, particularly in console gaming.

**Japan:** A distinct market profile, with greater preference for role-playing games and Nintendo platforms.

### 5. Critic Scores and Sales

The analysis identified a weak positive relationship between critic scores and commercial performance, indicating that ratings alone do not determine sales success.

## 🧪 Statistical Hypothesis Testing

Two statistical tests were conducted using Welch's t-test with a significance level of 5% (α = 0.05).

### Hypothesis 1 — Xbox One vs PC

**Question:** Do average user ratings differ significantly between Xbox One and PC games?

**Result:** No statistically significant difference was identified between the two platforms.

**Conclusion:** The null hypothesis was not rejected.

### Hypothesis 2 — Action vs Sports

**Question:** Do average user ratings differ significantly between Action and Sports games?

**Result:** A statistically significant difference was identified.

**Conclusion:** The null hypothesis was rejected, with Action games receiving higher average user ratings in the analyzed sample.

## 💡 Key Findings

- Video game sales are concentrated among a relatively small number of titles and platforms.
- Platform performance changes over time, reflecting product life cycles.
- Regional preferences differ, especially between Japan and Western markets.
- Action and Sports are commercially important genres.
- Critic scores show a limited relationship with sales.
- The statistical tests identified a significant difference in user ratings between Action and Sports games, but not between Xbox One and PC games.

## ⚠️ Limitations

- Missing values affect some rating and classification variables.
- Data for 2016 may be incomplete.
- Outliers can influence sales distributions and summary statistics.
- Statistical associations should not be interpreted as proof of causation.

## 🚀 How to Run the Project

1. Clone the repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Update the dataset path to the local location of `games.csv`.
5. Run the notebook cells sequentially.

Required libraries:

```bash
pip install pandas numpy plotly scipy notebook
```

## 📈 Project Conclusion

This analysis demonstrates how exploratory data analysis, interactive visualizations, and statistical testing can be combined to understand historical video game market behavior.

The project highlights the importance of platform life cycles, regional consumer preferences, and game genres in market analysis.

## 👩‍💻 Author

**Andressa Miranda**

Computer Science | Data Analytics | Python | Statistical Analysis

[GitHub Profile](https://github.com/Andressa202)

*Developed as part of the TripleTen Data Science program.*
