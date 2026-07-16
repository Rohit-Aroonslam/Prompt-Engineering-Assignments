# Prompt-Engineering-Assignments

Coding assignments completed as part of **Prompt Engineering and Programming with OpenAI**, a course from [Columbia+](https://plus.columbia.edu/) (Columbia University's professional and continuing education platform). All credit for the assignment designs, datasets, and course materials belongs to the course instructors — this repo holds my completed work and notes.

## Module 1: Stock Price Prediction with LLM
`Module 1 Assignment/`

A no-code/low-code exercise using Google's Gemini directly inside Google Colab to load historical stock price data (via Yahoo Finance), engineer features, and explore prediction approaches — all through natural language prompts rather than hand-written code.

## Module 2: Retail Sales Data Analysis with LLM
`Module 2 Assignment/`

Uses LangChain's pandas dataframe agent (backed by OpenAI's GPT-4o) to analyze a retail transactions dataset for Columbia Plus Mart, a fictional retail store. Covers:
- **Data exploration** — missing values, outliers, and summary statistics
- **Sales trend analysis** — monthly and weekday patterns in order volume
- **Customer segmentation** — KMeans clustering on age, spend, and quantity to identify distinct customer groups
- **Hypothesis testing** — statistical tests (ANOVA, t-test) on whether age, sales timing, and gender affect purchase behavior

Dataset: `Module 2 Assignment/data/retail_sales_dataset.csv` ([source](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset))

## Setup
Each notebook is self-contained and includes its own setup instructions (installing dependencies, adding an OpenAI API key via Colab Secrets, and loading the dataset). Open a notebook in Colab and run the cells top to bottom.
