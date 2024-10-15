# Used Car Price Prediction Project

## Overview

This project aims to predict the price of used cars using a dataset sourced from Kaggle. It leverages various machine learning models to analyze the relationship between vehicle features such as mileage, make, model, year, and price. By building predictive models, the project helps understand the factors influencing car pricing, which can be useful for online car marketplaces, dealerships, and individual buyers or sellers.

## Dataset

The dataset used in this project comes from a Kaggle competition. It contains numerous features related to used cars, including:

-   **Make and Model**: The brand and type of car.
-   **Year**: The year of manufacture.
-   **Mileage**: The distance the car has been driven.
-   **Engine Size**: The capacity of the car's engine.
-   **Transmission Type**: Automatic or manual, among others.
-   **Fuel Type**: Petrol, diesel, electric, etc.

You can access the dataset from the Kaggle competition [here](https://www.kaggle.com/competitions/playground-series-s4e9/overview).

## Dependencies

To run this project, you need the following Python libraries installed:

-   **Pandas**: For data manipulation.
-   **Numpy**: For numerical computations.
-   **Matplotlib & Seaborn**: For creating visualizations.
-   **Scikit-learn**: For preprocessing and building models.
-   **LightGBM**: For gradient boosting.

You can install these dependencies using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm
```

## How to Run

1. **Clone the Repository**: Clone the project to your local machine.

    ```bash
    git clone <repository-url>
    ```

2. **Install Dependencies**: Install the necessary Python libraries listed above.

3. **Open the Notebook**: Use Jupyter Notebook or Jupyter Lab to open the `main.ipynb` file.

4. **Run the Cells**: Execute each cell in the notebook to load data, preprocess, visualize, and train models.

## Results

The project aims to achieve an accurate model that can predict the price of used cars based on various features. The LightGBM model was chosen as the best-performing model due to its efficiency and accuracy.

## Acknowledgments

This project uses data from Kaggle. Thanks to Kaggle for providing the dataset.
