### Assignment Documentation

#### Objectives

The primary objectives of this assignment are:

1. Compute basic statistics (mean, median, min, max) of relevant climate variables.
2. Identify trends or patterns in the data using statistical summaries and visualizations.
3. Analyze glacier retreat and precipitation data to understand the impact of climate change in Nepal.
4. Provide insights and observations from the exploratory data analysis (EDA) process.

#### Environment Setup

To set up the environment and run the Python scripts:

1. Install the required libraries using the following command:
   ```bash
   pip install numpy pandas seaborn matplotlib geopandas rasterio
   ```
2. Ensure the dataset files are placed in the appropriate directories as specified in the code.
3. Run the Jupyter Notebook cells sequentially to execute the analysis.

#### Data Sources and Preprocessing

- **Data Sources**:

  - The data source used for this assignment was provided by our instructor. Link: https://github.com/Desmondonam/Nepal_Climate_change

- **Preprocessing Steps**:
  - The shapefile was reprojected to EPSG:4326 for consistency.
  - Raster data was read and stored along with its bounding box for visualization.
  - Glacier data was loaded and cleaned to ensure no missing values.

#### Visualizations and Their Significance

1. **Precipitation Maps**:
   - Visualized precipitation data for 2020 and 2050 overlaid on Nepal's map.
   - Significance: Highlights spatial distribution and changes in precipitation over time.
2. **Glacier Retreat Comparison**:
   - Bar chart comparing glacier retreat in 2020 and 2050.
   - Significance: Demonstrates the increase in glacier retreat due to climate change.
3. **Glacier Locations**:
   - Map showing the locations of glaciers in Nepal.
   - Significance: Provides spatial context for glacier retreat analysis.
4. **Distributions of Glacier Retreat and Percentage Increase**:
   - Histograms showing the distributions of retreat values and percentage increase.
   - Significance: Identifies patterns and variability in glacier retreat data.
5. **Correlation Matrix**:
   - Heatmap showing correlations between retreat values and percentage increase.
   - Significance: Reveals relationships between variables, such as strong correlation between retreat values in 2020 and 2050.

#### Findings from EDA

1. **Summary Statistics**:
   - The mean glacier retreat was 16.18 in 2020 and is projected to increase to 25.31 by 2050.
   - The percentage increase in retreat ranges from 33.7% to 79.3%, with a mean of 56.95%.
2. **Missing Values**:
   - No missing values were found in the dataset.
3. **Distributions**:
   - Retreat values for 2020 and 2050 are right-skewed, indicating a few glaciers with significantly higher retreat.
   - Percentage increase has a relatively normal distribution but with some higher values near 80%.
4. **Correlation Analysis**:
   - Strong correlation (0.94) between retreat values in 2020 and 2050, indicating consistent trends in glacier retreat.
   - Weak correlation between percentage increase and retreat values, suggesting variability in percentage increase.

This analysis provides valuable insights into the impact of climate change on Nepal's glaciers and precipitation patterns, aiding in further research and policy-making.
