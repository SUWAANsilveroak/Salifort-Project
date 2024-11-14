# Employee Satisfaction and Retention Analysis

## Project Overview
The HR department at Salifort Motors is looking to improve employee satisfaction and reduce turnover. This project aims to analyze the provided HR dataset to uncover patterns and insights related to employee satisfaction, performance, and other work factors that may contribute to employee retention or attrition.

## Project Goals
- **Identify factors that influence employee turnover.**
- **Provide data-driven recommendations to enhance employee satisfaction.**
- **Determine key variables that predict whether an employee is likely to leave.**

## The HR Dataset
The dataset contains 14,999 rows and 10 columns. Below is a brief description of each variable:

| Variable | Description |
|----------|-------------|
| `satisfaction_level` | Employee-reported job satisfaction level (range: 0–1). |
| `last_evaluation` | Score of employee's last performance review (range: 0–1). |
| `number_project` | Number of projects the employee contributes to. |
| `average_monthly_hours` | Average number of hours the employee worked per month. |
| `time_spend_company` | Number of years the employee has been with the company. |
| `Work_accident` | Indicates whether the employee experienced a workplace accident. |
| `left` | Indicates if the employee left the company (1 for yes, 0 for no). |
| `promotion_last_5years` | Indicates if the employee was promoted in the last 5 years (1 for yes, 0 for no). |
| `Department` | The department where the employee works. |
| `salary` | The employee's salary level. |

## Key Findings
### 1. Satisfaction Level
- Employees with lower satisfaction levels are more likely to leave the company.
- A strong correlation exists between job satisfaction and turnover.

### 2. Performance Evaluation
- High and low performance scores show different trends in employee turnover.
- Employees with intermediate scores may have a higher risk of attrition.

### 3. Workload and Projects
- Analysis indicates that both extremely high and low average monthly hours contribute to higher turnover rates.
- The number of projects can also affect employee satisfaction, with both overworked and underworked employees displaying higher chances of leaving.

### 4. Time Spent at the Company
- Employees with certain years of tenure are more prone to leaving, suggesting that turnover risk is not uniform across all experience levels.

### 5. Salary and Promotions
- Employees with low salary levels and few promotions in recent years are more inclined to leave.
- Departments with higher attrition rates often coincide with lower salary bands.

## Recommendations
- **Enhance Job Satisfaction**: Implement employee feedback mechanisms to address dissatisfaction.
- **Monitor Workload**: Balance project assignments to avoid overworking employees.
- **Recognition and Growth**: Increase the frequency of performance-based promotions and recognition programs.
- **Salary Adjustments**: Consider salary adjustments for employees in low-paying positions to improve retention.

## Further Reading
For detailed documentation and a complete analysis, please refer to the [Sali-project-report.pdf](https://github.com/SUWAANsilveroak/Salifort-Project/blob/master/Sali-project-report.pdf) in the GitHub repository.

## Technologies Used
- **Python**: For data analysis and visualization (Pandas, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**: For exploratory data analysis and documentation
- **Git**: Version control
- **GitHub**: Project hosting

## How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SUWAANsilveroak/Salifort-Project.git
