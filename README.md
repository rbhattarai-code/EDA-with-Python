Car Dataset Exploratory Data Analysis (EDA)
Project Overview

This project is focused on performing Exploratory Data Analysis (EDA) on a comprehensive car dataset sourced from Kaggle. Through this analysis, I aim to uncover insights about various car attributes, such as the make, model, year, fuel type, engine specifications, and pricing (MSRP). The project enhances my data analysis skills using Python, Pandas, and Matplotlib.
Dataset Description

The dataset contains 16 columns related to various data of cars:

    Make: The company that manufactures the car.
    Model: The specific model of the car.
    Year: The year the car was manufactured.
    Engine Fuel Type: The type of fuel the car uses.
    Engine HP: Horsepower of the car's engine.
    Engine Cylinders: The number of cylinders in the car's engine.
    Transmission Type: The type of transmission the car uses.
    Driven Wheels: Whether the car is rear-wheel drive, front-wheel drive, or all-wheel drive.
    Number of Doors: The number of doors the car has.
    Market Category: The car’s market category (e.g., luxury, crossover).
    Vehicle Size: Size of the car (compact, midsize, etc.).
    Vehicle Style: Style of the car (SUV, sedan, etc.).
    Highway MPG: Fuel efficiency in miles per gallon on the highway.
    City MPG: Fuel efficiency in miles per gallon in the city.
    Popularity: Popularity score of the car.
    MSRP: Manufacturer's suggested retail price.

Key Steps

    Data Cleaning:
        Removed duplicate records based on important features like Make, Model, Year, etc.
        Handled missing values by removing or imputing null values in key columns such as Engine Fuel Type, Engine HP, and Engine Cylinders.

    Visualization & Analysis:
        Outliers: I identified outliers in the MSRP (price) column and verified that both the highest and lowest values (e.g., a buggati priced at $2,065,902 and a Dodge priced at $2,000) were accurate.
        Scatter Plots: Visualized relationships between MSRP and features like Driven Wheels to observe trends and clusters.
        Bar Graphs: Used bar graphs to show the frequency of car manufacturers (Make) and other categorical variables.
        Heatmap: Built a heatmap to show correlations between numerical variables like Engine HP, city mpg, and highway MPG.

    Findings:
        Outliers: Identifying and analyzing the outliers helped me distinguish between human errors and legitimate extreme values, crucial in ensuring data accuracy.
        Trend Insights: Scatter plots and bar graphs helped me uncover trends in car pricing, efficiency, and popularity across different car types.

Tools Used

    Python: Core language for the project.
    Pandas: Used for data manipulation and cleaning.
    Matplotlib: Visualizing data through graphs.
    Seaborn: Enhanced visualizations such as heatmaps.

Learning Outcomes

This project allowed me to:

    Deepen my understanding of data cleaning processes, especially dealing with null and duplicate values.
    Explore how visualizations like scatter plots, bar graphs, and heatmaps can communicate complex data insights.
    Gain more experience working with outliers and understanding their impact on the analysis.

Dataset

You can find the dataset here: https://www.kaggle.com/datasets/CooperUnion/cardataset
