# Sea Level Predictor

This project aims to predict future sea levels using historical data from NOAA. It employs linear regression to analyze trends in sea levels from 1880 to 2013 and forecasts sea levels up to the year 2050.

## Objectives:

1. **Data Preprocessing**:
    - Load the sea level data from `epa-sea-level.csv` using `pandas`.
    - Inspect and clean the data as needed for analysis.

2. **Scatter Plot Creation**:
    - Create a scatter plot to display sea level measurements over the years.

3. **Linear Regression**:
    - Fit two lines of best fit using linear regression:
      - One for the entire dataset from 1880 onwards.
      - Another starting from the year 2000 to capture more recent trends.

4. **Plot Enhancement**:
    - Label the x-axis as "Year" and the y-axis as "Sea Level (inches)".
    - Add a plot title: "Rise in Sea Level".
    - Include both lines of best fit for visual comparison.

5. **Testing**:
    - Use `unittest` to ensure that the plot is generated correctly, including the title, labels, and data points.

## Running the Project

To run this project:

1. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

2. Run the `main.py` file to generate the sea level plot:
    ```bash
    python main.py
    ```

3. To run the unit tests, use the following command:
    ```bash
    python -m unittest test_module.py
    ```

## Files in this Repository:

- `epa-sea-level.csv`: The dataset containing sea level measurements from NOAA.
- `main.py`: The entry point of the project, which generates the sea level plot.
- `sea_level_predictor.py`: Contains the main logic for plotting the sea level data and applying linear regression.
- `test_module.py`: A set of unit tests to verify the accuracy of the plot.

## Tools and Libraries:

- **Pandas**: Used for loading and manipulating the dataset.
- **Matplotlib**: For plotting the sea level data and the lines of best fit.
- **Scipy**: For performing linear regression analysis.
- **Unittest**: For validating the accuracy of the generated plots.

## Outcomes:

- A comprehensive visualization of sea level rise over time.
- Linear regression models to predict future sea levels.
- Unit tests to verify that the plot's elements, such as titles and labels, are correctly applied.

## License

This project is licensed under the MIT License.
