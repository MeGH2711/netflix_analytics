# 📺 Netflix Movies & TV Shows Analysis

This is a mini data science project where I explored and visualized Netflix's catalog of movies and TV shows. The project was done using **Google Colab** with Python, and the goal was to gain hands-on experience with data cleaning, preprocessing, and exploratory data analysis (EDA) — all while uncovering interesting trends from the Netflix platform.

---

## 📊 Project Overview

- 🔍 Dataset: Netflix Movies and TV Shows (from Kaggle)
- 🛠 Tools: Python, Pandas, Matplotlib, Seaborn
- 🧠 Skills Learned:
  - Handling missing data
  - Working with dates and time series
  - Cleaning and transforming string data
  - Generating insights using visualizations

---

## 📁 Dataset

- Source: [Kaggle - Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- File Used: `netflix_titles.csv`
- Contains:
  - Title
  - Director
  - Cast
  - Country
  - Date added
  - Release year
  - Duration
  - Genre (listed_in)
  - Description

---

## 🧹 Data Cleaning Steps

- Removed duplicates
- Filled missing values in `country`, `cast`, `director` with `"Unknown"`
- Converted `date_added` to `datetime`
- Extracted `year_added` and `month_added` from `date_added`
- Split `listed_in` (genres) for better analysis

---

## 📈 Exploratory Data Analysis (EDA)

Here are some key visualizations and insights generated during this project:

- Distribution of **Movies vs TV Shows**
- Top 10 **countries** producing the most content
- **Content release trend** over the years
- Top 10 **genres** on Netflix
- (Optional) **Word cloud** of movie/show descriptions

All visualizations were created using `matplotlib` and `seaborn`.

---

## 📌 Sample Insights

- Netflix has more **movies** than TV shows.
- The **United States** leads by content production, followed by India and the UK.
- A peak in content addition was observed in **2019 and 2020**.
- Popular genres include **Dramas**, **Comedies**, and **Documentaries**.

---

## 💻 Technologies Used

| Tool         | Purpose                          |
|--------------|----------------------------------|
| Python       | Programming Language             |
| Pandas       | Data manipulation                |
| Seaborn      | Data visualization               |
| Matplotlib   | Plotting graphs                  |
| WordCloud    | Optional visualization           |
| Google Colab | Notebook environment             |

---

## 🚀 How to Run This Project

1. Clone this repository or download the notebook.
2. Download the dataset from Kaggle.
3. Open the notebook in [Google Colab](https://colab.research.google.com).
4. Upload the dataset using `files.upload()`.
5. Run each cell to explore the data and visualize insights.

---


---

## 📌 Future Work Ideas

- Build a **dashboard** using Streamlit
- Use NLP to analyze the **description** text column
- Build a **recommendation system** using genres/countries

---

## 🙋‍♂️ Author

**Megh Patel**  
💻 M.Tech Student @ Ahmedabad University  
🔗 [LinkedIn](https://www.linkedin.com/in/meghpatel2711/) | [GitHub]([https://github.com](https://github.com/MeGH2711/))
