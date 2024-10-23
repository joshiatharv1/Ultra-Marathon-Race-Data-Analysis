# Ultra-Marathon-Race-Data-Analysis
This project demonstrates my ability to work with large datasets, clean and preprocess data, and generate actionable insights through data visualization. The analysis helped reveal patterns in ultra-marathon performance over time.  Technologies: Python, Pandas, Seaborn, Jupyter Notebook.


# Ultra-Marathon Race Data Analysis

## Project Overview
This project is a comprehensive exploratory data analysis (EDA) of ultra-marathon race records from 1798 to 2022, focusing on identifying trends in race performance by race length, athlete gender, and race season. The dataset contains records from public websites and includes details on athlete performance across various races.

### Key Highlights:
- Cleaned and preprocessed the dataset for analysis by removing irrelevant columns, correcting data types, and handling null values.
- Visualized key trends using Python's Pandas and Seaborn libraries, including athlete speed vs. race length, age, and gender.
- Investigated race performance based on seasons and gender, with a focus on the 50-mile ultra-marathon races.

## Dataset
The dataset contains ultra-marathon race records over a period of more than two centuries. Key features include race name, race length, athlete speed, gender, and race date.

## Data Cleaning and Preparation
- Dropped irrelevant columns: `Athlete Clubs`, `Country`, `Age Category`, `Year of Birth`.
- Corrected column names and data types for consistency.
- Removed null values to ensure a cleaner dataset for analysis.
  
## Analysis and Insights
1. **Race Length Distribution**:
    - Histograms to visualize the distribution of race lengths.
    - Plots to show race length distribution segmented by athlete gender.

2. **Speed Analysis by Gender and Race Length**:
    - Violin plots and regression analysis to examine how gender and age impact average speed in various race lengths.
    - Seasonal trends in athlete speed for 50-mile ultra-marathon races.

3. **Performance by Season**:
    - Investigated the impact of seasons (Spring, Summer, Fall, Winter) on 50-mile race performance. 
    - Aggregated athlete average speed by season to determine the best and worst performing groups.

## Technologies Used
- **Python**: Used for data manipulation and analysis.
- **Pandas**: Data cleaning, preprocessing, and aggregation.
- **Seaborn**: Visualization of data to identify trends and relationships.
- **Jupyter Notebook**: For running and documenting the analysis process.

## How to Run
1. Clone this repository:  
    ```bash
    git clone https://github.com/username/ultra-marathon-analysis.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Open the Jupyter Notebook and run the analysis:
    ```bash
    jupyter notebook ultra-marathon-analysis.ipynb
    ```

## Insights
- **Best performing groups** in 50-mile races are typically male athletes racing in the Winter season.
- **Worst performing groups** are female athletes racing in the Summer season, where heat and conditions may affect performance.

## Future Work
- Incorporate more detailed performance metrics.
- Analyze how athlete training and preparation may influence race results.

## Author
Atharv Joshi
