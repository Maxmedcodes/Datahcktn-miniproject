# Datahcktn-miniproject - Task

# Hackathon: “From Data to Insights to Predictions”

**Duration**: 1.5 days

**Goal**: Work as a data scientist for a day and a half – explore a dataset, ask questions, find answers, and make predictions using `Python`, `Pandas`, `Matplotlib`, and `scikit-learn` — all inside Databricks.

## Scenario
You’ve just been hired as a Junior Data Scientist for a company that needs to make data-driven decisions. Your task is to pick a real dataset from [Kaggle](https://www.kaggle.com/), explore it, clean it, find patterns, visualize results, and use Machine Learning to predict something useful.

All of your work will be done in [Databricks](https://www.databricks.com/learn/free-edition). When you finish, you’ll push your notebook(s) and any related files to a GitHub repository and send the link in the Slack channel.

## Steps & Deliverables

1. **Choose a Dataset**
- Go to **Kaggle** and find a dataset you find interesting (small-to-medium size so you can work quickly – < 100MB recommended)
- Make sure it has at least one numeric column you can predict with regression or one categorical column you can classify
- Upload it to **Databricks**

2. **Ask Questions & Create Hypotheses**
- Write 3–5 analysis questions you want to answer
- Write 1–2 hypotheses you can test
- Decide which column will be your target variable for Machine Learning

3. **Data Cleaning & Transformation**
- Load your dataset in a `Jupyter Notebook` inside Databricks
- Handle missing values, duplicates, and incorrect data types
- Create new columns if needed
- Filter, group, and sort data to prepare it for analysis

4. **Data Visualization**
- Use `Matplotlib` (and optionally `Seaborn`) to create at least 5 meaningful plots that help answer your questions
- Each plot should have a clear title, axis labels, and legends if needed

5. **Machine Learning Predictions**
- Use `scikit-learn` to create a basic model:
  - Regression (if predicting a number)
  - Classification (if predicting a category)
- Steps:
  - Split data into train/test sets
  - Choose a simple model
  - Train and evaluate the model
  - Show accuracy score, R², or other relevant metrics
- Interpret the results

6. **Bonus Ideas** (if time allows)
- Use correlation heatmaps to identify relationships
- Try feature scaling
- Test multiple models and compare performance

7. **Submission Instructions**
- Create a GitHub repository
- Include:
  - Jupyter notebooks (`.ipynb`)
  - Dataset (if allowed by Kaggle’s license)
  - `README.md` with:
    - Dataset source
    - Your questions and hypotheses
    - Summary of cleaning process
    - Summary of results and predictions
- Push to GitHub and send link in Slack
