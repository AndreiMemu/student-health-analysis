# Student Health & Sleep Analysis

## Overview
Statistical analysis of the relationship between depression and sleep quality
in students, using Python and SciPy.

## What This Project Does
- Cleans and recategorizes raw sleep duration data into quality tiers
- Encodes ordinal sleep categories into numeric scores
- Applies a Mann-Whitney U test to determine whether sleep quality differs
  significantly between students with and without depression

## Key Finding
The Mann-Whitney U test returned a p-value of 4.47e-47, far below the 0.05
threshold. We reject the null hypothesis — there is a statistically significant
difference in sleep quality between students with and without depression.

## Tools Used
- Python
- pandas
- scipy.stats

## Dataset
Student health dataset containing depression status, sleep duration, and other
health indicators.
