# Student Performance Factors Analysis

Welcome to the **Student Performance Factors Analysis** repository! This project delves into the **"Student Performance Factors"** dataset from [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors), aiming to uncover the key elements that influence academic success.

## Table of Contents

- [Dataset](#dataset)
- [Objective](#objective)
- [Features](#features)
- [Analysis Process](#analysis-process)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Getting Started](#getting-started)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Dataset

The analysis utilizes the **Student Performance Factors** dataset, which encompasses a variety of features related to student demographics, study habits, health, and social factors. The dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors).

### Dataset Features

- **Hours_Studied**: Number of hours studied per week
- **Attendance**: Percentage of classes attended
- **Parental_Involvement**: Level of parental involvement in the student's education
- **Access_to_Resources**: Availability of academic resources (High/Low)
- **Extracurricular_Activities**: Participation in extracurricular activities (Yes/No)
- **Sleep_Hours**: Average hours of sleep per night
- **Previous_Scores**: Previous academic performance (percentage)
- **Motivation_Level**: Self-reported motivation level (Low/Medium/High)
- **Internet_Access**: Access to the internet for study purposes (Yes/No)
- **Tutoring_Sessions**: Number of tutoring sessions attended
- **Family_Income**: Family income level (Low/Medium/High)
- **Teacher_Quality**: Perceived quality of teaching (Low/Medium/High)
- **School_Type**: Type of school attended (Public/Private)
- **Peer_Influence**: Influence of peers on academic performance (Negative/Neutral/Positive)
- **Physical_Activity**: Hours of physical activity per week
- **Learning_Disabilities**: Presence of learning disabilities (Yes/No)
- **Parental_Education_Level**: Highest level of education attained by parents
- **Distance_from_Home**: Distance from home to school (Near/Far)
- **Gender**: Gender of the student
- **Exam_Score**: Final exam score

## Objective

The primary goals of this analysis are:

1. **Identify Significant Factors**: Determine which factors significantly impact student performance.
2. **Explore Relationships**: Analyze the correlations between various features and academic outcomes.
3. **Provide Insights**: Offer actionable recommendations to enhance student performance based on the findings.

## Analysis Process

The analysis follows a structured approach:

1. **Data Cleaning**: Address missing values, remove outliers, and correct data inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Visualize data distributions and explore relationships between features.
3. **Statistical Analysis**: Perform correlation studies and hypothesis testing to identify significant factors.
4. **Modeling**: Develop regression models to predict student performance based on identified features.
5. **Conclusions & Insights**: Summarize key findings and propose recommendations for improving academic outcomes.

## Technologies Used

- **Python**: Core programming language for the analysis.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning for predictive modeling.

## Results

The analysis yields several key insights:

- **Impact of Study Time**: A strong correlation exists between the number of hours studied and exam scores.
- **Family and School Support**: Higher levels of parental involvement and quality of teaching positively influence academic performance.
- **Health and Well-being**: Adequate sleep and physical activity are associated with better student outcomes.

Detailed visualizations and statistical findings are documented in the [final report](path/to/final_report.pdf).

## Getting Started

Follow these steps to run the analysis on your local machine:

### Prerequisites

- Python 3.7 or higher
- Git

### Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/PstarH/student-performance-factor-analysis.git
    ```
2. **Navigate to the Project Directory**
    ```bash
    cd student-performance-factor-analysis
    ```
3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```
4. **Run the Analysis**
    ```bash
    python main.py
    ```

### Dataset

Ensure that the **StudentPerformanceFactors.csv** file is placed in the project's root directory. If you wish to use a different dataset, update the file path accordingly in the scripts.

## Conclusion

This project demonstrates the application of data analysis techniques to identify and understand the factors influencing student performance. The findings highlight the importance of study habits, support systems, and health in academic success. Future work can explore advanced machine learning models to further enhance predictive accuracy and uncover deeper insights.

## Acknowledgements

- **Lai Nguyen**: Gratitude to the original author of the dataset on [Kaggle](https://www.kaggle.com/lainguyn123) for providing the data.
- **Open Source Community**: Thanks to the developers of Python libraries used in this project.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code as specified in the license.
