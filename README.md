## Austin, Texas Crime Analysis

### Overview
This project analyzes crime data in Austin, Texas, from 2018 to 2021. The objective is to identify the most frequent crimes and observe trends over the specified period. The analysis utilizes Python libraries such as Pandas and Matplotlib for data manipulation and visualization.

### Analysis Summary
The analysis included several key steps:

1. **Data Loading and Cleaning:**
   - Loaded the crime data from a CSV file.
   - Dropped unnecessary columns and removed duplicate entries.
   - Extracted the year from the "Occurred Date" and created a "Date Stamp" column.

2. **Filtering Data:**
   - Focused on data from 2018 to 2021.
   - Counted unique offense descriptions and identified the top 5 crimes for each year.

3. **Visualization:**
   - Created bar charts and pie charts to visualize the top 5 highest offense crimes for each year and overall.
   - Compared the total number of specific crimes (Family Disturbance, Burglary of Vehicle, Theft) across the years.

### Key Findings
- **Top 5 Crimes (2018-2021):**
  - **Overall:** Family Disturbance, Burglary of Vehicle, Theft, Criminal Mischief, Assault with Injury - Family/Dating Violence.
  - **2018:** Family Disturbance, Burglary of Vehicle, Theft, Criminal Mischief, Assault with Injury - Family/Dating Violence.
  - **2019:** Burglary of Vehicle, Family Disturbance, Theft, Criminal Mischief, Assault with Injury - Family/Dating Violence.
  - **2020:** Family Disturbance, Burglary of Vehicle, Theft, Criminal Mischief, Auto Theft.
  - **2021:** Family Disturbance, Theft, Burglary of Vehicle, Criminal Mischief, Auto Theft.

- **Yearly Crime Trends:**
  - **Family Disturbance:** Decreased from 10,636 incidents in 2018 to 9,688 in 2021.
  - **Burglary of Vehicle:** Peaked at 11,754 incidents in 2019 and significantly decreased to 5,028 in 2021.
  - **Theft:** Gradually decreased from 9,298 incidents in 2018 to 5,748 in 2021.

### Tools and Libraries
- **Pandas:** Used for data cleaning, manipulation, and analysis.
- **Matplotlib:** Utilized for creating bar charts and pie charts to visualize crime trends.
- **Hvplot, Requests, Scipy.stats:** Additional libraries for data handling and visualization.

### Instructions
1. Clone the repository.
2. Install the required dependencies.
3. Run the analysis script to see the full analysis and results.

This project provides a detailed look at crime trends in Austin, Texas, offering insights into the most frequent offenses and their changes over time. The visualizations help in understanding the data more effectively, highlighting key areas for potential policy and law enforcement focus.

---



IMPORTANT NOTE: The CSV was not uploaded with this repo only because the csv data set was too large to incorporate into github.  The official website for this data set is https://catalog.data.gov/dataset/?tags=crime&organization=city-of-austin
https://catalog.data.gov/dataset/crime-reports-bf2b7  (this is the specific one.  The first web information is the navigation page to this one)



