# Performance Analysis of Professional Cycling Riders

This repository contains the complete statistical analysis conducted for the  
**TU Dortmund University – M.Sc. Data Science Application Report (Summer Semester 2026)**.

The project investigates whether statistically significant differences exist between
professional cycling rider classes and how rider specialization interacts with different
stage types in a multi-stage tour.

---

## Project Summary

Using data from a cycling manager game simulation, this project applies descriptive and
inferential statistical methods to analyze performance patterns across rider and stage
classes. The analysis is designed to meet academic standards for statistical reporting and
ensures full reproducibility of all results.

---

## Dataset

- 3,496 stage-level observations  
- 184 riders  
- 19 stages  
- Rider classes: All Rounder, Climber, Sprinter, Unclassed  
- Stage classes: Flat, Hills, Mountain  
- No missing values  

---

## Methods

- Descriptive statistics (mean, median, variance, skewness, kurtosis)
- Graphical analysis using box plots
- Shapiro–Wilk tests for normality assessment
- Kruskal–Wallis tests for group comparisons
- Mann–Whitney U tests with Bonferroni correction for post-hoc analysis
- Effect size estimation using η²

---

## Key Results

- Rider class significantly influences performance outcomes.
- All Rounders exhibit the highest overall performance, followed by Climbers, Sprinters, and
  Unclassed riders.
- Performance strongly depends on stage type:
  - Sprinters dominate flat stages
  - Climbers and All Rounders perform best on mountain stages
- Significant interaction effects confirm the impact of rider specialization.

---

## Source Code

The repository contains all scripts and notebooks required to reproduce the statistical
analysis, figures, and tables presented in the report.

---

## Academic Context

This project was completed as part of the application process for the  
**M.Sc. Data Science program at TU Dortmund University** and is intended for academic
evaluation purposes.
