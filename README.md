🎬 Netflix Data Analysis
Exploratory Data Analysis (EDA) of a Netflix movies dataset to uncover trends in genres, popularity, ratings, languages, and release patterns.

📌 Project Overview
This project performs a comprehensive EDA on a dataset of ~9,800 Netflix movies sourced from TMDB (The Movie Database). The goal is to extract meaningful insights about what kinds of movies dominate the platform, which genres are most popular, and how content has evolved over time.

📂 Repository Structure
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full analysis
├── NetflixData.csv               # Dataset used for the analysis
└── README.md                     # Project documentation

📊 Dataset
File: NetflixData.csv
Rows: 9,826
Columns: 9
ColumnDescriptionRelease_DateDate the movie was releasedTitleMovie titleOverviewBrief plot descriptionPopularityTMDB popularity scoreVote_CountNumber of user votesVote_AverageAverage user rating (0–10)Original_LanguageLanguage the movie was originally made inGenreOne or more genres assigned to the moviePoster_UrlURL to the movie poster image

🔍 Analysis Performed

Data Loading & Preview — Loading the CSV and inspecting the first few rows
Dataset Structure — Shape, column names, and data types
Missing Value Check — Identifying and handling null values
Descriptive Statistics — Summary stats for numerical columns
Genre Analysis — Most frequent genres across the dataset
Popularity by Genre — Average popularity score per genre
Language Distribution — Breakdown of movies by original language
Release Year Trend — Number of movie releases over time
Vote Average Distribution — How ratings are spread across movies
Popularity Distribution — Distribution of popularity scores


💡 Key Insights

Drama is the most frequently occurring genre on Netflix.
Adventure movies have the highest average popularity, followed by Action and Science Fiction.
The number of movie releases increased significantly after the year 2000, reflecting the rapid growth of the film industry and streaming platforms.
Popularity distribution is highly skewed — most movies are average, and only a few become blockbuster hits.
English is by far the dominant original language in the dataset.


🛠️ Technologies Used

Python 3
Pandas — Data manipulation and analysis
Plotly Express — Interactive visualizations
Google Colab — Development environment


🚀 Getting Started
1. Clone the repository
bashgit clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
2. Install dependencies
bashpip install pandas plotly
3. Run the notebook
Open Netflix_Data_Analysis.ipynb in Jupyter Notebook, JupyterLab, or Google Colab.

Note: If running on Google Colab, upload NetflixData.csv to the Colab session storage and update the file path in the data loading cell:
pythondf = pd.read_csv('/content/NetflixData.csv')


📈 Sample Visualizations
The notebook includes interactive Plotly charts for:

Bar chart of top genres by frequency
Bar chart of average popularity by genre
Histogram of vote averages
Histogram of popularity scores
Line/bar chart of releases by year
Language distribution chart


🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for improvements, additional analyses, or bug fixes.

📄 License
This project is open-source and available under the MIT License.

🙏 Acknowledgements

Dataset sourced from TMDB (The Movie Database)
Inspired by the growing interest in streaming platform data analytics
