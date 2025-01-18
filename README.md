# Google-Reviews-Analysis

## Overview
This project helps businesses and analysts gain a comprehensive understanding of customer feedback by processing and analyzing large volumes of reviews. It provides a way to extract meaningful insights from thousands of reviews without the need to manually read through them. The project focuses on identifying trends in customer sentiment, major areas of satisfaction or concern, and how these aspects change over time.

## Features
**Language Detection and Translation:**
Automatically detects review languages and translates non-German reviews to German for consistent analysis.

**Sentiment and Topic Analysis:**
Categorizes reviews into topics like food, service, price, hygiene, and ambiance, offering a breakdown of customer satisfaction levels.

**Named Entity Recognition (NER):**
Extracts specific entities (e.g., dishes, menu items, or service aspects) to understand detailed feedback.

**Trends Over Time:**
Tracks how customer sentiment and review topics evolve over specific time periods.

**Visualization and Summary:**
Generates word clouds, bigrams, bar plots, and summary statistics to present actionable insights at a glance.

## Insights
**This project enables users to:**

Identify key drivers of positive and negative customer experiences.

Discover emerging trends in feedback over time (e.g., improved service, declining food quality).

Summarize sentiment across thousands of reviews, making it easier to pinpoint areas for improvement or celebrate strengths.

## Data Preprocessing
**Key preprocessing steps include:**

**Cleaning and Normalization:** Removes unnecessary characters (e.g., newlines), standardizes text, and handles missing data.

**Language Filtering:** Filters out reviews not in German or English for translation and further analysis.
**Stopword Removal:** Prepares data for visualizations by removing common words (e.g., "and," "the") to focus on meaningful terms.

These preprocessing steps ensure high-quality input for accurate insights and visualizations.

## Prerequisites
Python 3.7 or higher.
Required libraries:
pandas
matplotlib
numpy
tqdm
gliner
openai
transformers

**API keys for:**
Hugging Face (for sentiment and topic classification)
DeepL (for language translation)
Setup

**Install Libraries:**

pip install pandas matplotlib numpy tqdm gliner openai transformers

**Configure API Keys:**

Add your keys to a .env file:

HUGGINGFACE_API_KEY=<your_key>

DEEPL_API_KEY=<your_key>

**Run the Notebook:**

Open the notebook and execute cells in sequence to preprocess data, analyze reviews, and generate insights.

**Outputs:**

Saves processed, translated, and classified reviews in CSV files.

Creates visualizations (e.g., word clouds, rating distributions) and summaries for quick analysis.

## Example Use Case
**A restaurant owner uses this notebook to:**

1. Detect that most complaints are about "price" and "hygiene."

2. Notice improving "service" ratings after staff training initiatives.

3. Save time by getting summarized feedback instead of reading 2,000+ reviews manually.

## Security Note
Ensure API keys are stored securely in environment variables and not hard-coded into the notebook to prevent unauthorized access.

## Author
Jon Ardinast

## License and Sharing
This project is for personal or educational purposes only. Please contact me if you'd like to use it for other purposes.
