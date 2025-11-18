# Copilot Instructions

## About this Project

This project is a machine learning analysis performed in a Jupyter Notebook (`mlfinalproject.ipynb`). The goal is to explore the relationship between social media usage and mental health.

The analysis involves:
1.  Downloading a dataset from Kaggle.
2.  Performing Exploratory Data Analysis (EDA) to understand the data.
3.  Visualizing the data to find patterns.
4.  Defining a machine learning problem (regression) to predict `Mental_Health_Score`.

## Workflow

The primary workflow is contained within the `mlfinalproject.ipynb` notebook. When adding new analysis steps, please follow the existing pattern:

1.  **Markdown for Reasoning**: Before adding a new code cell, add a Markdown cell that explains the purpose and reasoning for the code that will be written. Use the `**Reasoning**:` heading.

    *Example from the notebook:*
    ```markdown
    **Reasoning**:
    To validate the data quantity and quality, I will first print the shape of the DataFrame to get the number of rows and columns, and then calculate and display the sum of missing values for each column to identify any data quality issues.
    ```

2.  **Code Cell**: Add the Python code to perform the step described in the reasoning cell.

3.  **Subtask Headings**: For major sections of the analysis, use Markdown headings like `## Subtask:` to clearly define the objective.

## Key Libraries

The project relies on the following core Python libraries:
- `kagglehub`: For downloading the dataset.
- `pandas`: For data manipulation and analysis.
- `matplotlib` & `seaborn`: For data visualization.

When adding new features, please use these libraries if possible to maintain consistency.

## Data

The dataset is downloaded from Kaggle using `kagglehub.dataset_download("adilshamim8/social-media-addiction-vs-relationships")`. The loaded data is stored in a pandas DataFrame called `df`.

The target variable for the regression task is `Mental_Health_Score`.
