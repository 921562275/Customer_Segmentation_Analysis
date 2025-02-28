# Customer Segmentation Analysis with Interactive Dashboard

## Overview
This project performs customer segmentation using K-means clustering on the Mall Customers dataset. It identifies distinct customer groups based on age, annual income, and spending score, enhanced with an interactive 3D dashboard built using Plotly.

## Objectives
- Segment customers for targeted marketing strategies.
- Provide actionable business insights based on cluster characteristics.
- Showcase data analysis and interactive visualization skills.

## Dataset
- **Source**: [Mall Customer Segmentation Data (Kaggle)](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features**: Age, Annual Income (k$), Spending Score (1-100)

## Tools
- **Python**: Pandas, NumPy, Scikit-learn, Plotly
- **Environment**: Jupyter Notebook

## Methodology
1. **Data Preprocessing**: Standardized features (Age, Income, Spending Score).
2. **Exploratory Analysis**: Visualized raw data in an interactive 3D scatter plot.
3. **Clustering**: Applied K-means with k=5, optimized using Elbow Method and Silhouette Score.
4. **Visualization**: Created an interactive 3D dashboard with Plotly.
5. **Insights**: Summarized cluster profiles and provided marketing recommendations.

## Results
- Identified 5 customer segments (e.g., young high-spenders, high-income low-spenders).
- Interactive dashboard (`customer_segments.html`) allows exploration of clusters.
- Sample marketing recommendation: Offer premium products to high-spending clusters.

## Files
- `customer_segmentation.ipynb`: Full code and analysis.
- `Mall_Customers.csv`: Dataset.
- `customer_segments.html`: Interactive 3D dashboard.

## Usage
1. Install dependencies: `pip install pandas numpy scikit-learn plotly`.
2. Run `customer_segmentation.ipynb` in Jupyter Notebook.
3. Open `customer_segments.html` in a browser to explore the dashboard.

## Future Improvements
- Incorporate gender as an additional feature.
- Integrate with a web app using Dash for real-time filtering.