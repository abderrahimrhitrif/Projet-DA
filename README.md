# Sales Data Analysis and Prediction

This project focuses on analyzing and predicting sales trends for various clothing categories—pants, sweaters, and dresses—using statistical and machine learning techniques.

## Features

1. **Data Processing**:
   - Handles duplicate and missing values.
   - Removes outliers using the IQR method.
   - Centers and standardizes numerical data for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizes sales data trends using horizontal box plots.
   - Investigates relationships between variables with scatter plots.

3. **Statistical Analysis**:
   - Calculates Pearson correlation coefficients.
   - Visualizes correlations with heatmaps.
   - Tests hypotheses about mean differences between datasets.

4. **Dimensionality Reduction**:
   - Implements PCA (Principal Component Analysis) manually.
   - Projects data onto principal components for visualization and analysis.

5. **Linear Regression**:
   - Builds and evaluates linear regression models for sales predictions.
   - Uses metrics like MSE, MAE, RMSE, and R² to assess performance.

## Dataset

The project utilizes sales data stored in `DataSetVentes.xlsx`, with separate sheets for pants, sweaters, and dresses.

### Example Data Format:
| Date       | Sales (Billion Yuan) | X4 (Billion) | X8 (10 Million) | X9 (100 Thousand) | X10 (Million) |
|------------|----------------------|--------------|------------------|-------------------|----------------|
| 2016-05-01 | 2.23                | 3.84         | 1.48            | 1.12              | 1.19           |

## Visualizations

- Box plots for each feature in all categories.
- Scatter plots to analyze relationships.
- Correlation heatmaps to identify trends.

### Example Visualization:
![Sample Box Plot](output_8_0.png)

## Project Highlights

1. **Data Cleaning**:
   - Removes duplicates and handles outliers effectively.
2. **Dimensionality Reduction**:
   - PCA reduces data complexity while preserving variance.
3. **Regression Analysis**:
   - High prediction accuracy for sweater sales (R² = 0.94).

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url/sales-analysis.git
   ```
2. Run the analysis script:
   ```bash
   python main.py
   ```

## Dependencies

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - scipy

## Results

- Hypothesis testing showed significant differences in sales means across categories.
- PCA identified principal components capturing over 97% variance.
- Linear regression models achieved accurate predictions:
  - Sweater sales: R² = 0.94
  - Pants sales: R² = 0.65
  - Dress sales: R² = 0.83

## Contribution

Feel free to open issues or create pull requests to enhance the project.

## License

This project is licensed under the MIT License.
