                                                            ## DataPrep v0.2 ##

DataPrep is a GUI-based Python application for preprocessing tabular data, specifically designed to handle missing values, zero-variance features, and high-correlation removal. It allows users to load CSV/Excel files, configure preprocessing settings, and save processed data.


## Features
- Load CSV (Preferred)/Excel files for processing.
- Select index and dependent columns.
- Choose the correlation method (Pearson, Spearman, Kendall).
- Set correlation and covariance cutoff values.
- Choose processing method (SIMPLE, SPARC, SWAPCo).
- Remove missing columns and low variance features.
- Save processed data in CSV/Excel format.
- About and Info sections for user guidance.


## GUI Overview
- File Selection: Browse and load the input data file.
- Index Column & Dependent Column: Dropdowns to select columns.
- Correlation Method: Choose Pearson, Spearman, or Kendall.
- Correlation & Covariance Cutoff: Set threshold values.
- Processing Method: Select from Remove Null Vars, SIMPLE, SPARC, or SWAPCo.
- Preprocessing & Saving: Buttons to start and save processed data.
- About & Info: Displays additional information about the application.


## Usage:
1. Browse and select an input CSV/Excel file.
2. Choose index and dependent columns.
3. Set correlation method, correlation cutoff, and covariance cutoff values.
4. Select a processing method (Remove Null, SIMPLE, SPARC, or SWAPCo).
5. Click **Start Preprocessing** to process the data.
6. Save the processed data using the **Save Reduced Data** button.


## Sources:
https://stackoverflow.com/questions/29294983/how-to-calculate-correlation-between-all-columns-and-remove-highly-correlated-on)

https://pandas.pydata.org/docs/

https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.VarianceThreshold

https://docs.python.org/3/library/tkinter


## Developed by
 SUVANKAR BANERJEE 
 suvankarbanerjee1995@gmail.com
 
 Research Scholar, Natural Science Laboratory, Division of Medicinal Chemistry, Department of Pharmaceutical Technology, Jadavpur University, Kolkata, INDIA, PIN: 700060.
 
 Assistant Professor, School of Pharmacy, The Neotia Univesity, Jhingar pole, Jhinga, Sarisha, Diamond Harbour Road, 24 Parganas (South), West Bengal, INDIA, PIN: 743368.
