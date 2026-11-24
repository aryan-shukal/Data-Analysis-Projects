# Data Analysis & Machine Learning Projects



A collection of hands-on projects exploring data analytics, exploratory data analysis, data visualization, predictive modelling, and machine learning using Python.



These projects demonstrate practical applications of data analysis techniques across entertainment, healthcare-related classification, and transportation demand analysis.



## Projects



### 1. Netflix Data Analysis



**Notebook:** `Netflix_Data_Analysis.ipynb`



**Objective:** Explore Netflix's content catalogue to identify patterns and trends across movies and TV shows.



**Technologies:** Python, Pandas, NumPy, Matplotlib, Seaborn, WordCloud



**Key Activities:**

- Data cleaning and preprocessing.

- Exploratory data analysis (EDA).

- Movie and TV show distribution analysis.

- Country-wise content distribution.

- Genre, director, and content rating analysis.

- Content additions by year and month.

- Movie and TV show duration analysis.

- Data visualization using charts, plots, and heatmaps.



**Key Observations:**

- Movies slightly outnumber TV shows in the analysed dataset.

- The United States, India, and the United Kingdom are among the leading content-producing countries.

- Content addition patterns vary across years and months.

- Movie durations and TV show seasons exhibit different distribution patterns.



### 2. Personalized Healthcare Recommendations



**Notebook:** `Personalized_Healthcare_Recommendations.ipynb`



**Objective:** Develop a machine learning classification prototype using blood donation-related data and demonstrate a basic recommendation mechanism based on model predictions.



**Technologies:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn



**Key Activities:**

- Dataset exploration and visualization.

- Numerical data preprocessing using imputation and standardization.

- Training and testing data splitting.

- Feature selection using SelectKBest.

- Random Forest classification.

- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix.

- Basic recommendation generation based on predicted classes.



**Dataset Features:**

- Recency

- Frequency

- Monetary

- Time

- Class (target variable)



**Model Evaluation:**

- Test accuracy: 72.67%

- Class 1 precision: 41%

- Class 1 recall: 24%

- Class 1 F1-score: 0.31



**Note:** This is an educational machine learning prototype, not a clinically validated healthcare recommendation system. The model has limitations, particularly in identifying positive-class cases.



### 3. Uber Trip Analysis & Demand Prediction



**Notebook:** `Uber_Trip_Analysis.ipynb`



**Objective:** Explore Uber trip activity and experiment with regression models to estimate trip demand using operational and temporal features.



**Technologies:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost



**Key Activities:**

- Data preprocessing and date conversion.

- Exploratory analysis of trip activity.

- Feature engineering using calendar-based variables.

- Weekend and rush-hour indicators.

- Random Forest regression.

- Comparison of Gradient Boosting, Random Forest, XGBoost, and Voting Regressor models.

- Model evaluation using Mean Squared Error and Mean Absolute Percentage Error (MAPE).

- Actual versus predicted visualization.



**Reported Model Comparison (MAPE):**



| Model | MAPE |

|---|---:|

| Gradient Boosting | 11.44% |

| XGBoost | 11.60% |

| Voting Regressor | 11.67% |

| Random Forest | 13.38% |



Gradient Boosting achieved the lowest reported MAPE among the four models in the notebook's evaluation.



**Note:** The analysis uses a random train-test split. The results should be interpreted as an exploratory model comparison rather than validated future-demand forecasting performance.



## Skills Demonstrated



- Data cleaning and preprocessing

- Exploratory Data Analysis (EDA)

- Data visualization and interpretation

- Feature engineering

- Statistical analysis

- Classification and regression

- Machine learning model evaluation

- Python-based analytical workflows



## How to Run



1. Clone this repository:



&#x20;  ```bash

&#x20;  git clone https://github.com/aryan-shukal/Data-Analysis-Projects.git

&#x20;  ```



2. Open the notebooks using Jupyter Notebook, JupyterLab, or Google Colab.



3. Install the relevant Python libraries:



&#x20;  ```bash

&#x20;  pip install pandas numpy matplotlib seaborn scikit-learn xgboost wordcloud

&#x20;  ```



4. Download the datasets required by each notebook and update the dataset file paths accordingly.



## Repository Structure



```text

Data-Analysis-Projects/

â”‚

â”œâ”€â”€ Netflix_Data_Analysis.ipynb

â”œâ”€â”€ Personalized_Healthcare_Recommendations.ipynb

â”œâ”€â”€ Uber_Trip_Analysis.ipynb

â””â”€â”€ README.md

```



## Author



**Aryan Shukla**



- GitHub: [aryan-shukal](https://github.com/aryan-shukal)

- LinkedIn: [LinkedIn](https://www.linkedin.com/in/aryan-shukal/)



---



*These projects were developed for learning and practical exploration of data analytics and machine learning techniques.*
