# Netflix Data Analysis (Project 1) - Pluto Academy AI & ML Internship Program
## Exploratory Data Analysis & Content Insights Report

Analysis and exploration of the Netflix content dataset, investigating trends in streaming content, production patterns, and platform strategy over time.

---

## Dataset

**Source:** Netflix Content Dataset (Kaggle)

The dataset contains comprehensive information about content available on the Netflix streaming platform:

- **Rows:** 8,800+ content titles
- **Columns:** 12 features
- **Key Features:** show_id, type (Movie/TV Show), title, director, cast, country, date_added, release_year, rating, duration, listed_in (genres), description

**Data Coverage:** Netflix content data spanning from content addition dates, offering a snapshot of the platform's library composition and production trends.

---

## Objective

Conduct an exploratory data analysis to understand the Netflix content dataset and identify emerging patterns in streaming content. This analysis aims to:

- Analyze the distribution of content types (Movies vs. TV Shows)
- Identify dominant genres and content categories
- Understand temporal trends in content releases and platform additions
- Visualize content distribution across countries and regions
- Explore relationships between content ratings, duration, and platform strategy
- Deliver data-backed insights about Netflix's content portfolio and acquisition patterns

---

## Key Insights

1. **Content Type Distribution** — Netflix's library is dominated by movies, with TV shows representing a smaller but growing segment. The ratio reflects the platform's strategic focus on diverse content formats.

2. **Genre Dominance** — Drama, Comedy, and International content form the core of Netflix's library. These genres appeal to the broadest audience demographics and support the platform's global expansion.

3. **Temporal Trends in Acquisition** — Netflix has accelerated content acquisition in recent years, with significant increases in the number of titles added annually, reflecting competitive pressure and platform growth.

4. **Geographic Content Strategy** — Content production and acquisition is concentrated in a few key countries (US, India, UK), though the platform is expanding into emerging markets and diverse production regions.

5. **Rating and Content Strategy** — The platform shows a strategic emphasis on TV-MA and PG-13 content, targeting mature audiences and families. This diversification supports broader audience retention.

6. **Duration Patterns** — Movies show consistent duration ranges (80-130 minutes), while TV shows vary significantly in episode counts, reflecting different production models and audience engagement strategies.

---

## Visualizations

The analysis includes multiple chart types to explore the data from different angles:

- **Bar Charts** — Content type distribution, top genres, and country-wise content count
- **Time Series Charts** — Trends in content additions over years
- **Pie Charts** — Proportional breakdown of content types and ratings
- **Histograms** — Distribution of movie durations and TV show episodes
- **Scatter Plots** — Relationships between release year and platform additions
- **Heatmaps** — Genre and country correlation matrices
- **Count Plots** — Rating distribution and content type breakdowns
- **Geographic Maps** — Global distribution of content production

---

## Tech Stack

- **Language:** Python 3
- **Data Processing:** Pandas · NumPy
- **Visualization:** Matplotlib · Seaborn · Plotly
- **Notebook Environment:** Jupyter

---

## Repository Structure

```
Netflix-EDA-project/
├── README.md                                    # This file
├── LICENSE                                      # Project license
├── requirements.txt                             # Python dependencies
├── data/                                        # Data files directory
│   ├── README.md                                # Data documentation
│   └── netflix_titles.csv                       # Netflix dataset
├── images/                                      # Generated visualizations
│   └── (exported chart PNGs and graphs)
├── notebooks/                                   # Jupyter notebooks
│   └── Netflix_EDA_Project1.ipynb              # Main EDA analysis notebook
└── reports/                                     # Analysis reports
    └── insights_report.md                       # Detailed insights documentation
```

---

## How to Run

### Prerequisites
Ensure you have Python 3.7+ installed with the required packages.

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/raaghuno18-spec/Netflix-EDA-project.git
   cd Netflix-EDA-project
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   Or install manually:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly jupyter
   ```

4. **Launch Jupyter and open the notebook:**
   ```bash
   jupyter notebook notebooks/Netflix_EDA_Project1.ipynb
   ```

5. **Run all cells** top to bottom to generate analysis, visualizations, and insights.

---

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- jupyter

---

## Author
Raghavendra N O — Pluto Academy AI & ML Internship, Project 01

## License

See [LICENSE](LICENSE) file for details.

---

**Project:** Netflix Content Analysis  
**Status:** In Progress  
**Last Updated:** 2026
