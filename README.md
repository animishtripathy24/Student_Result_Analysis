
# Student Result Analysis

This project aims to analyze the results of students using various data analysis and visualization libraries such as Pandas, Seaborn, and Matplotlib. Through this analysis, we draw several conclusions about the factors affecting student performance.


## Table of Content
[Introduction](#introduction)
- [Libraries Used](#libraries-used)
- [Dataset](#dataset)
- [Analysis](#analysis)
  - [Gender Distribution](#gender-distribution)
  - [Impact of Parent Education on Scores](#impact-of-parent-education-on-scores)
  - [Impact of Parent Marital Status on Scores](#impact-of-parent-marital-status-on-scores)
  - [Subject Difficulty](#subject-difficulty)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
## Introduction
In this project, we perform exploratory data analysis (EDA) on a student results dataset. Our goal is to uncover insights about the demographic and socio-economic factors that influence student performance. We use visualizations to support our findings and provide clear conclusions based on the data.
## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **Seaborn**: For statistical data visualization.
- **Matplotlib**: For creating static, animated, and interactive visualizations.

## Dataset
The dataset contains information on students' scores in various subjects along with demographic and socio-economic factors such as gender, parent education level, and parent marital status.
## Analysis
### Gender Distribution
We analyzed the gender distribution of students and found that the number of females is higher than that of males.

### Impact of Parent Education on Scores
We visualized the distribution of parent education levels and their impact on student scores. From the charts, we concluded that the education of parents has a positive impact on their children's education.

### Impact of Parent Marital Status on Scores
We analyzed the impact of parents' marital status on student scores and concluded that there is no or negligible impact on the students' scores due to their parents' marital status.

### Subject Difficulty
We created boxplots to compare scores across different subjects and concluded that mathematics is comparatively more difficult to score in than other subjects.
## Conclusion
Our analysis revealed several insights:
- The number of female students is higher than that of male students.
- Higher parent education levels are associated with better student performance.
- Parent marital status has little to no impact on student scores.
- Mathematics is a more challenging subject for students compared to others.
## How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/animishtripathy24/Student_Result_Analysis
2. Navigate to the project directory:
    ```sh
    cd Student_Result_Analysis

3. Install the required libraries:
    ```sh
    pip install pandas seaborn matplotlib
4. Start Jupyter Notebook:
    ```sh
    jupyter notebook