# Ravali_Insurance_charges_Prediction_using_fitbit_data
Insurance Charges Based on Health Using Fitbit Data
This project analyzes Fitbit data to determine health insurance charges for individuals based on their fitness levels and health metrics. The key objectives were:
Analyze users' daily activity levels (step count, intensity) to assess their routines.
Examine the relationship between sleep patterns and BMI.
Evaluate how BMI, physical activity, and health insurance costs correlate.
Data
The project utilized two datasets:
Fitbit activity data from 30 users, including minute-level physical activity, heart rate, and sleep monitoring from 03/12/2016 - 05/12/2016. Source: https://www.fitabase.com/resources/knowledge-base/exporting-
data/example-data-sets/
Insurance charges for a region in the United States. Source: https://www.kaggle.com/datasets/mirichoi0218/insurance
The datasets were joined using the common BMI column.
Data Cleaning and Aggregation
The raw data was cleaned and aggregated to prepare it for analysis. This involved:
Joining the two datasets based on user ID and BMI.
Extracting relevant columns (daily activity, intensities, steps, weight, insurance charges).
Calculating derived metrics like average step count, sleep duration, and BMI categories.
Analysis and Visualization
The cleaned data was analyzed using various techniques, and the findings were visualized using Tableau. Key analyses included:
Comparing users' daily step counts and activity intensities to assess activity levels.
1
Analyzing the relationship between sleep duration and physical activity.
Categorizing BMI and correlating it with step count and insurance charges.
The visualizations effectively conveyed the relationships between health metrics, activity levels, and insurance costs.
Key Findings
Users with higher daily step counts and activity intensities exhibited healthier routines.
1
Better sleep quality was associated with higher physical activity levels.
Individuals with higher BMIs tended to have lower activity levels and higher insurance charges due to increased health risks.
Future Work
Potential areas for future research include analyzing additional health indicators (blood pressure, cholesterol), demographic factors (age, gender), lifestyle factors (diet, smoking), pre-existing conditions, and exploring advanced health tracking technologies.
