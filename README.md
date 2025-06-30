# 📊 Laptop Pricing Analysis

## Project Overview

This project performs an exploratory data analysis (EDA) on a dataset of laptop prices and characteristics. It aims to:

- Understand the distribution of key variables:
  - Manufacturer
  - Screen Size (cm)
  - Price
- Compute statistical measures:
  - Central tendency (mean, median, mode)
  - Dispersion (standard deviation, variance, range, interquartile range)
  - Shape (skewness, kurtosis)
- Analyze relationships:
  - Between Manufacturer and Price
  - Between Screen Size and Price
- Visualize distributions and correlations.

---

## Task Description

> Consider the file `laptop_pricing`.
> Explore the variables: Manufacturer, Screen_Size_cm, Price.  
> Calculate in Python the measures of relative location, dispersion, and shape that make sense for each of these variables.  
> Justify whether there is any relationship between the variable Price and any of the other variables.  
> Create graphical representations of the distribution of each variable, and of the correlation between Screen_Size_cm and Price.
>
> ## Code Flow Summary

The analysis follows these steps:

| Step | Description |
|------|-------------|
| **Load Data** | Reads CSV into pandas DataFrame. |
| **Explore Manufacturer** | Shows frequency table and bar chart. |
| **Explore Screen_Size_cm** | Computes mean, median, mode, standard deviation, variance, range, IQR, skewness, kurtosis, histogram, boxplot. |
| **Explore Price** | Same statistical analysis as Screen_Size_cm. |
| **Analyze Manufacturer vs Price** | Calculates average price by manufacturer and shows boxplot. |
| **Analyze Screen_Size_cm vs Price** | Computes correlation and generates scatter plot. |

---

## Expected Outputs

Once you run the analysis, the outputs will include:

✅ Statistical summaries printed to the console  
✅ Graphs displayed:
- Manufacturer bar chart
- Histograms and boxplots for numerical variables
- Boxplot of Price by Manufacturer
- Scatter plot of Price vs Screen Size

---

## Results & Insights

_Fill in this section after running the analysis._

- **Manufacturer:**
    - Main brands present in the dataset
- **Screen Size:**
    - Typical range and distribution shape
- **Price:**
    - Price range and distribution shape
- **Manufacturer vs Price:**
    - Brands with higher or lower average prices
- **Screen Size vs Price:**
    - Correlation coefficient
    - Any visible trend?

---

## Author

[Laura Pantano]


