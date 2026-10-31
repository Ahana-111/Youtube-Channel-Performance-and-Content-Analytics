# YouTube Channel Performance & Content Analytics

## Project Overview

This project uses Python to explore and analyze YouTube data. It focuses on understanding audience engagement through comments, likes, replies, and sentiment analysis.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- TextBlob
- Jupyter Notebook

## Project Objectives

- Explore and understand YouTube data.
- Clean and preprocess the dataset.
- Analyze likes and replies on comments.
- Perform sentiment analysis on YouTube comments.
- Identify positive, negative, and neutral comments.
- Present findings through data visualizations.

## Project Files

- "Youtube.ipynb" – Jupyter Notebook containing the analysis.
- "youtube_sample.csv" – Sample dataset in CSV format.
- "youtube_sample.json" – Sample dataset in JSON format.

## Dataset

The original dataset (video_id_info.csv) is not included in this repository because it exceeds GitHub's 25 MB browser-upload limit.

The dataset contains YouTube comment information, including video IDs, comment text, likes, and replies. The sample datasets provided in this repository are for reference only.

To run the notebook, download video_id_info.csv separately and place it in the same folder as Youtube.ipynb. Also, download the additional country-specific files and place them inside the YT_additional_data folder.

The project also uses additional country-specific CSV files and the "US_category_id.json" file stored in the "YT_additional_data" folder for category-based analysis. These files are required to reproduce the category and channel analysis. They are not included in this repository.
 

## Analysis Workflow

The project follows these steps:
Import the required Python libraries.
Load the YouTube dataset.
Explore the dataset and understand its structure.
Identify and handle missing values.
Analyze comments, likes, and replies.
Perform sentiment analysis using TextBlob.
Classify comments as positive, negative, or neutral.
Visualize the analysis results.

## Key Findings & Insights

1. Views and Likes: A strong positive correlation of approximately 0.78 was observed between video views and likes.
2. Channel Performance: The Late Show with Stephen Colbert had the highest number of trending videos in the analyzed dataset, with 710 videos.
3. Audience Engagement: Like rate, dislike rate, and comment count rate were analyzed to understand audience interaction.
4. Category Analysis: Likes and engagement patterns were compared across different YouTube video categories.
5. Sentiment Analysis: TextBlob was used to analyze YouTube comments, and positive and negative comment word clouds were generated.
6. Emoji Analysis: Frequently used emojis in YouTube comments were identified and visualized.

## How to Run the Project

1. Install Python on your computer.
2. Install Jupyter Notebook.
3. Install the required libraries:
 
pip install pandas numpy seaborn matplotlib textblob wordcloud emoji==2.10.1 plotly

4. Download or clone this repository.
5. Download the original "video_id_info.csv" dataset separately and place it in the same folder as "Youtube.ipynb".
6. Download the additional country-specific CSV and JSON files and place them inside the "YT_additional_data" folder.
7. Open Jupyter Notebook and run "Youtube.ipynb" cell by cell.

Note: Make sure the dataset files are placed in the correct folders before running the notebook.

## Project Status

The exploratory data analysis, sentiment analysis, emoji analysis, and visualizations have been completed.
