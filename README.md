# Social Media Addiction Analysis

A comprehensive data analysis project examining social media addiction patterns among students across various demographics and behavioral indicators.

##  Project Overview

This project analyzes a dataset of 705 students to understand the relationship between social media usage and various factors including academic performance, mental health, sleep patterns, and addiction levels. The analysis provides insights into how different demographics and usage patterns correlate with social media addiction.

##  Objectives

- Analyze social media usage patterns among students
- Identify correlations between social media usage and academic performance
- Examine the impact of social media on mental health and sleep
- Understand addiction patterns across different demographics
- Visualize key trends and relationships in the data

##  Dataset Description

The dataset contains **705 student records** with the following features:

### Features

| Column Name | Type | Description |
|------------|------|-------------|
| **Student_ID** | Integer | Unique identifier for each student |
| **Age** | Integer | Student age (18-24 years) |
| **Gender** | Categorical | Male/Female |
| **Academic_Level** | Categorical | High School, Undergraduate, Graduate |
| **Country** | Categorical | Student's country (110 different countries) |
| **Avg_Daily_Usage_Hours** | Float | Average daily social media usage in hours (1.5-8.5) |
| **Most_Used_Platform** | Categorical | Primary social media platform (12 platforms) |
| **Affects_Academic_Performance** | Binary | Yes/No - Whether social media affects academics |
| **Sleep_Hours_Per_Night** | Float | Average sleep hours per night (3.8-9.6) |
| **Mental_Health_Score** | Integer | Mental health rating (4-9 scale) |
| **Relationship_Status** | Categorical | Single, In Relationship, Complicated |
| **Conflicts_Over_Social_Media** | Integer | Number of conflicts (0-5) |
| **Addicted_Score** | Integer | Social media addiction score (2-9) |

### Key Statistics

- **Total Students**: 705
- **Age Range**: 18-24 years
- **Average Daily Usage**: 4.92 hours
- **Average Sleep**: 6.87 hours/night
- **Average Mental Health Score**: 6.23/9
- **Average Addiction Score**: 6.44/9
- **No Missing Values**: Complete dataset with 100% data integrity

### Social Media Platforms Analyzed

The dataset includes 12 different platforms:
- Instagram
- Twitter
- TikTok
- YouTube
- Facebook
- WhatsApp
- VKontakte
- And others

##  Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization

##  Notebook Structure

The analysis is organized in the following sections:

1. **Data Loading & Exploration**
   - Import required libraries
   - Load the dataset
   - Initial data inspection

2. **Data Quality Check**
   - Check for missing values
   - Data type verification
   - Basic statistics

3. **Exploratory Data Analysis**
   - Distribution analysis of numerical features
   - Visualization of key relationships
   - Statistical summaries

##  Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn
```

### Running the Analysis

1. Clone this repository or download the notebook
2. Ensure you have the dataset file: `Students Social Media Addiction.csv`
3. Update the file path in the notebook if needed
4. Run all cells in sequence

### Using Google Colab

1. Upload the notebook to Google Colab
2. Upload the dataset CSV file to Colab
3. Update the path in the notebook: `/content/Students Social Media Addiction.csv`
4. Run all cells

##  Key Analysis Areas

### 1. Usage Patterns
- Distribution of daily social media usage
- Platform preferences by demographic
- Peak usage patterns

### 2. Academic Impact
- Correlation between usage hours and academic performance
- Analysis by academic level
- Impact of specific platforms

### 3. Health & Wellbeing
- Relationship between usage and sleep hours
- Mental health score correlations
- Addiction score analysis

### 4. Demographics
- Age-based patterns
- Gender differences in usage
- Geographic variations (110 countries)

### 5. Social Relationships
- Relationship status impact
- Conflict patterns
- Social dynamics

##  Expected Insights

This analysis can help answer questions such as:
- What is the average social media usage among students?
- How does social media usage affect academic performance?
- Is there a correlation between usage hours and sleep quality?
- Which platforms are most popular among different demographics?
- What are the key indicators of social media addiction?
- How does relationship status relate to social media conflicts?

##  Data Quality

-  **No missing values** - 100% complete dataset
-  **Consistent data types** - Proper numerical and categorical encoding
-  **Reasonable ranges** - All values within expected bounds
-  **Diverse sample** - 110 countries, balanced demographics

##  Notes

- The dataset represents students aged 18-24 from 110 different countries
- Addiction scores range from 2-9, with higher scores indicating higher addiction
- Mental health scores are self-reported on a 4-9 scale
- The analysis focuses on correlation, not causation

##  Contributing

Feel free to fork this project and add your own analyses or visualizations. Some ideas:
- Advanced statistical testing (correlation matrices, hypothesis testing)
- Machine learning models to predict addiction scores
- Interactive visualizations using plotly
- Time series analysis if temporal data becomes available
- Comparative analysis across countries or regions

##  License

This project is available for educational and research purposes.

##  Author

Data analysis project for understanding social media addiction patterns among students.

##  Contact

For questions or suggestions regarding this analysis, please open an issue in the repository.

---

**Last Updated**: 2024

*This analysis is part of a broader study on digital wellbeing and student behavior in the age of social media.*
