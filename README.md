# Culture Shocked: Student Mental Health Abroad
## Overview
This project explores the mental health challenges faced by international students, focusing on social connectedness and acculturative stress. The analysis is based on data from a study conducted by a Japanese international university in 2018, which was approved by several ethical and regulatory boards. The study found that international students are at a higher risk of mental health difficulties compared to the general population.

Using PostgreSQL, this project aims to validate whether social connectedness, acculturative stress, and length of stay influence depression among international students.

## Objective
- To explore whether international students face unique mental health challenges as compared to domestic students.
- To analyze if social connectedness and acculturative stress are significant predictors of depression.
- To determine if the length of stay affects the mental health outcomes of international students.

## Data Source
The dataset comes from a 2018 study conducted at a Japanese international university, focusing on international students' mental health. The survey data includes information on students' social support, acculturative stress, depression levels, and length of stay in the host country.

## Tools Used
- PostgreSQL for data exploration and analysis
- Jupyter Notebook for executing SQL queries and visualizing findings

## Key Findings
- International students report higher acculturative stress and similar levels of depression as domestic students.
- Social connectedness helps lower depression and enhances the sense of belonging.
- Loneliness is linked to higher levels of depression and acculturative stress.
- While social media and phones can improve connections, they may also contribute to stress.
- The length of stay is a contributing factor, with longer stays leading to better adjustment but also potential stress.


## Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/cultureshock-unpacking-minds.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Load data into PostgreSQL:
    ```bash
    psql -U your-username -d your-database -f students_data.sql
    ```
4. Run the analysis in Jupyter Notebook:
    ```bash
    jupyter notebook analysis.ipynb
    ```

