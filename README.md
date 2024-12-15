# Student_Performance_EDA
Project Overview

This project is an exploratory data analysis (EDA) of a dataset related to student performance. The primary goal is to uncover patterns and insights that may influence academic outcomes. The analysis includes understanding the data, preparing it for visualization, and interpreting key trends.

## Features of the Dataset

#### The dataset contains the following columns:

- StudentID: Unique identifier for each student.

- Age: Age of the student.

- Gender: Gender of the student (encoded numerically).

- Ethnicity: Ethnic background (categorical).

- ParentalEducation: Level of education attained by the parents (categorical).

- StudyTimeWeekly: Average hours of study per week.

- Absences: Number of absences.

- Tutoring: Participation in tutoring sessions (binary).

- ParentalSupport: Level of parental support (categorical).

- Extracurricular: Participation in extracurricular activities (binary).

- Sports: Participation in sports activities (binary).

- Music: Participation in music activities (binary).

- Volunteering: Participation in volunteering activities (binary).

- GPA: Grade Point Average.

- GradeClass: Final classification of grades (categorical).

## Project Structure

### The project is organized into the following sections:

Data Understanding

- Importing libraries and loading the dataset.

- Previewing the dataset to understand its structure and content.

Data Preparation

- Handling missing values and outliers.

- Transforming and encoding categorical variables if needed.

Data Visualization

- Visual exploration of key variables such as GPA, study time, and parental support.

- Correlation analysis and heatmaps.

- Distribution plots for numeric variables and bar plots for categorical variables.


Requirements

The project requires the following Python libraries:

- pandas

- matplotlib

- seaborn

- numpy

### Insights Gained

Correlation between study time and GPA: A positive relationship was observed.

Impact of extracurricular activities: Students involved in music and sports tend to have higher GPAs.

Role of parental support: Higher levels of parental support are associated with better academic performance.

Future Improvements

Incorporate machine learning models to predict GPA or grade classification based on the input features.

Enhance data visualization using interactive tools like Plotly or Tableau.

Include more advanced statistical analysis to validate hypotheses.
