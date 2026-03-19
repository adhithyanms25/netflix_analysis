🎬 Netflix Data Analysis & Visualization
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a Netflix dataset to uncover trends, patterns, and insights related to movies and TV shows.

The analysis focuses on content distribution, ratings, country contributions, and release trends, using Python-based data science tools.

🎯 Objectives

Identify top-rated TV shows

Analyze movie title patterns (e.g., starting letters)

Find countries contributing the most content

Determine years with highest and lowest releases

Identify lowest-rated movies

Discover directors with maximum contributions

Compare ratings across different content types

📂 Dataset

Dataset: Netflix Titles with Viewer Ratings

Format: Excel (.xlsx)

Features include:

Title

Type (Movie / TV Show)

Country

Release Year

Director

Viewer Rating

Duration

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook

🔍 Data Preprocessing

Handled missing values using .dropna()

Created a clean working dataset (df_draft)

Performed data inspection using:

.info()

.isnull()

.value_counts()

📊 Key Analysis & Insights
1. ⭐ Top Rated TV Shows

Identified highest-rated TV shows based on viewer ratings

Visualized top 10 shows using line plots

2. 🔤 Movie Title Analysis

Counted number of movies starting with letter 'S'

Demonstrates string filtering and pattern analysis

3. 🌍 Country Contribution

Grouped data by country

Found country with highest content production

Visualized top contributing countries

4. 📅 Release Year Trends

Analyzed number of movies released per year

Identified:

Year with maximum releases

Year with minimum releases

5. 📉 Lowest Rated Movies

Extracted movies with lowest viewer ratings

Displayed results using bar charts

6. 🎬 Director Contribution

Identified most active director

Based on number of titles contributed

7. 📺 Rating Analysis

Compared average viewer ratings across categories

Visualized rating trends

📈 Visualizations

Line plots for trends

Bar charts for comparisons

Category-based visual insights

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/netflix-data-analysis.git

Install dependencies:

pip install pandas numpy matplotlib

Open the notebook:

jupyter notebook netflix.ipynb
🚀 Future Improvements

Add interactive dashboards using Plotly or Power BI

Apply machine learning models for prediction

Improve visualizations with Seaborn

Deploy project using web apps (Streamlit)

💡 Conclusion

This project demonstrates:

Strong understanding of data cleaning

Ability to perform EDA

Skills in data visualization

Practical use of real-world dataset

👤 Author

Adhithyan M S
Aspiring Data Scientist

⭐ If you like this project

Give it a ⭐ on GitHub!
