# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of a Netflix movies dataset to uncover trends, patterns, and insights across genres, popularity, ratings, languages, and release years.

---

## 📋 Project Overview

This project performs a comprehensive analysis of **9,826 Netflix movies** using Python. The dataset contains metadata such as release date, genre, popularity score, vote count, vote average, original language, and poster URL sourced from TMDB (The Movie Database).

The goal is to answer key questions like:
- Which genres are most common on Netflix?
- Which genres are the most popular?
- How has the number of movie releases changed over time?
- What is the distribution of movie ratings and popularity?
- Which languages dominate the Netflix library?

---

## 📁 Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── NetflixData.csv               # Dataset used for analysis
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Dataset Description

| Column              | Description                                      |
|---------------------|--------------------------------------------------|
| `Release_Date`      | Date the movie was released                      |
| `Title`             | Movie title                                      |
| `Overview`          | Short description of the movie                   |
| `Popularity`        | Popularity score from TMDB                       |
| `Vote_Count`        | Total number of user votes                       |
| `Vote_Average`      | Average user rating (0–10)                       |
| `Original_Language` | Language the movie was originally produced in    |
| `Genre`             | One or more genres associated with the movie     |
| `Poster_Url`        | URL to the movie's poster image (from TMDB)      |

- **Rows:** 9,826  
- **Columns:** 9

---

## 🔍 Analysis Performed

1. **Data Loading & Preview** — Loading the CSV and inspecting the first few rows
2. **Dataset Structure** — Shape, column names, data types, and null value check
3. **Data Cleaning** — Handling missing values and formatting the `Release_Date` column
4. **Genre Analysis** — Most frequent genres and average popularity per genre
5. **Language Distribution** — Distribution of movies by original language
6. **Release Year Trend** — Number of movie releases per year over time
7. **Ratings Distribution** — Distribution of vote averages across all movies
8. **Popularity Distribution** — How popularity scores are distributed (skewness)

---

## 📈 Key Insights

- **Drama** is the most frequently occurring genre in the Netflix dataset.
- **Adventure** movies show the highest average popularity among all genres.
- **Action** and **Science Fiction** genres also attract high audience interest.
- Movie releases grew significantly **after the year 2000**, reflecting the growth of streaming platforms.
- The popularity distribution is **highly skewed** — most movies are average, while only a few become blockbuster hits.
- **English (en)** dominates as the original language, with a variety of other languages also represented.

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** — Data manipulation and analysis
- **Plotly Express** — Interactive visualizations
- **Jupyter Notebook / Google Colab** — Development environment

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

> Or open directly in [Google Colab](https://colab.research.google.com/) by uploading the `.ipynb` file.

---

## 📌 Notes

- Make sure `NetflixData.csv` is in the same directory as the notebook before running.
- If using Google Colab, upload the CSV to `/content/` or update the file path in the notebook accordingly.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
