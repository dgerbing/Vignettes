Example web pages to illustrate lessR functions for data analysis and data visualization.

Visualization with only three functions
---------------------------------------

- `Chart()` for categorical variables:
  form = "bar", "pie", "radar", "bubble", "dot", "sunburst", "treemap", "icicle", "profile", "mosaic", "assoc"
- `X()` for a continuous variable:
  form = "histogram", "freq_poly", "density", "violin", "box", "strip", and their combination "vbs"
- `XY()` for the relationship of two continuous variables, and for a variable over time:
  form = "scatter", "contour", "smooth", "hexbin", "sunflower", plus time series with forecasting

Parameters `by` (within panel) and `facet` (between panels) stratify by the levels of categorical variables.

Data analysis and model building
--------------------------------

- `Regression()` for predicting values of a continuous variable
- `Logit()` for predicting values of a binary categorical variable
- `ttest()` for one-sample, independent-groups, and paired-samples t-tests
- `ANOVA()` for one-way, one-way with blocks, and two-way analysis of variance
- `Prop_test()` for one or more proportions, goodness-of-fit, and independence

Correlations
------------

- `Correlation()` for the correlation of two variables with its hypothesis test, or the correlation matrix of many variables
- `corEFA()` for exploratory factor analysis
- `corCFA()` for confirmatory factor analysis
- `corScree()`, `corReorder()`, `corReflect()`, and `corProp()` for working with a correlation matrix

Utilities
---------

- `Read()` and `Write()` for reading and writing data files, including Excel, csv, and R
- `pivot()` for summary statistics of variables, aggregated over groups
- `details()` for a summary of the variables in a data frame
- `recode()`, `rescale()`, `rename()`, and `order_by()` for transforming variables and data
- `reshape_long()` and `reshape_wide()` for reshaping a data frame
- `Merge()` for joining data frames
- `train_test()` for splitting data into training and testing sets
- `getColors()` and `style()` for custom colors and visual themes
