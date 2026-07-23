## About
Customer segmentation is a critical aspect of modern business intelligence, especially for e-commerce platforms aiming to optimize marketing strategies and improve customer experience. This research explores the application of the KMeans clustering algorithm for customer segmentation based on purchasing behavior. The project is implemented using Python's Flask web framework and integrates data preprocessing, clustering, visualization, and interactive user interfaces. The system allows businesses to upload customer datasets and automatically generate insights through clustering, visual analytics, and downloadable reports.

## Methodology
- Data Collection: User uploads a CSV file with customer features.
- Preprocessing: Missing values are handled, and numerical features are standardized.
- Clustering: KMeans algorithm is applied. The optimal number of clusters is determined using the Elbow Method.
- Evaluation: Silhouette Score is used to evaluate cluster quality.
- Visualization: Results are displayed via pie charts, bar graphs, and PCA-based cluster plots.

## System Architecture
- Frontend: HTML, Tailwind CSS
- Backend: Flask (Python)
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, FPDF

## Results
Upon testing with realistic datasets, the system successfully identified 4 distinct customer groups: Budget Shoppers, High Spenders, Occasional Buyers, and Loyal Customers. The visual output helps business owners quickly understand the distribution and characteristics of each group. A toggle feature enables detailed views for data science students, while business owners can view simplified insights

## Future Scope
- Integration of dynamic clustering (e.g., DBSCAN or hierarchical methods)
- Real-time customer feedback loop
- Integration with sales forecasting systems
- Multilingual and mobile-responsive interface


