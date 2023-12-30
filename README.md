# Projects
This repository contains a collection of my professional projects, which I have created to demonstrate my skills and experience in software development.

# Python Software for managing a vegan product store.
Certainly, here's the revised project summary for the "Vegan Store Management Software" project in Python without the example interactions:

Title: Vegan Store Management Software in Python

Description:

Welcome to the "Vegan Store Management Software" project, a text-based application for efficiently managing a vegan product store. This software provides a range of features to streamline store operations:

Key Features:

    Product Management: Easily register new products with details such as name, quantity, purchase price, and selling price.

    Product Listing: View a comprehensive list of all products in the store.

    Sales Registration: Record sales transactions, keeping track of product quantities sold.

    Profit Calculation: Calculate both gross and net profits, accounting for product costs.

    Command Menu: An interactive command-line interface makes it simple to interact with the software.

Project Guidelines:

    Code Structure: The project emphasizes good code organization, including the use of functions to encapsulate different functionalities.

    Data Structures: Thoughtful selection of data structures such as lists, dictionaries, or combinations thereof, to efficiently manage product data.

    Persistence: The program ensures data persistence, retaining user input between program runs, by utilizing a text file with customizable encoding for data storage.

    Input Validation: Robust input validation is in place, guaranteeing that numerical inputs are indeed numbers, and handling invalid cases with meaningful exceptions and error messages.

    Stock Verification: During purchases, the software checks whether the purchased products are in stock and provides an error message if not available.

    Stock Updates: When adding products to the stock, the software checks if the product is already in stock. If so, it updates the existing quantity without the need to re-enter purchase and selling prices.

    Profit Calculation: The software calculates gross profit as the total sales revenue and net profit as gross profit minus the cost of purchased products.

Project Reminders:

    It's essential to strictly adhere to project specifications to meet the desired outcomes and produce results as specified in the project guidelines.

    Ensure that each function performs a single, specific task. Divide long functions into smaller, more concise ones if necessary.

    Comments should be used to describe functions, classes, and methods.

    Use English for variable, function, and method names, following snake_case for variables and camelCase for class names. Maintain a consistent use of the English language throughout the project.

This project is a valuable exercise in building a functional, persistent, and user-friendly application in Python for managing a vegan product store. Happy coding!

# Descriptive Statistical Analysis and Visualization of Texas Real Estate Sales Data Using R.
Title: Exploring Texas Real Estate Sales Data with Descriptive Statistics and Data Visualization in R

Description:

Welcome to the "Exploring Texas Real Estate Sales Data" project! This repository contains a comprehensive analysis of real estate sales data in Texas using the R programming language.

Project Highlights:

    Dataset: We start by downloading and importing the "realestate_textas.csv" dataset, which includes information on property sales in various Texas cities. The dataset features key variables such as city, year, month, sales, volume, median price, listings, and months of inventory.

    Data Exploration: We conduct an in-depth exploration of the dataset, identifying variable types and calculating position, variability, and shape indices where applicable. For other variables, we create frequency distributions to gain a comprehensive understanding.

    Variability and Asymmetry: We identify the variable with the highest variability and the most asymmetric variable, providing insights into the data's characteristics.

    Data Visualization: Utilizing the power of R and the ggplot2 package, we create visually appealing and informative data visualizations. These include box plots comparing median prices among cities, box plots analyzing total sales value across cities and years, and bar charts to assess sales trends across months and years in different cities.

    Customization: We go beyond the basic solutions and customize our graphs by playing with themes, colors, labels, axes, and legends, resulting in visually stunning and insightful visuals.

    Gini Index: We calculate the Gini index for selected variables, providing an additional layer of analysis.

    Statistical Summaries: Leveraging the dplyr package, we compute summary statistics, such as mean and standard deviation, for specific variables. These summaries are organized by city, year, and month.

This project is a journey through the world of descriptive statistics and data visualization, offering valuable insights into the Texas real estate market. Whether you're a data enthusiast, a statistician, or just curious about real estate trends, this repository is a treasure trove of information and engaging visuals.

Feel free to explore, adapt, and expand upon the analyses and visualizations in this repository to suit your needs. Happy data exploration!

Creating a README for your statistical project on predicting neonatal weight would be beneficial for your portfolio. However, as an AI, I can't directly generate files like Word, PDF, or Markdown. Instead, I can guide you on how to structure the README and provide insights into what each section could contain:

# Statistical Model for Predicting Neonatal Weight

#### Introduction
This project aims to develop a statistical model to predict the weight of newborns based on various factors collected from three hospitals with 2500 neonatal records.

#### Dataset Description
- **File**: `neonati.csv`
- **Variables**:
  - Mother's age
  - Number of pregnancies
  - Mother smoking (0=NO, 1=YES)
  - Weeks of gestation
  - Weight in grams of the newborn
  - Length in mm of the newborn
  - Diameter in mm of the newborn's skull
  - Type of delivery: Natural or Cesarean
  - Hospital: 1, 2, 3
  - Sex of the newborn: M or F
- **Objective**: Explore if it's possible to predict neonatal weight given other variables, particularly studying the maternal variables for potential significant effects (e.g., the potentially harmful effect of smoking).

#### Data Analysis Steps
1. **Data Import**: Import the `neonati.csv` dataset and verify its correct reading.
2. **Descriptive Analysis**: Describe the dataset's composition, variable types, and the study's objective.
3. **Exploratory Data Analysis (EDA)**: Conduct a brief descriptive analysis using indices and graphical tools.
4. **Hypothesis Testing**: Test if the sample means of weight and length significantly differ from the population.
5. **Sex-Based Analysis**: Check for significant differences in weight and length between sexes.
6. **Hospital Cesarean Rate Hypothesis**: Investigate if there are significant differences in Cesarean rates among hospitals.

#### Multivariate Analysis
1. **Regression Model**: Create a multiple linear regression model using all variables and interpret the coefficients and results.
2. **Model Selection**: Utilize various selection criteria and explain their significance.
3. **Nonlinear Effects and Interactions**: Consider nonlinear effects or interactions between variables.
4. **Residual Analysis**: Conduct a thorough diagnostic of the model's residuals and identify influential values.
5. **Predictive Performance**: Assess the model's suitability for predictions.
6. **Prediction Example**: Make a prediction for the weight of a third pregnancy at the 39th week, considering no ultrasound measurements.

#### Visualization and Additional Analysis
1. **Model Visualization**: Create graphical representations aiding in visualizing the model.
2. **Out-of-the-Box Analysis**: Encourage unconventional analyses and considerations.
3. **Resources Used**: Mention any R packages or functions utilized for enhanced analysis.
4. **Support and References**: Provide guidance on using R's integrated manual or external resources.


