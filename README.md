# Student Performance Factors Analysis

This repository contains an analysis of the dataset titled **"Student Performance Factors"**, which is sourced from Kaggle. The objective of this project is to explore and analyze various factors affecting student performance, identifying key patterns and correlations.

## Dataset

The dataset used in this analysis is available on Kaggle:

- [Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)

It includes a range of features that may influence academic performance, such as demographic information, personal habits, and study-related factors.

## Objective

The main goals of this analysis are:
1. To identify significant factors influencing student performance.
2. To analyze how various features such as study habits, health, and social factors relate to academic outcomes.
3. To provide insights and recommendations for improving student performance.

## Features in the Dataset
The dataset includes the following key features:

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
## Analysis Process

1. **Data Cleaning**: Handle missing data, outliers, and incorrect data entries.
2. **Exploratory Data Analysis (EDA)**: Visualize and explore relationships between various features and student performance.
3. **Statistical Analysis**: Apply correlation analysis and hypothesis testing to identify significant factors.
4. **Modeling**: Use regression models to predict student performance based on different features.
5. **Conclusions & Insights**: Summarize key findings and provide actionable recommendations.

## Technologies Used

- **Python**: Programming language for data analysis.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computing.
- **Matplotlib** and **Seaborn**: Data visualization libraries.
- **Scikit-learn**: Machine learning library for predictive modeling.

## Results

The key findings of the analysis are presented in the final report. They include:
- The impact of study time on student grades.
- The influence of family and school support on academic outcomes.
- The correlation between health status and student performance.

## How to Run the Project

To run the analysis on your local machine, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/PstarH/student-performance-factor-analysis
    ```
2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the main.py
    ```bash
    python main.py
    ```

## Conclusion

This project demonstrates the use of data analysis techniques to uncover important factors influencing student performance. Further improvements can be made by integrating more advanced machine learning models to enhance predictive capabilities.

## Acknowledgements

- Thanks to the original author of the dataset, [Lai Nguyen](https://www.kaggle.com/lainguyn123), for making the dataset available.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
