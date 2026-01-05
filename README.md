# 📊 Netflix Content Analysis - Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

## 🎯 Project Overview

An in-depth exploratory data analysis of Netflix's content catalog, examining **8,807 movies and TV shows** to uncover insights about content trends, genre preferences, geographic production patterns, and viewing characteristics. This project demonstrates data cleaning, statistical analysis, and visualization techniques using Python.

## 📌 Key Findings

- **Content Split**: Netflix's library consists of **69.6% Movies** and **30.4% TV Shows**
- **Peak Growth**: Content additions peaked in **2019** with significant growth in the streaming wars era
- **Top Producer**: The **United States** leads with the highest number of titles, followed by India and the UK
- **Popular Genres**: International Movies, Dramas, and Comedies dominate the catalog
- **Content Ratings**: TV-MA and TV-14 are the most common ratings, indicating mature content focus
- **Movie Duration**: Average movie length is **99 minutes** with most TV shows having **1 season**

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualizations
- **Jupyter Notebook** - Interactive development environment

## 📁 Project Structure

```
netflix-eda-project/
│
├── data/
│   └── netflix_titles.csv          # Dataset (8,807 titles)
│
├── notebooks/
│   └── netflix_content_analysis.ipynb  # Main analysis notebook
│
├── images/                          # Generated visualizations
│   ├── content_type_distribution.png
│   ├── yearly_content_trend.png
│   ├── top_countries.png
│   ├── content_ratings.png
│   ├── top_genres.png
│   └── ... (additional charts)
│
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation
```

## 📊 Analysis Sections

1. **Data Understanding & Exploration**
   - Dataset overview and structure
   - Missing value analysis
   - Data quality assessment

2. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Date parsing and feature extraction
   - Data type conversions

3. **Content Type Analysis**
   - Movies vs TV Shows distribution
   - Content composition trends

4. **Temporal Analysis**
   - Yearly content addition trends
   - Monthly seasonality patterns
   - Peak growth periods

5. **Geographic Distribution**
   - Top content-producing countries
   - Regional content preferences
   - International vs domestic content

6. **Content Ratings Analysis**
   - Rating distribution and trends
   - Age-appropriate content mix
   - Rating by content type

7. **Genre Analysis**
   - Most popular genres
   - Genre combinations
   - Content diversity

8. **Duration Analysis**
   - Movie length distribution
   - TV show season patterns
   - Content consumption insights

9. **Release Year Trends**
   - Content by decade
   - Classic vs modern content ratio

10. **Top Contributors**
    - Most prolific directors
    - Frequently featured actors

## 📈 Sample Visualizations

The project includes 12+ professional visualizations including:
- Content type pie charts and bar plots
- Time series trends of content additions
- Geographic heat maps and country rankings
- Genre popularity analysis
- Duration distributions and box plots
- Rating breakdowns by content type

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.8 or higher
pip (Python package manager)
```

### Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/netflix-eda-project.git
   cd netflix-eda-project
   ```

2. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook notebooks/netflix_content_analysis.ipynb
   ```

4. **Run all cells**
   - Execute cells sequentially to reproduce the analysis
   - Visualizations will be saved in the `images/` folder

## 📊 Dataset Information

**Source**: Netflix Movies and TV Shows Dataset  
**Records**: 8,807 titles  
**Features**: 12 columns including:
- Title, Type (Movie/TV Show)
- Director, Cast
- Country of production
- Release year, Date added to Netflix
- Rating, Duration
- Genres, Description

**Missing Values**:
- Director: 29.9%
- Cast: 9.4%
- Country: 9.4%
- Date Added: 0.1%

## 💡 Key Insights for Business

1. **Content Strategy**: Netflix focuses heavily on TV-MA content, targeting mature audiences
2. **International Expansion**: Strong presence in US, India, UK markets with localized content
3. **Recent Content Focus**: Majority of additions from 2015-2020 reflecting aggressive growth period
4. **Genre Diversification**: Wide genre coverage with emphasis on Dramas and International content
5. **Production Efficiency**: Most TV shows are single-season, indicating experimental approach

## 🔮 Future Enhancements

- Sentiment analysis on descriptions
- Machine learning models for content recommendation
- Network analysis of actor-director collaborations
- Time series forecasting for content additions
- Comparative analysis with competitor platforms

## 👩‍💻 Author

**Meghana Reddy Guntupalli**  
IT Service Delivery Analyst | Data Enthusiast  

- **LinkedIn**: [linkedin.com/in/meghana-reddy](#)
- **Email**: meghana.reddy@example.com
- **Location**: Dubai, UAE

## 📝 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- Dataset sourced from publicly available Netflix data
- Inspired by data analytics community best practices
- Built as part of portfolio development for data analyst roles

---

⭐ **If you found this project helpful, please consider giving it a star!**

---

**Last Updated**: January 2026
