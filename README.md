# Institutional Determinants of Alumni Earnings

## Author(s) and Date of Submission

- **Author:** Sai Pranav Sripathi  
- **Date of Submission:** December 8, 2025

## Project Structure

- `data/`  
  Folder for the U.S. College Scorecard institutional data file(s) used in the analysis  
  (e.g. `MERGED2020_21_PP.csv`). Large raw data files may be excluded from version control.

- `Math261_Project2.qmd`  
  Quarto document containing the full analysis and project report, including code, figures, and text.

- `Math261_Project2.pdf`  
  Compiled version of the project report for submission.

- `references.bib`  
  BibTeX file containing references for R, College Scorecard documentation, and related literature cited in the paper.

- `.gitignore`  
  Specifies files and folders excluded from version control (e.g. temporary files, local data exports).

## Description

This project analyzes U.S. College Scorecard institution-level data to investigate which observable institutional characteristics are associated with higher median alumni earnings ten years after entry.

Using linear regression and LASSO regression, the project studies how alumni earnings relate to:

- Instructional expenditures per full-time equivalent (FTE) student  
- Admissions selectivity (admission rate, SAT scores)  
- Student financial aid composition (e.g., Pell Grant share)  
- Institution size  
- Program mix (shares of completions in Engineering, Computer Science, Business, Biological Sciences, etc.)

The analysis evaluates model fit and predictive performance using a train/test split, examines residual diagnostics, and constructs prediction intervals to quantify the uncertainty in earnings predictions.

## Use of External Resources (including LLMs)

External resources were used in this project as follows:

- **LLM-based tools : ChatGPT**  
  - Used for feedback on writing quality and organization of the report.  

## License for Dataset

The data used in this project come from the **U.S. Department of Education College Scorecard**: (https://collegescorecard.ed.gov/data/)
- Institution-level data files (including the 2020–21 file used here) are publicly available for research and analysis.

According to the College Scorecard data catalog, the dataset is intended for public access and use; licensing details and any additional restrictions are provided on the official data and documentation pages.
