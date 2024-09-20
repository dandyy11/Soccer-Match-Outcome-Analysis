# Soccer-Match-Outcome-Analysis
The analysis focuses on match outcomes (home win or not), goals scored by home and away teams, and the correlation between match outcomes and performance metrics. The project employs descriptive analysis, correlation analysis, and predictive modeling using a Random Forest classifier to predict match outcomes.

### Dataset
- **EPL Match Data:** A dataset containing 6,840 football matches with attributes such as home goals, away goals, team form, goal difference, and match outcomes.

### Objectives
1. **Descriptive Analysis:** Provide summary statistics on the number of matches, goals scored, and match outcomes (home win or not home win).
2. **Correlation Analysis:** Determine the relationship between home/away goals scored and the likelihood of a home win.
3. **Exploratory Data Analysis (EDA):** Use visualizations such as box plots to examine the distribution of goals scored by home and away teams based on the match outcome.
4. **Predictive Modeling:** Train a Random Forest model to predict match outcomes based on team performance metrics and evaluate model accuracy.

### Repository Structure
- `combined_analysis.Rmd` - R Markdown file containing the full analysis, including data loading, cleaning, EDA, and predictive modeling.
- `Detailed_Report.pdf` - PDF report with a comprehensive overview of the analysis and findings.
- `Summary.docx` - Word document summarizing the descriptive, diagnostic, and predictive analysis.
- `Match Outcome.png` - Visualizations of home and away goals scored by match outcome.

### Findings
1. **Descriptive Analysis:** 
   - Total Matches: 6,840
   - Total Goals Scored: 18,179
   - Average Home Goals per Match: 1.53
   - Average Away Goals per Match: 1.13
   - Home Wins: 46.43%, Not Home Wins: 53.57%
2. **Diagnostic Analysis:** 
   - Strong positive correlation between home goals scored and a home win (0.633).
   - Negative correlation between away goals scored and a home win (-0.496).
3. **Predictive Analysis:** 
   - The Random Forest model achieved an accuracy of 60.96% in predicting match outcomes (home win or not).

### Conclusion
The analysis provided insights into football match outcomes and scoring patterns for home and away teams. Through exploratory data analysis and Random Forest predictive modeling, the project offers useful insights into factors influencing match outcomes. These findings can help guide further analysis and strategy development in football match predictions.

### How to Use
To reproduce the analyses, clone this repository and open the R Markdown files (`.Rmd`). You can knit these files in RStudio to generate the HTML or Markdown outputs.
```bash
# Clone the repository
https://github.com/dandyy11/Soccer-Match-Outcome-Analysis.git

### Contact
For questions or suggestions, please contact Salman Imtiaz at salman.imtiaz414@gmail.com
