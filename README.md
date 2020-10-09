# Pymaceuticals-Matplotlib

# Background
Analyzed the data provided by pharmacuetical company, Pymaceuticals using pandas and matplotlib. Imported two csv.files found in the data folder, Mouse_metadata.csv and Study_results.csv using pandas. My first task was merging the data from both files into one dataframe which makes the data all accessible and able to use that to build other data frames and narrow the data. My second task was to find the one duplicate Mouse ID in the merged data frame and remove it. I found this challenging but I used this function duplicated(["Mouse ID", "Timepoint"])] to find the duplicate mouse, g989. Once the mouse was removed the total number of uniqiue mice was 248. I used a cleaner version of the merge_df going forward; having one duplicate mouse would throw off the summary statistics. Next, I used the cleaned data frame to caluculate the Avg Tumor Volume, Median Tumor Volume, Variance Tumor Volume, Standard Deviation Tumor Volume, Standard Error Tumor Volume. 

I built several other data frames most were grouped by "Drug Regimen" or had a major focus on Capomulin, Pymaceuticals' drug of interest which, were used to build various charts.

Graphs/Charts built:

Bar Chart - Number of Mice tested by Drug Regimen

Pie Chart - Percentage of mice are each Gender

Box and Whisker Plot - Tumor Volume of four frug types

Line Graph - Capolulin treatment of mouse y793

Scatter Plot










 
