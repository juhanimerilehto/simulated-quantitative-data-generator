# Student Well-being Data Generator

**Version 1.0**
### Creator: Juhani Merilehto - @juhanimerilehto - Jyväskylä University of Applied Sciences (JAMK), Likes institute

![JAMK Likes Logo](./assets/likes_str_logo.png)

## Overview

Student Well-being Data Generator is a Python-based tool for creating realistic simulated datasets for academic research in physical activity and well-being studies. Developed for the Strategic Exercise Information and Research unit in Likes Institute, at JAMK University of Applied Sciences, this tool generates comprehensive datasets suitable for various statistical analyses including t-tests, ANOVA, regression analyses, and non-parametric tests.

## Features

- **Comprehensive Dataset Generation**: Creates realistic student well-being data including:
  - Demographic information
  - Physical activity metrics
  - Mental well-being scores
  - Academic performance indicators
  - Lifestyle and social engagement metrics
  - Intervention group assignments

- **Formatted Excel Output**: 
  - Multiple worksheets (Data, Data Dictionary, Summary Statistics)
  - Professional formatting with headers and column widths
  - Automated statistical summaries

- **Data Quality Controls**:
  - Realistic value ranges and distributions
  - Proper data types for each variable
  - Built-in random seed for reproducibility

- **Documentation**:
  - Comprehensive data dictionary
  - Automated summary statistics
  - Clear variable descriptions and value ranges

## Hardware Requirements

- **Python:** 3.8 or higher
- **RAM:** 4GB recommended
- **Storage:** 100MB free space
- **OS:** Windows 10/11, MacOS, or Linux

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/juhanimerilehto/student-wellbeing-generator.git
cd student-wellbeing-generator
```

### 2. Create a virtual environment:
```bash
python -m venv data-env
source data-env/bin/activate  # For Windows: data-env\Scripts\activate
```

### 3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Basic usage:
```bash
python generate_data.py
```

The script will create an Excel file named 'student_wellbeing_dataset.xlsx' with three sheets:
1. **Data**: Main dataset with 500 participants
2. **Data Dictionary**: Variable descriptions and metadata
3. **Summary Statistics**: Automated statistical summaries

## Data Structure

The generated dataset includes:

### Demographic Variables:
- Age (18-25)
- Gender (Male, Female, Non-binary)
- Year of Study (1-4)

### Physical Activity Metrics:
- Weekly Exercise Hours
- Primary Exercise Type
- Exercise Intensity
- Fitness Scores (Pre/Post)

### Well-being Measures:
- Stress Level (0-100)
- Anxiety Score (0-100)
- Life Satisfaction (0-100)

### Academic Performance:
- GPA (0-4.0)
- Study Hours per Week

### Lifestyle Factors:
- Sleep Patterns
- Screen Time
- Social Activities
- Club Membership

## File Structure

```plaintext
student-wellbeing-generator/
├── assets/
│   └── likes_str_logo.png
├── excel-data-generator.py
├── requirements.txt
└── README.md
```

## Credits

- **Juhani Merilehto (@juhanimerilehto)** – Specialist, Data and Statistics
- **JAMK Likes** – Organization sponsor

## License

This project is licensed for free use under the condition that proper credit is given to Juhani Merilehto (@juhanimerilehto) and JAMK Likes institute. You are free to use, modify, and distribute this project, provided that you mention the original author and institution and do not hold them liable for any consequences arising from the use of the software.