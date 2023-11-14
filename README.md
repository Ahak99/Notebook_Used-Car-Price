# Used Car Price

### Objectives
    1. The provided contains various details and attributes associated with used cars. The target variable, which is the central focus of analysis, is the price of the used cars, and it is measured in lakhs.
    2. So, I tested several regression algorithm, and I used RandomSearch method to select the best set of parameters for my predictive model.

### Life cycle of project
    1. Install the dependencies
    2. Collect data
        - Dataset source : Dataset Source - https://www.kaggle.com/datasets/sujay1844/used-car-prices
        - The dataset was stored in Amazon S3.
    3. Read data
    4. Data Checks to perform
        - Check Missing values.
        - Check Duplicates.
        - Check data type.
        - Check the number of unique values of each column.
        - Check statistics of data set.
        - Check various categories present in the different categorical column.

    3. Data Analysis & Visualisation (more details in the notebook)

    5. Model building
        - Split data into Training/Testing set
        - Normalize data.
        - Train the model and use the random search method to select the best set of parameters.
        - Save the model
        - Predict

### Software and tools requirements

    1. Github
    2. Jupyter or Google Colab
