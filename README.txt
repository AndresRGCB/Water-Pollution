
# Water Quality Evaluation using Machine Learning

This project uses various machine learning techniques to evaluate pH levels in coastal water quality data. The analysis includes clustering and regression techniques applied to data from both Mexican and U.S. coastal regions. The study focuses on uncovering patterns in water quality over time and across different locations.

## Team Members

- Brenda Eloisa Sánchez Pichardo [A01637814]
- Ilse Karena de Anda García [A01637814]
- Andres Robles Gil Candas [A01704315]
- Iván Miguel García López [A01686450]

## Project Overview

This project aims to provide insights into water quality trends in coastal regions, specifically focusing on pH levels. The following machine learning techniques were used:

- **Clustering**: Identifies natural groupings based on geographic and temporal attributes.
- **Regression Analysis**: Models temporal trends in pH levels for predictive insights.

## Datasets

- **CONAGUA Dataset**: Coastal water quality data collected by the National Water Commission (Comisión Nacional del Agua) of Mexico.
- **USA Dataset**: Additional coastal data points from the Gulf of Mexico.

### Key Variables from CONAGUA Dataset:

- Latitude, Longitude
- pH Levels
- Water Temperature
- Various Chemical Indicators (Nitrites, Nitrates, Phosphates, etc.)

## Requirements

To run the notebook, you will need the following Python libraries:

\`\`\`bash
pandas
numpy
matplotlib
scikit-learn
scipy
\`\`\`

## How to Use

1. **Clone the Repository**

   Clone this repository to your local machine using:

   \`\`\`bash
   git clone https://github.com/yourusername/WaterQualityML.git
   \`\`\`

2. **Install Dependencies**

   Install the required Python libraries:

   \`\`\`bash
   pip install pandas numpy matplotlib scikit-learn scipy
   \`\`\`

3. **Dataset Setup**

   Ensure that the dataset files (`CONAGUA` and `USA`) are available in the working directory. Load them in the notebook using the appropriate file paths.

4. **Run the Notebook**

   Open the provided Jupyter notebook (`WATERproject_Team01.ipynb`) and run all cells to:

   - Explore the dataset
   - Perform clustering and regression analysis
   - Visualize the results

## Methodology

The methodology is structured into several key phases:

1. **Dataset Exploration**: Understanding the dataset's structure, variables, and distribution.
2. **Data Preprocessing**: Handling missing values, standardizing formats, and integrating the CONAGUA and USA datasets.
3. **Clustering Analysis**: Using the K-Means and K-Nearest Neighbors (KNN) algorithms to group data points by geographic and temporal patterns.
4. **Regression Analysis**: Applying Ridge and Linear regression models to predict future pH levels.

## Results and Discussion

- **Clustering Analysis**: Identified natural groupings of pH levels in different geographic regions and time periods.
- **Regression Analysis**: Showed temporal trends in pH levels, offering insights into potential future water quality issues.

## Conclusion

The project successfully applied machine learning techniques to analyze pH levels in coastal water, providing insights into patterns, anomalies, and future trends.

## References

Please refer to the attached report for a detailed list of references and related work.
