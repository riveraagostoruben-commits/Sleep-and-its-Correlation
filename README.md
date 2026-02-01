# Sleep-and-its-Correlation

Project Summary

Does a larger brain mean more sleep? This project dives into the biological data of various mammal species to find the statistical links between body mass, brain weight, life span, and sleep patterns (Total Sleep vs. Dreaming Sleep).

Research Questions

- What is the relationship between body weight and brain weight across species?
- Do larger animals sleep more or less than smaller ones?
- How does dreaming (REM) sleep correlate with a species' overall life expectancy?

Data Analysis 

- Data Acquisition: Streamlined data loading using the `kagglehub` API.
- Statistical Profiling: Utilized `data.corr()` to generate a comprehensive correlation matrix.
- Visual Analytics: 
    - Created Heatmaps to identify positive and negative biological drivers.
    - Used Scatter Plots to visualize the 0.93 correlation between body and brain mass.

Key Results

- Brain-Body Link: Confirmed a nearly linear relationship (0.93) between body and brain size.
- The Sleep Paradox: Found a negative correlation between body size and total sleep, suggesting that larger mammals typically require fewer hours of rest.

Technologies 

- Python
- Pandas
- Seaborn & Matplotlib
