# NREC4107 Chapter Audit

Audit date: 2026-06-12

Scope: `part-i/` through `part-vi/`, chapters 01-32 only. Landing pages were read for context but are not scored as chapters.

Exam alignment note: no separate midterm, make-up, or final exam files were found in the active repository. Exam alignment below is therefore inferred from the course sequence, repeated emphasis, chapter placement, and final-project materials. Inferred midterm coverage is strongest for data, visualization, and core regression foundations. Inferred make-up coverage likely mirrors the core regression and interpretation chapters. Inferred final coverage is strongest for econometric problems, diagnostics, prediction concepts, and the empirical project.

| Ch | Title | Pages/Length | Main Topic | Action | Reason | Notes |
|---:|---|---|---|---|---|---|
| 01 | Applied Econometrics | Short, 160 lines, 1 code block | Course framing, questions, data, interpretation, causality caution | Keep | Clear and well aligned with applied econometrics objectives. Minimal code and good conceptual framing. | Midterm light-to-medium. Keep as orientation; not a heavy exam chapter. |
| 02 | Data Types | Medium, 231 lines, 5 code blocks | Variable types, unit of observation, dependent and explanatory variables | Shorten | Important foundation, but repeats question framing from Ch 01 and later Ch 09/27. | Midterm medium. Move variable-type checklist to Dataset Integrity Checklist or Python Code Guide. |
| 03 | Python and Colab | Medium, 240 lines, 11 code blocks | Google Colab setup, imports, loading data, reproducibility | Move to Appendix | Mostly technical workflow rather than econometric reasoning. Better as Python Code Guide material. | Midterm light. Useful for access and setup, but not core exam content. |
| 04 | Data Cleaning | Long, 274 lines, 12 code blocks | Inspecting, cleaning, derived variables, saving prepared data | Shorten | Strong practical value but code-heavy and overlaps Ch 02, Ch 05, and Ch 28. | Midterm medium. Keep cleaning logic in chapter, move procedural checklist to Dataset Integrity Checklist. |
| 05 | Descriptive Statistics | Long, 298 lines, 14 code blocks | Summary statistics, frequency tables, missing values, IQR, correlations | Shorten | Important but too code-heavy and repeats data inspection from Ch 02/04. | Midterm heavy. Candidate for tighter applied interpretation plus formulas/checklist appendix. |
| 06 | Univariate Graphs | Long, 290 lines, 12 code blocks, 8 figures | Histograms, boxplots, bar charts, variable distributions | Keep | Clear applied graph chapter with strong visual support and limited theory burden. | Midterm medium. Some plotting code can later move to Python Code Guide. |
| 07 | Bivariate Graphs | Very long, 350 lines, 11 code blocks, 8 figures | Scatterplots, group comparisons, boxplots, crosstabs | Shorten | Useful but repetitive across graph types and overlaps Ch 09 research-question conversion. | Midterm medium-to-heavy. Preserve key price-volume and category examples. |
| 08 | Multivariate Graphs | Very long, 424 lines, 14 code blocks, 8 figures | Heatmaps, scatter matrix, multi-factor and interactive graphs | Move to Appendix | Too long and too code-heavy for core econometrics. Interactive treemap, sunburst, and 3D plots are likely not tested. | Midterm light. Best as optional visualization appendix or Python Code Guide. |
| 09 | Research Questions | Very long, 435 lines, 6 code blocks, 5 figures | Turning graphs into empirical questions and model ideas | Shorten | Very aligned with course goals, but repeats Ch 01/02/07 and is text-heavy. | Midterm medium. Keep the workflow; reduce repeated graph interpretations. |
| 10 | Simple Regression | Medium, 209 lines, 7 code blocks | OLS slope/intercept, fitted line, residuals, R-squared, causality caution | Keep | One of the core chapters; strong balance of code, results, and interpretation. | Midterm heavy and make-up heavy. Essential. |
| 11 | Hypothesis Testing | Medium, 168 lines, 5 code blocks | Standard errors, confidence intervals, t-tests, p-values | Keep | Central exam material and concise. Good statistical vs economic significance distinction. | Midterm heavy and make-up heavy. Essential. |
| 12 | Prediction and Fit | Medium, 163 lines, 7 code blocks | Fitted values, errors, R-squared, prediction vs explanation | Keep | Important bridge between regression and later prediction chapters. | Midterm heavy; final medium because it supports Part V. |
| 13 | Multiple Regression | Short, 143 lines, 2 code blocks | Controls, omitted variable bias, interpreting conditional effects | Keep | Compact, practical, and central to applied econometrics. | Midterm heavy and make-up heavy. Essential. |
| 14 | Functional Forms | Medium, 165 lines, 3 code blocks | Linear, quadratic, log-log, elasticity interpretation | Keep | Strong applied interpretation chapter with appropriate math level. | Midterm/final medium-to-heavy. Good exam candidate. |
| 15 | Dummy Variables | Medium, 196 lines, 2 code blocks | Categorical predictors, reference groups, dummy variable trap | Keep | Highly relevant for real datasets and project interpretation. | Midterm/final heavy. Could support practice questions. |
| 16 | Model Selection | Medium, 187 lines, 2 code blocks | Restricted/unrestricted models, F-tests, omitted/irrelevant variables | Keep | Important capstone for regression sequence. | Midterm/final heavy. Formula Sheet could include F-test logic. |
| 17 | Heteroskedasticity | Very long, 333 lines, 7 code blocks | Residual variance, Breusch-Pagan test, robust standard errors | Shorten | Core final topic, but too long and repetitive in common mistakes/interpreting steps. | Final heavy and likely make-up medium. Keep robust SE emphasis. |
| 18 | Autocorrelation | Very long, 323 lines, 8 code blocks | Time-series persistence, residual plots, Durbin-Watson, Newey-West | Shorten | Important but less central if course data are mostly cross-sectional. Simulation/code load is high. | Final medium. Could be lightly tested unless final includes time series. |
| 19 | Multicollinearity | Very long, 343 lines, 6 code blocks | Correlation among regressors, VIF, interpretation limits | Shorten | Useful and exam-relevant, but long for a concept students can learn with fewer examples. | Final heavy. VIF workflow belongs in Dataset Integrity Checklist. |
| 20 | Endogeneity | Very long, 403 lines, 3 code blocks | Omitted variables, simultaneity, measurement error, IV and 2SLS | Rewrite Later | Core concept but currently too technical and partly disconnected from available dataset; commented IV code weakens usability. | Final heavy conceptually, but IV implementation likely lightly tested. Needs applied NRE example. |
| 21 | Diagnostics | Very long, 413 lines, 6 code blocks | Model credibility, residuals, RESET, influence, robustness | Rewrite Later | Strong capstone idea but repeats Ch 17-20 and becomes a checklist plus multiple diagnostics. | Final heavy. Better as concise diagnostic framework plus appendix checklist. |
| 22 | Train Test Split | Medium, 223 lines, 5 code blocks, 1 figure | Train/test logic, unseen data, MAE, MSE, RMSE, overfitting | Keep | Clear and useful transition from regression fit to prediction. | Final medium. Not core traditional econometrics, but practical. |
| 23 | Econometrics vs ML | Medium, 218 lines, 3 code blocks, 1 figure | Explanation vs prediction; regression vs ML tradeoffs | Merge Later | Conceptual distinctions repeat Ch 12, Ch 22, and Ch 26. Could merge with Ch 22 or Ch 26. | Final light. Good orientation but not enough standalone tested content. |
| 24 | Trees and Forests | Medium, 234 lines, 4 code blocks, 1 figure | Decision trees, random forests, nonlinear prediction, importance | Keep | Good applied ML introduction with intuitive explanations. | Final light-to-medium. Keep if ML remains part of final scope. |
| 25 | Gradient Boosting | Long, 260 lines, 4 code blocks, 1 figure | Boosting, XGBoost, model comparison metrics | Move to Appendix | Useful but advanced relative to applied intermediate econometrics; dependency complexity is a sign it may be optional. | Final light. Better as optional ML extension or Python Code Guide example. |
| 26 | Feature Importance | Long, 265 lines, 5 code blocks, 1 figure | Feature importance, permutation importance, partial dependence, prediction limits | Merge Later | Strong caution against causal overinterpretation, but overlaps Ch 23 and Ch 24. | Final medium. Keep causal-warning content, possibly merge with Ch 23/24. |
| 27 | Research Question | Medium, 173 lines, 1 code block, 1 figure | Choosing focused project questions and hypotheses | Keep | Strong project alignment and practical student guidance. | Final project heavy. Not necessarily exam-heavy, but course-outcome heavy. |
| 28 | Data Section | Medium, 206 lines, 6 code blocks, 1 figure | Writing data section, source, unit, variables, limitations | Shorten | Valuable for project, but repeats Ch 02/04/05 data inspection. | Final project heavy. Move checklist to Empirical Project Checklist. |
| 29 | Methodology | Medium, 176 lines, 1 code block, 1 figure | Writing model and estimation-method sections | Keep | Strong alignment with final empirical project and concise. | Final project heavy. Good bridge from regression tools to writing. |
| 30 | Results and Discussion | Medium, 181 lines, 3 code blocks, 1 figure | Regression table interpretation and discussion writing | Keep | Very practical and well aligned with applied interpretation. | Final project heavy. Excellent candidate for grading rubric support. |
| 31 | Tables and Figures | Medium, 198 lines, 6 code blocks, 1 figure | Presenting tables, graphs, appendices, reproducibility | Move to Appendix | More of a production guide than a chapter; belongs in empirical project resources. | Final project medium. Useful but lightly exam-tested. |
| 32 | Article Template | Long, 276 lines, 1 code block, 1 figure | Full paper template, section templates, submission checklist | Move to Appendix | Valuable as a template, but template/checklist material is better outside the main chapter sequence. | Final project heavy but not exam content. Move to Empirical Project Checklist or article template appendix. |

## Executive Summary

The coursebook is coherent and practical, with a strong running milk-product dataset and a clear progression from data work to regression, econometric problems, prediction, and final project writing. The strongest core is Part III, where regression concepts are linked to actual model output and interpretation. The largest readability issue is that several chapters are too long for a website format, especially Ch 08, Ch 09, Ch 20, and Ch 21. The largest content-design issue is repetition: research-question framing appears in Ch 01, Ch 02, Ch 09, and Ch 27; data inspection appears in Ch 02, Ch 04, Ch 05, and Ch 28; prediction vs explanation appears in Ch 12, Ch 22, Ch 23, and Ch 26.

Exam alignment is difficult to verify because the repository does not contain explicit midterm, make-up, or final exam documents. Based on course sequence, the most heavily testable chapters are Ch 10-17 and Ch 19-21. The most lightly tested chapters are likely Ch 03, Ch 08, Ch 25, Ch 31, and Ch 32. Final-project alignment is strongest in Ch 27-32, even when some of that material may be better presented as appendices or checklists.

## Strongest Chapters

1. **Ch 10. Simple Regression** - Clear, central, and well balanced between model, output, plots, and interpretation.
2. **Ch 11. Hypothesis Testing** - Concise treatment of standard errors, confidence intervals, p-values, and economic significance.
3. **Ch 13. Multiple Regression** - Strong applied explanation of controls and omitted variable bias without excessive code.
4. **Ch 15. Dummy Variables** - Highly relevant for real agricultural and market datasets; strong treatment of reference groups.
5. **Ch 30. Results and Discussion** - Excellent practical chapter for translating output into empirical writing.

## Weakest Chapters

1. **Ch 08. Multivariate Graphs** - Too long and code-heavy; interactive plots are useful but likely optional.
2. **Ch 09. Research Questions** - Pedagogically valuable but very long and repeats earlier question-framing material.
3. **Ch 20. Endogeneity** - Important topic, but too technical and needs a cleaner applied NRE example.
4. **Ch 21. Diagnostics** - Strong idea but overextended; overlaps with Ch 17-20 and should become a tighter diagnostic framework.
5. **Ch 25. Gradient Boosting** - Advanced for the course level and better suited as optional ML extension material.

## Recommended Merges

- **Ch 01 + selected Ch 02 framing**: keep Ch 01 as orientation and move repeated data-type checklists into Ch 02 or appendix.
- **Ch 07 + selected Ch 09 examples**: merge graph-to-question examples into the bivariate/multivariate visualization sequence.
- **Ch 22 + Ch 23**: combine train/test logic with explanation-vs-prediction framing.
- **Ch 24 + selected Ch 25 model comparison**: keep tree/forest basics and make boosting an optional extension.
- **Ch 23 + Ch 26 caution sections**: combine prediction-vs-causation and feature-importance warnings.
- **Ch 31 + Ch 32**: convert to a final-project appendix containing tables, figures, article template, and checklist.

## Missing Topics

- **Sampling and data-generating processes**: students need clearer language on sampling, population, and external validity.
- **Causal research designs**: difference-in-differences, fixed effects, regression discontinuity, and matching are absent or only implied.
- **Panel data**: important for natural resource economics, agriculture, trade, climate, and policy datasets.
- **Limited dependent variables**: logit/probit or binary outcomes are useful for adoption, participation, and policy uptake questions.
- **Model validation beyond train/test split**: cross-validation is missing despite the ML sequence.
- **Natural Resource Economics examples**: water use, environmental valuation, fisheries, land use, climate risk, and resource policy applications could appear more often.
- **Research ethics and data documentation**: reproducibility is present, but citation, data provenance, and transparent limitations could be formalized.
- **Exam practice integration**: no explicit practice-question bank is visible in the active coursebook.

## Appendix Opportunities

- **Formula Sheet**: OLS equation, t-test, confidence interval, R-squared, RMSE/MAE/MSE, F-test, VIF, robust SE concept, Durbin-Watson, and elasticity formulas.
- **Python Code Guide**: Colab setup, imports, file paths, plotting templates, statsmodels workflow, scikit-learn train/test workflow, Random Forest, and optional boosting.
- **Exam Practice Questions**: interpretation of coefficients, p-values, confidence intervals, dummy variables, model comparison, robust SE, VIF, endogeneity, diagnostics.
- **Empirical Project Checklist**: research question, variable table, data section, methodology paragraph, results paragraph, table/figure standards, final submission checklist.
- **Dataset Integrity Checklist**: missing values, duplicates, unit of observation, constructed variables, categorical levels, outliers, data dictionary, reproducible cleaning log.
- **Visualization Appendix**: graph catalog from Ch 06-08, including code snippets and when each graph is appropriate.
- **ML Appendix**: XGBoost/gradient boosting, feature importance code, partial dependence, and prediction caveats.

## Priority Revision Order

1. Ch 08. Multivariate Graphs
2. Ch 09. Research Questions
3. Ch 20. Endogeneity
4. Ch 21. Diagnostics
5. Ch 25. Gradient Boosting
6. Ch 32. Article Template
7. Ch 17. Heteroskedasticity
8. Ch 19. Multicollinearity
9. Ch 18. Autocorrelation
10. Ch 04. Data Cleaning
11. Ch 05. Descriptive Statistics
12. Ch 07. Bivariate Graphs
13. Ch 26. Feature Importance
14. Ch 23. Econometrics vs ML
15. Ch 31. Tables and Figures
16. Ch 28. Data Section
17. Ch 03. Python and Colab
18. Ch 16. Model Selection
19. Ch 14. Functional Forms
20. Ch 15. Dummy Variables
21. Ch 13. Multiple Regression
22. Ch 12. Prediction and Fit
23. Ch 11. Hypothesis Testing
24. Ch 10. Simple Regression
25. Ch 27. Research Question
26. Ch 29. Methodology
27. Ch 30. Results and Discussion
28. Ch 24. Trees and Forests
29. Ch 22. Train Test Split
30. Ch 06. Univariate Graphs
31. Ch 02. Data Types
32. Ch 01. Applied Econometrics
