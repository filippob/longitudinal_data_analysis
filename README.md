# Analysis of longitudinal data
Scripts for the analysis of longitudinal data in Python

**Material for the Course "Machine learning for longitudinal data with Python"**

Instructors: *Filippo Biscarini, Nelson Nazzicari*

This course will introduce students, researchers and professionals to the analysis of longitudinal data, i.e. data with a time component. The course will describe the main types of longitudinal data (e.g. treatments over timepoints, time series data), and a number of approaches to process and analyse such data.

Each day the course will start at **14:00** and end at **20:00** (CET).
As a general rule, we'll have a longer break (30 minutes) at about 16:30-17:00 and two shorter breaks (10-15 minutes) later on during the day (to be decided flexibly depending on the sessions).  

<!-- timetable: [here](https://docs.google.com/) -->

**Day 1**

- Lecture 0: General Introduction / Overview of the Course [Filippo]
    - [General Introduction](slides/1.introduction.pdf)
- Lecture 1: [Longitudinal data: examples and challenges](slides/1.longitudinal_data.pdf) [Filippo]
- Lab 0: Brushing up basic Python [Filippo]
    - [0.basic_python.ipynb](day_1/0.basic_python.ipynb)
- Lab 1: First encounter with longitudinal data [Filippo]
    - [1.longitudinal_data.ipynb](day_1/1.longitudinal_data.ipynb)
    - [1.2.confounding.ipynb](day_1/1.2.confounding.ipynb)
- Lecture 2: [The basic experimental setting: treatments and timepoints](slides/2.treatments_and_timepoints.pdf) [Filippo]
- Lab 2: Treatments and timepoints in R [Filippo]
    - [2.treatments_and_timepoints.ipynb](day_1/2.treatments_and_timepoints.ipynb)
    <!-- - [2.2.exercise.Rmd](day_1/2.2.exercise.Rmd)
    - [2.3.linear_regression_with_tidymodels.Rmd](day_1/2.3.linear_regression_with_tidymodels.Rmd) -->
- Lecture XX: [The machine learning perspective - part 1](slides/) [Nelson]

 
**Day 2**

- Lecture 3: [Analysis of repeated records](slides/3.repeated_records.pdf) [Filippo]
- Lab 3: Models to analyse data with repeated records over time (multiple time points) and space (multiple locations) in R
    - [3.repeated_records.ipynb](day_2/3.repeated_records.ipynb)
- Lecture 4: [Difference-in-differences (diff-in-diff)](slides/4.difference_in_differences.pdf) [Filippo]
- Lab 4: diff-in-diff in R
    - [4.diff-in-diff.ipynb](day_2/4.diff_in_diff.ipynb)
 
**Day 3**

- Lecture 5: [Cross-validation: simple and with spatial, temporal (or other) data structure](slides/6.cross-validation_with_data_structure.pdf)
- Lab 5: Cross-validation strategies in Python
    - [5.1.cross_validation.ipynb](day_3/5.1.cross_validation.ipynb)
    - [5.2.block_cross_validation.ipynb](day_3/5.2.block_cross_validation.ipynb)
 
**Day 4**

- Lecture 6: [Time series and forecasting](slides/7.time_series_and_forecasting.pdf)
- Lab 6: Time series and forecasting in Python
    - [6.1.time_series_and_autocorrelations.ipynb](day_4/6.1.time_series_and_autocorrelations.ipynb)
    - [6.2.forecasting.ipynb](day_4/6.2.forecasting.ipynb)

[OPTIONAL]
- Lectures:
    - [Censored data and survival analysis](slides/5.censored_data_and_survival_analysis.pdf)
- Labs:
    - [5.survival_analysis.Rmd](day_2/5.survival_analysis.Rmd)
    - [7.3.time_series_with_tidymodels.Rmd](day_2/7.3.time_series_with_tidymodels.Rmd)
