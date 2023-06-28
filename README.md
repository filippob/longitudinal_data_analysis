# Analysis of longitudinal data
Scripts for the analysis of longitudinal data in R

**Material for the Course "Introduction to the analysis of longitudinal data with R"**

Instructors: *Filippo Biscarini, Andreia Amaral*

This course will introduce students, researchers and professionals to the analysis of longitudinal data, i.e. data with a time component. The course will describe the main types of longitudinal data (e.g. treatments over timepoints, time series data), and a number of approaches to process and analyse such data.

Each day the course will start at **14:00** and end at **20:00** (CET).
As a general rule, we'll have a longer break (30 minutes) at about 17:00 and two shorter breaks (10-15 minutes) later on during the day (to be decided flexibly depending on the sessions).  

<!-- timetable: [here](https://docs.google.com/) -->

**Day 1**

- Lecture 0: General Introduction / Overview of the Course [Filippo]
    - [General Introduction](slides/1.introduction.pdf)
- Lecture 1: [Longitudinal data: examples and challenges](slides/1.introduction.pdf) [Filippo]
- Lab 1: First encounter with longitudinal data [Filippo]
    - [1.longitudinal_data.Rmd](day_1/1.longitudinal_data.Rmd)
- Lecture 2: [The basic experimental setting: treatments and timepoints](slides/2.treatments_and_timepoints.pdf) [Filippo]
- Lab 2: Treatments and timepoints in R [Filippo]
    - [2.1.treatments_and_timepoints.Rmd](day_1/2.1.treatments_and_timepoints.Rmd)
    - [2.2.exercise.Rmd](day_1/2.2.exercise.Rmd)
    - [2.3.linear_regression_with_tidymodels.Rmd](day_1/2.3.linear_regression_with_tidymodels.Rmd)
- Lecture 3: [Analysis of repeated records](slides/3.repeated_records.pdf) [Filippo]
- Lab 3: Models to analyse data with repeated records over time (multiple time points) and space (multiple locations) in R
    - [3.repeated_records.Rmd](day_1/3.repeated_records.Rmd)
- Lecture 4: [Difference-in-differences (diff-in-diff)](slides/3.difference_in_differences.pdf) [Filippo]
 
**Day 2**

- Lab 4: diff-in-diff in R
    - [4.diff-in-diff.Rmd](day_2/4.diff-in-diff.Rmd)
- Lecture 5: Censored data and survival analysis
- Lab 5: Survival analysis in R
    - [5.survival_analysis.Rmd](day_2/5.survival_analysis.Rmd)
- Lecture 6: Cross-validation: simple and with spatial, temporal (or other) data structure
- Lab 6: Cross-validation strategies in R
    - [6.1.cross_validation.Rmd](day_2/6.1.cross_validation.Rmd)
    - [6.2.block_cross_validation.Rmd](day_2/6.2.block_cross_validation.Rmd)
- Lecture 7: Time series and forecasting
- Lab 7: Time series and forecasting in R
    - [7.1.time_series_and_autocorrelations.Rmd](day_2/7.1.time_series_and_autocorrelations.Rmd)
    - [7.2.forecasting.Rmd](day_2/7.2.forecasting.Rmd)
    - [7.3.time_series_with_tidymodels.Rmd](day_2/7.3.time_series_with_tidymodels.Rmd)
 
**Day 3**

 - Lecture 8: Introduction to Linear Mixed Models
 - Lab 8: Linear Mixed Models
     - [8.1 Day3_Analysis_Lab8-Lab11](https://github.com/filippob/longitudinal_data_analysis/blob/main/day_3/Day3_lab8_start.Rmd)
       
 - Lab 9: Testing for the effects of variables in R
 - Lab 10: Group effect and Interaction between time and group in R
 - Lab 11: Parametric curves and prediction of random effects in R

 - Lecture 9: Model diagnostics  
