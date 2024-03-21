# Project Overview
This project is a comprehensive analysis of district-wide standardized test results for a city's school district. The primary objective is to provide actionable insights into school performance metrics. These insights will assist the school board and mayor in making informed decisions regarding future school budgets, resource allocation, and strategic priorities.

The analysis covers a wide range of key metrics, including average math and reading scores, passing rates in math and reading, overall passing rates, budget analysis per school, school size analysis, and comparisons of performance based on spending per student. By conducting this analysis, we aim to identify trends, patterns, and areas for improvement within the school district.

## Project Structure
The project is structured into several key components to ensure a systematic and thorough analysis:

1. **Data Collection and Preparation**:
   - Data is sourced from CSV files (*schools_complete.csv* and *students_complete.csv*) containing information about schools and students, respectively.
   - Pandas is used to import, clean, and preprocess the data for analysis.

2. **District Summary**:
   - Calculates and presents a high-level snapshot of the district's key metrics, including total schools, total students, total budget, average scores, and passing rates.

3. **School Summary**:
   - Generates a detailed summary of each school's performance metrics, such as budget per student, average scores, passing rates, and overall passing rates.

4. **Top and Bottom Performing Schools**:
   - Identifies the top-performing and bottom-performing schools based on overall passing rates.

5. **Math and Reading Scores by Grade**:
   - Analyzes and presents average math and reading scores for students in each grade level (9th, 10th, 11th, 12th) at each school.

6. **Scores by School Spending**:
   - Categorizes schools based on average spending per student and analyzes performance metrics within each spending range.

7. **Scores by School Size**:
   - Classifies schools based on size (small, medium, large) and examines performance metrics for each size category.

8. **Scores by School Type**:
   - Compares performance metrics between different school types (charter vs. district) to identify any significant differences.

9. **Conclusion and Recommendations**:
   - Provides a conclusion based on the analysis findings and offers actionable recommendations for improving school performance and resource allocation strategies.

## Repository Structure
The repository is organized as follows:

1. **PyCitySchools Folder**:
   - Contains the main Jupyter notebook script for analysis (*PyCitySchools_starter.ipynb*).
   - **Resources Folder**
     - Contains the CSV files necessary for the analysis (*schools_complete.csv* and *students_complete.csv*).

This structured approach allows for efficient data analysis, visualization, and reporting of key insights derived from the district-wide standardized test results.

## Tools Used
The tools utilized in this project include:

- Python: Programming language used for data analysis and manipulation.
- Pandas Library: Used for data manipulation, cleaning, and analysis.
- Jupyter Notebook: Interactive environment for running Python code and analyzing data.
- Matplotlib: Library for data visualization and plotting.
- NumPy: Library for numerical computations and array operations.

## Conclusion
The pandas-challenge project aims to provide comprehensive insights into school performance metrics, enabling stakeholders to make data-driven decisions for improving educational outcomes and resource allocation within the city's school district.
