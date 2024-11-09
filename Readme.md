# Student Performance Visualization and Insights Analysis

### Overview
This project analyzes a dataset on student performance, using data visualization to uncover key insights into student scores across subjects like math, reading, and writing, as well as the impact of factors such as gender, parental education, and test preparation status. Developed during my internship at Go2Cod, this project demonstrates the use of Python libraries to generate visual insights that can help inform educational strategies.

### Table of Contents
- [Project Summary](#project-summary)
- [Technologies Used](#technologies-used)
- [Dataset Overview](#dataset-overview)
- [Key Visualizations and Insights](#key-visualizations-and-insights)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Acknowledgments](#acknowledgments)

## Project Summary
The main goal of this project is to turn raw student data into actionable insights through data visualization. We utilized various types of plots and charts to:
- Highlight score trends and distributions,
- Understand the influence of demographic factors,
- Examine relationships between different subjects.

By examining student performance visually, we can see patterns that might suggest where to focus support efforts in education and how factors like preparation or family background impact scores.

## Technologies Used
- **Python** for data analysis and visualization
- **Jupyter Notebook** for code execution and documentation
- **Libraries**:
  - **Pandas** for data handling
  - **Matplotlib** and **Seaborn** for data visualization
  - **Plotly** for interactive visualizations

## Dataset Overview
The dataset includes the following fields:
- **Math score**: Numeric scores in math
- **Reading score**: Numeric scores in reading
- **Writing score**: Numeric scores in writing
- **Gender**
- **Race/Ethnicity**
- **Parental education level**
- **Lunch type** (standard/reduced)
- **Test preparation status** (completed/not completed)

**Note**: The dataset used is `dataset.csv`, which should be placed in the project directory.

## Key Visualizations and Insights

### 1. Average Scores by Gender (Bar Chart)
   - **Goal**: Compare average scores across subjects for male and female students.
   - **Insight**: Female students tend to perform better in reading and writing, while males slightly excel in math. This may suggest subject-specific strengths based on gender.

### 2. Test Preparation and Math Scores (Box Plot)
   - **Goal**: Show how completing a test preparation course affects math scores.
   - **Insight**: Students who completed the test preparation course generally scored higher in math. This suggests that preparation programs could improve performance.

### 3. Parental Education Level vs. Student Performance (Line Chart)
   - **Goal**: Explore how parental education level influences student scores.
   - **Insight**: Higher parental education levels correlate with improved scores, especially in reading and writing. This trend emphasizes the role of family background in student performance.

### 4. Gender Distribution (Pie Chart)
   - **Goal**: Show the proportion of male and female students.
   - **Insight**: The dataset is fairly balanced in terms of gender, supporting the reliability of gender-based insights.

### 5. Math Score Distribution (Histogram)
   - **Goal**: Visualize the distribution of math scores.
   - **Insight**: Math scores are normally distributed but skewed slightly lower, indicating that while most students are average, some could benefit from additional math support.

### 6. Reading vs. Writing Scores by Gender (Scatter Plot)
   - **Goal**: Explore the relationship between reading and writing scores by gender.
   - **Insight**: There’s a strong correlation between reading and writing scores, with females tending toward higher scores in both. Improving one literacy skill may positively affect the other.

### 7. Math vs. Reading Scores with Regression Line (Joint Plot)
   - **Goal**: Investigate the relationship between math and reading scores.
   - **Insight**: A positive correlation exists between math and reading scores, suggesting that students strong in one area often perform well in others.

### 8. Math vs. Reading Density (Joint Grid with Hexbin and KDE Marginals)
   - **Goal**: Show density of math and reading scores.
   - **Insight**: Most students fall within a mid-range concentration for both math and reading. High performers in one tend to do well in the other, indicating interconnected academic skills.

### 9. Correlation Between Scores (Heatmap)
   - **Goal**: Assess relationships between math, reading, and writing scores.
   - **Insight**: Strong positive correlations between reading and writing scores indicate interdependent literacy skills.

### 10. Parental Education Level Distribution (Treemap)
   - **Goal**: Display the distribution of parental education levels.
   - **Insight**: Visualizing education levels shows common levels and how they may link to student performance.

## Setup and Installation

### Prerequisites
Ensure Python 3.x is installed. You’ll also need Jupyter Notebook to run the analysis.

1. **Clone this repository**:
   ```bash
   git clone https://github.com/tony-stone-code/GO2COD_DS_03.git
