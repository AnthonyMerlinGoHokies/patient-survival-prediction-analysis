# Patient Survival Prediction Analysis 

A comprehensive exploratory data analysis of hospital patient survival patterns using 91,713 medical records. This Excel-based analysis identifies critical mortality risk factors and provides actionable insights for healthcare decision-making.

## Key Findings

### Overall Statistics
- **Dataset Size:** 91,713 patient records
- **Overall Mortality Rate:** 8.63%
- **Data Completeness:** 97.45%

### Critical Insights

#### 1. ICU Type Mortality Variations
- **Highest Risk:** MICU (Medical ICU) - **12.09% mortality**
- **Moderate Risk:** Cardiac ICU - **10.34% mortality**
- **Lowest Risk:** CSICU (Cardiac Surgery ICU) - **5.51% mortality**

#### 2. Age as Primary Risk Factor
| Age Group | Mortality Rate | Risk Level |
|-----------|----------------|------------|
| 18-37     | 3.45%         | Low        |
| 38-57     | 5.39%         | Moderate   |
| 58-77     | 8.86%         | High       |
| 78-97     | **13.06%**    | Critical   |

#### 3. Surgery Type Impact
- **Elective Surgery:** 3.09% mortality (Planned procedures)
- **Non-Elective:** 9.88% mortality (**3x higher risk**)

## Analysis Methodology

### Data Quality Assessment
- Comprehensive missing value analysis across 85 variables
- Data completeness scoring and validation
- Outlier identification and handling recommendations

### Statistical Analysis
- Pivot table analysis for categorical variables
- Mortality rate calculations by risk factors
- Cross-tabulation of key variables

### Key Variables Analyzed
- **Demographics:** Age, Gender, Ethnicity, BMI
- **Clinical:** ICU Type, Admission Source, Surgery Type
- **Outcomes:** Hospital Death (Primary Target Variable)

## Business Impact

### Healthcare Applications
1. **Resource Allocation:** Higher staffing for high-risk ICU types (MICU)
2. **Risk Stratification:** Age-based mortality prediction models
3. **Surgical Planning:** Evidence for elective surgery benefits
4. **Quality Improvement:** Targeted interventions for high-risk groups

### Clinical Insights
- Age remains the strongest predictor of mortality
- Emergency admissions carry significantly higher risk
- ICU specialization impacts patient outcomes
- Comprehensive data collection enables better predictions

## Tools & Technologies

- **Primary Analysis:** Microsoft Excel
- **Techniques:** Pivot Tables, Statistical Analysis, Data Profiling
- **Data Size:** 31.41 MB dataset with 91K+ records
- **Variables:** 85 clinical and demographic features

## Data Overview

The analysis uses a comprehensive hospital dataset featuring:
- **Patient Demographics:** Age, gender, ethnicity, BMI
- **Clinical Measures:** Vital signs, lab values, medical history
- **Administrative Data:** ICU types, admission sources, length of stay
- **Outcome Variable:** In-hospital mortality (binary classification)

## Future Enhancements

- **Machine Learning Models:** Implement predictive algorithms
- **Interactive Dashboards:** Create dynamic visualizations
- **Real-time Scoring:** Develop mortality risk calculators
- **External Validation:** Test findings on additional datasets

## How to Use This Analysis

1. **Healthcare Professionals:** Review findings for clinical insights
2. **Data Scientists:** Use methodology for similar healthcare analyses
3. **Researchers:** Reference statistical approaches and findings
4. **Students:** Learn Excel-based healthcare data analysis

## Contributing

Interested in extending this analysis? Areas for contribution:
- Additional statistical tests
- Machine learning model development
- Interactive visualization creation
- Clinical interpretation validation

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Feel free to reach out for questions about the methodology or findings!

---

*This analysis demonstrates the power of thorough exploratory data analysis in uncovering actionable healthcare insights from large-scale medical datasets.*
