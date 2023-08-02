# Pymaceuticals, Inc. - Squamous Cell Carcinoma Study

## Overview

Welcome to the Pymaceuticals, Inc. Squamous Cell Carcinoma (SCC) Study! In this analysis, we explored a dataset of mice treated with various drug regimens to investigate their effectiveness in reducing tumor volume in SCC. The goal of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

## Dataset Description

The dataset consists of two main files:

1. `mouse_metadata.csv`: This file contains metadata about the mice involved in the study, including Mouse ID, Drug Regimen, Sex, Age (in months), and Weight (in grams).
2. `study_results.csv`: This file contains the study results, including the Mouse ID, Timepoint, and Tumor Volume (in cubic millimeters) for each mouse throughout the study.

## Analysis Tasks

The analysis covered the following tasks:

1. Data Preparation: The mouse metadata and study results were merged into a single DataFrame. Duplicate mice and time points were removed to ensure data integrity.

2. Summary Statistics: Summary statistics were calculated for each drug regimen, including mean, median, variance, standard deviation, and standard error of the tumor volume.

3. Treatment Comparison: Bar charts were used to visualize the total number of mice for each drug regimen throughout the study.

4. Gender Distribution: Pie charts were used to display the distribution of female and male mice in the study.

5. Treatment Efficacy: Box plots were generated to illustrate the final tumor volume distribution for the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin).

6. Individual Mouse Response: Line plots were used to observe the tumor volume change over time for a single mouse treated with Capomulin.

7. Mouse Weight vs. Tumor Volume: A scatter plot and a linear regression model were used to investigate the correlation between mouse weight and the average observed tumor volume for the entire Capomulin regimen.

## Key Findings

- Capomulin and Ramicane showed promising results in reducing tumor volume, outperforming Infubinol and Ceftamin.
- Infubinol had one potential outlier with a tumor volume of 36.32 mm3.
- The study included a balanced representation of female and male mice, providing reliable results across genders.
- There was a positive correlation between mouse weight and tumor volume in mice treated with Capomulin.

## Recommendations

- Based on the study results, Capomulin and Ramicane should be prioritized for further research and potential clinical trials.
- Continued monitoring of tumor volume and individual mouse response to treatment is essential to assess long-term effectiveness and safety.
- Further investigations into the potential outlier in the Infubinol group may be warranted to understand its impact on treatment outcomes.

## Limitations

- The study is based on animal models and may not fully represent human responses to treatments.
- The study duration of 45 days may not capture long-term treatment effects.
- Additional experiments and clinical trials are required to validate the findings in human patients.

## Getting Started

To run the analysis, you will need the following dependencies:

- Python 3
- pandas
- matplotlib
- scipy

You can install the required dependencies using the following command:

```bash
pip install pandas matplotlib scipy
```

To reproduce the analysis, you can use the provided Jupyter Notebook or Python script.
