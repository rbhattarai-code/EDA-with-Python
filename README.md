Car Dataset Exploratory Data Analysis (EDA)
Project Overview

This project involves performing Exploratory Data Analysis (EDA) on a dataset of cars. The analysis includes cleaning the data, handling missing values, identifying outliers, and visualizing key insights using Python libraries like pandas, matplotlib, and seaborn.
Key Objectives:

    1.  To clean and prepare the data for analysis by removing duplicates and handling missing values.
    2. To analyze the relationships between various car attributes (like MSRP, Year, Transmission Type, etc.).
    3. To identify outliers in the dataset and understand their significance.
    4. To visualize the data using scatter plots, histograms, and heatmaps.

Dataset

The dataset consists of several columns such as:

    Make: Manufacturer of the car.
    Model: The model name of the car.
    Year: The manufacturing year.
    Transmission Type: The type of transmission (e.g., automatic, manual).
    Driven Wheels: Type of drive system (e.g., front-wheel, rear-wheel).
    Vehicle Size & Style: Categorization based on the car size and style.
    MSRP: Manufacturer’s suggested retail price.

Key Findings

    Outlier Detection:
        Outliers were identified in the MSRP column. The highest value was $2,065,902, which was verified as accurate and not due to data entry errors. The lowest value was $2000, attributed to a Dodge vehicle, and was also accurate.
    Data Cleaning:
        Null values were handled by either removing rows or filling in missing data where appropriate.
        Duplicates were identified and removed based on a subset of columns (Make, Model, Year, etc.).
    Visualizations:
        Scatter Plots: Showed relationships between Driven Wheels and MSRP.
        Histograms: Displayed the frequency distribution of MSRP values.
        Heatmaps: Highlighted correlations between different numeric features.

Visualizations

Some key visualizations used in this project:

    Boxplot: To visualize the spread and identify outliers in the MSRP column.
    Scatter Plot: To understand the relationship between Driven Wheels and MSRP.
    Histogram: To check the distribution of car prices (MSRP).
    Heatmap: To observe correlations between features like MSRP, Year, etc.

Tools & Libraries

The following Python libraries were used for this analysis:

    Pandas: For data manipulation and analysis.
    Matplotlib: For creating static, animated, and interactive visualizations.
    Seaborn: For statistical data visualization.

Conclusion

This project provided insights into how different car attributes affect their market price (MSRP). Handling outliers and cleaning data were key tasks, and visualizations helped uncover patterns and trends in the dataset.
