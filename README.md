# 🎬 Netflix 1990s Movies: Exploratory Data Analysis (EDA)

Netflix! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.
Given the large number of movies and series available on the platform, it provides a perfect opportunity to apply exploratory data analysis (EDA) techniques and gain insights into trends within the entertainment industry.

In this project, we focus specifically on movies released during the 1990s, exploring patterns related to movie duration, genre distribution, and country of production using the dataset netflix_data.csv.

**📊 Dataset Overview**

The dataset used in this project contains information about movies and TV shows available on Netflix.

Key columns include:

| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

The analysis focuses only on movies released between 1990 and 1999.

**📌 Data Source**

The dataset used in this project was obtained from DataCamp as part of a guided project and learning exercise.

Platform: DataCamp

Dataset name: netflix_data.csv

Description: Contains metadata for movies and TV shows available on Netflix, including release year, duration, genre, and country.

The dataset was used for educational and portfolio purposes only, and the analysis focuses on movies released during the 1990s.

**🔍 Objectives of the Analysis**

The main goals of this project were:

To understand typical movie runtimes in the 1990s

To analyze runtime trends across the decade

To identify dominant genres of the period

To examine country-wise distribution of 1990s movies on Netflix

To translate technical findings into business-relevant insights

**📈 Exploratory Data Analysis**

The analysis follows a structured EDA process:

Initial data understanding (info(), describe())

Missing value assessment

Filtering movies released in the 1990s

Visual analysis of:

Movie duration distribution

Runtime trends over time

Genre dominance

Country-wise movie counts

All visualizations use a Netflix-inspired red and black theme for consistent and professional presentation.


**🧠 Key Insights**

🎞️ Most Frequent Movie Duration

Most 1990s movies on Netflix have a runtime of approximately 90 minutes, indicating a standard feature-length format.

📉 Runtime Trend Across the 1990s

The average movie duration did not remain stable throughout the decade, showing noticeable variation year by year.

🎭 Genre Dominance

Action, Drama, and Comedy dominated the 1990s movie catalog, with Action movies appearing most frequently.

💥 Action Movie Runtime Patterns

Action movies tend to be longer, with only 7 Action movies shorter than 90 minutes, suggesting most Action films in the 1990s exceeded 1.5 hours.

🌍 Country-wise Production

The United States produced the highest number of 1990s movies available on Netflix, followed by India and the United Kingdom, reflecting historical global film production trends.

🏢 Business Implications

Content Strategy: Understanding dominant genres and runtimes helps guide content acquisition and licensing strategies.

Recommendation Systems: Runtime and genre patterns can improve personalized recommendations based on viewing preferences.

Regional Insights: Country-level analysis supports region-specific content targeting and investment decisions.

User Engagement: Differentiating short vs long movies can optimize viewer engagement for different audience segments.

**🛠️ Tools & Technologies Used**

Python

Pandas (data manipulation)

Matplotlib (visualization)

Jupyter Notebook

📌 Project Structure
├── netflix_data.csv
├── netflix_notebook.ipynb
├── images/
└── README.md

**✅ Conclusion**

This project demonstrates how structured exploratory data analysis can uncover meaningful insights about historical movie trends. By combining statistical summaries, visual storytelling, and business interpretation, the analysis highlights patterns in runtime, genre dominance, and regional production that are relevant for both data analysts and business stakeholders.

**📬 Author**

Muneeza Syed
📍 United Kingdom